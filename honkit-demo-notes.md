# SA HonKit demo

## Test repo location

  - Repo: https://github.com/hmaier-fws/sa-demo-metadata-guide
  - Rendered page: https://hmaier-fws.github.io/sa-demo-metadata-guide/


# Requirements:

  - Node.js (on IRTM [approved software list](https://doimspp.sharepoint.com/sites/fws-FF10T00000/SitePages/Approved-Software.aspx))
  
# Syntax overview

  - Basic Markdown syntax including some [HonKit-specific](https://honkit.netlify.app/syntax/markdown.html) formatting.
  - Callout box formatting is specified by the [hints plugin](https://www.npmjs.com/package/gitbook-plugin-hints#usage).

## Quick setup

  1. `npm install`
  
The above command will read the package.json file and install all required modules.
Running the `install` command for each module is not necessary.

## New Install

  1. Required: Valid Node.js installation
  2. Install HonKit: `npm install honkit`
  3. Install Hints plugin: `npm install gitbook-plugin-hints`
  4. Install anchorjs plugin: `npm install gitbook-plugin-anchorjs`
  5. Install ebook convert plugin" `npm install ebook-convert`
  
The above commands insatll the minimum required modules to create a GitBook-type documentation collection.  


## Local edits and preview

### Command: `npx honkit serve ./source ./docs`

The complete syntax of the command is: `npx honkit serve --format website ./source ./docs`

This command builds the book and serves it locally at [http://localhost:4000](http://localhost:4000). The rendered book is updated as files are edited, allowing for the viewing of changes in real time.

The markdown files are rendered as html into the "_book" directory by default. 
Supplying the output parameter "./docs" causes the html to be rendered to the 
"docs" (or other specified) directory. GitHub Pages uses content from a "docs" 
directory to generate a GitHub.io website. Rendering the book to "docs" 
eliminates the additional step of building the book to a "docs" directory or 
manually renaming "_book" to "docs" prior to uploading data to GitHub.

A complete list of HonKit options can be viewed by typing: `npx honkit serve --help`

## Build book

### Command: `npx honkit build --format website ./source ./docs`

This command should not be necessary if the above syntax is used to preview the book while editing.

## Generate PDF

  1. Install ebook convert: `npm install ebook-convert`
  2. Install Calibre Portable executable
  3. Add to path to directory containing Calibre Portable executable:
    `set path=C:\Users\HMaier\bin\Calibre Portable\Calibre;%path%`
  4. Build PDF: `npx honkit pdf ./source ./test-pdf.pdf`
---

# References

  - [Node.js](https://nodejs.org/en). A JavaScript environment that allows JavaScript code to be run form the command line.
  - [HonKit](https://honkit.netlify.app/). Node.js package used to create GitBook-like documentation. See associated [GitHub repository](https://github.com/honkit/honkit).
  - [gitbook-plugin-hints](https://www.npmjs.com/package/gitbook-plugin-hints). Plugin to create hint blocks in documents.
  - [AnchorJS](https://www.bryanbraun.com/anchorjs/). Node.js plugin that generates an anchor link icon next to headings, allowing users to copy a url that provides a direct link to a specific location in the rendered document. See associated [GitHub repository](https://github.com/bryanbraun/anchorjs).
  