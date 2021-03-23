# Documentation Guide

* [About this guide](documentation-guide.md#about-this-guide)
  * [Who is this guide for?](documentation-guide.md#who-is-this-guide-for)
  * [What is it about?](documentation-guide.md#what-is-it-about)
* [Workflow](documentation-guide.md#workflow)
  * [Setup Environment](documentation-guide.md#setup-environment)
* [Style Guide](documentation-guide.md#style-guide)
  * [Headings](documentation-guide.md#headings)
  * [Lists](documentation-guide.md#lists)
    * [Ordered lists](documentation-guide.md#ordered-lists)
    * [List headings](documentation-guide.md#list-headings)
  * [Icons](documentation-guide.md#icons)
  * [Buttons](documentation-guide.md#buttons)
  * [Hints](documentation-guide.md#hints)
  * [Screenshots](documentation-guide.md#screenshots)
    * [Types of screenshots](documentation-guide.md#types-of-screenshots)
    * [Requirements for all screenshots](documentation-guide.md#requirements-for-all-screenshots)
    * [Requirements for annotated screenshots](documentation-guide.md#requirements-for-annotated-screenshots)
    * [Screenshot captions](documentation-guide.md#screenshot-captions)
    * [Bookmarlet for Screenshots](documentation-guide.md#bookmarlet-for-screenshots)

## About this guide

### Who is this guide for?

This guide is intended for parties interested in contributing to this documentation.

### What is it about?

This guide describes a recommended workflow and required conventions to be used when creating content.

## Workflow

### Setup Environment

While the online editor may be used, the most efficient way to create documentation is to install the GitBook Toolchain locally. See [https://toolchain.gitbook.com/](https://toolchain.gitbook.com/) for detailed instructions. The short version follows.

{% hint style="info" %}
The following is required:

* NodeJS \(v4.0.0 and above is recommended\)
* git
* A Markdown editor/IDE \([ATOM](https://atom.io/) is a good open source choice\)
* Windows, Linux, Unix, or Mac OS X
{% endhint %}

1. Install `gitbook-cli` using npm:

   ```bash
    $ npm install gitbook-cli -g
   ```

2. Clone the mdEditor GitBook:

   ```bash
    $ git clone https://git.gitbook.com/cookmt/mdeditor-for-lccs.git
   ```

3. Setup GitBook

   ```bash
    $ cd mdEditor-for-lccs
    $ gitbook install
   ```

4. Start the local GitBook server

   ```bash
    $ gitbook serve
   ```

5. Open a browser to: [http://localhost:4000](http://localhost:4000)

## Style Guide

This section covers styling conventions required for this documentations. Some of the conventions rely on plug-ins that enhance the native GitBook Markdown functionality. In some instances, the effects of the plugins are not displayed until after the book has been generated.

### Headings

Please use headings to define page sections. Heading levels should appear sequentially without gaps \(don't skip heading levels\). Headings should start at Level 1 for the page title. Headings should not be used purely to define font styles - if absolutely necessary, use CSS for that. Following this convention will make it possible to parse the markdown programmatically, e.g. to dynamically create a table of contents.

### Lists

#### Ordered lists

Ordered lists are processed irrespective of the actual number assigned to each list item. For Example:

```text
1. first
2. second
3. third
```

{% hint style="info" %}
1. first
2. second
3. third
{% endhint %}

is rendered the same as:

```text
1. first
12. twelfth
30. thirtieth
```

{% hint style="info" %}
1. first
2. twelfth
3. thirtieth
{% endhint %}

Therefore, one recommended convention is to use `1.` for every item in an ordered list. This makes it easier to insert or remove items from the list, at the expense of slightly less readable Markdown. If you choose to sequentially order the list items, you **must** make sure the numbers are sequential to avoid confusion.

#### List headings

Headings may be use in lists. However, special handling is required to ensure bullets for ordered lists are styled appropriately.

The `tasks` tag is available for styling "task lists". For simplicity, all of the various heading levels are styled the same.

```text
Example without task tag

1. ## Level 2
1. ### Level 3
1. ###### Level 6
```

{% hint style="info" %}
Example without task tag

1. **Level 2**
2. **Level 3**
3. **Level 6**
{% endhint %}

```text
Example with task tag

<!-- tasks -->
1. ## Level 2
1. ### Level 3
1. ###### Level 6
<!-- endtasks -->
```

{% hint style="info" %}
Example with task tag

1. **Level 2**
2. **Level 3**
3. **Level 6**
{% endhint %}

### Icons

[FontAwesome](https://fontawesome.com/v4.7.0/icons/) icons are available. Use an `<i>` tag to render the chosen icon.

```text
<i class="fa fa-smile-o"> </i> Happy Birthday <i class="fa fa-birthday-cake"></i>
```

{% hint style="info" %}
 Happy Birthday 
{% endhint %}

### Buttons

[Bootstrap 3](https://getbootstrap.com/docs/3.3/css/#buttons) style buttons are supported. Use a `<span>` tag since these are for documentation only. Icons may be combined with buttons.

Default Primary  Success Info Extra - Small Warning - Small Danger - Large Link

```markup
<!-- Standard button -->
<span class="btn btn-default">Default</span>

<!-- Provides extra visual weight and identifies the primary action in a set of buttons -->
<span class="btn btn-primary">Primary</span>

<!-- Indicates a successful or positive action -->
<span class="btn btn-success"><i class="fa fa-check"></i> Success</span>

<!-- Contextual button for informational alert messages -->
<span class="btn btn-info btn-xs">Info Extra - Small</span>

<!-- Indicates caution should be taken with this action -->
<span class="btn btn-warning btn-sm">Warning - Small</span>

<!-- Indicates a dangerous or potentially negative action -->
<span class="btn btn-danger btn-lg">Danger - Large</span>

<!-- Deemphasize a button by making it look like a link while maintaining button behavior -->
<span class="btn btn-link">Link</span>
```

### Hints

Styled hint blocks are supported.

```text
{% hint style='info' %}
Important info: this note needs to be highlighted
{% endhint %}
```

There are five supported variations.

* `info` \(default\)
* `tip`
* `danger`
* `working`
* `plain`

{% hint style="info" %}
Info: this note needs to be highlighted.
{% endhint %}

{% hint style="info" %}
Tip: 20% is customary.
{% endhint %}

{% hint style="danger" %}
Danger: this is going to blow up!
{% endhint %}

{% hint style="info" %}
Working: for the man every night and day...
{% endhint %}

{% hint style="info" %}
Plain: booooooorrrrring.
{% endhint %}

### Screenshots

{% hint style="info" %}
The following software is required:

* [Libre Office Draw](https://www.libreoffice.org/)
* A tool to capture screenshots
* Windows, Linux, Unix, or Mac OS X
{% endhint %}

#### Types of screenshots

1. _basic_ screenshots have no annotation or markup applied
2. _annotated_ screenshots have markup applied, e.g. callouts, highlights, etc.

#### Requirements for all screenshots

1. Minimum 1200px wide
2. Must include a caption
3. PNG format
4. Generally browser window captures should only contain minimum user interface controls, without navigation toolbar, tab bar, bookmarks toolbar, or status bar. See [Bookmarlet for Screenshots](documentation-guide.md#bookmarlet-for-screenshots).

   ![Example browser screenshot.](.gitbook/assets/homepage.png){caption class=border}

5. Images should be stored in the `assets` directory corresponding to the section in which the image appears. Exceptions to this requirement are made for images used in multiple sections.
6. Image sizes should be as small as possible without sacrificing quality.

   Usually significant size reduction can be achieved by color-type or bit-depth

   reduction. [pngcrush](https://en.wikipedia.org/wiki/Pngcrush) is a good tool for this.

#### Requirements for annotated screenshots

1. Use LibreOffice Draw to create the annotations
   * A template is available here `/assets/documentation-guide/callouts-template.odg`
   * Each screenshot should be placed on a new page
   * Whenever possible place annotations in callouts _outside_ of the image or

     in a way that  does not cover user interface elements

   * Name the page using the name of the PNG file
   * Export the screenshot to PNG
     * only export the
     * compression level 6
     * 1200 pixels wide
2. All annotated screenshots for a section should be stored in a single `.odg` file.
3. Save the LibreOffice Draw file \(.odg\) in the directory with the screenshots

   ![Creating screenshots using LibreOffice Draw](.gitbook/assets/libreoffice-screenshot.gif){caption class=border}

#### Screenshot captions

To apply a caption to a screenshot use this syntax in the Markdown.

```text
![caption goes here](/assets/path/to/image){caption}
```

![Screenshot with caption](.gitbook/assets/example-image.png){caption}

To apply a border to a screenshot, add `class=border`.

```text
![caption goes here](/assets/path/to/image){caption class=border}
```

![Screenshot with border](.gitbook/assets/example-image%20%281%29.png){caption class=border}

Applying the `{caption}` to a image will also indent the image from the surrounding text.

#### Bookmarlet for Screenshots

Use this bookmarlet: [Plain Window](javascript:%28function%28%29{var%20windowObjectReference;var%20strWindowFeatures='menubar=no,location=yes,resizable=yes,scrollbars=yes,status=no,width=1200,height=1200';windowObjectReference=window.open%28window.location.href,'Plain%20Jane',strWindowFeatures%29;}%29%28%29;). Drag the link to your bookmarks bar or create a bookmark with the code below. Clicking the bookmark will open the current webpage in a plain window that is 1200px wide. Re-size to needed height and take a screenshot. More about bookmarlets here: [https://www.wikipedia.org/wiki/Bookmarklet](https://www.wikipedia.org/wiki/Bookmarklet).

```javascript
javascript:(function(){var windowObjectReference;var strWindowFeatures='menubar=no,location=yes,resizable=yes,scrollbars=yes,status=no,width=1200,height=1200';windowObjectReference=window.open(window.location.href,'Plain Window',strWindowFeatures);})();
```

