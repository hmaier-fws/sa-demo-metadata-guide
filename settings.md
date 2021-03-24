# Settings

The settings menu allows for the configuring of user-specific options. Settings must be configured before you create SA metadata.

## General Settings

**mdEditor Version**: The mdEditor version notes the current version of mdEditor. Use this when reporting errors. Errors can be reported at [https://github.com/adiwg/mdEditor/issues](https://github.com/adiwg/mdEditor/issues). You must have a github account in order to post.

**Auto-Save**: The Auto-Save option will write all changes to local storage when you exit a data entry field. Changes must be manually saved if the Auto-Save feature is turned off.

{% hint style="info" %}
Auto-Save allows you to save less frequently, but it makes it harder to undo changes that you make to your records. If you stay on the same record, you can cancel changes. But once you leave the record, the record is saved and you can’t cancel the change except by manually re-editing the record.
{% endhint %}

**Copy in Edit Mode:** All 

**Delete in Edit Mode:** Allow users to delete a record while in edit

**Clear All Records**: All records can be cleared by clicking the "Clear Storage Cache."

{% hint style="danger" %}
**Warning**: Clearing all records will delete all of the records currently loaded in mdEditor. Before doing so, use the Export function to make a backup of your records. Otherwise, the records will be permanently lost \(unless you previously made a backup copy\).
{% endhint %}

![General Settings](.gitbook/assets/image%20%285%29.png)

## SA Specific Settings

_These must be implemented before you begin creating metadata records._

 **\(1\) Importing from ScienceBase** In the Defaults section, set the default Import URL to import items from ScienceBase with the following: [https://api.sciencebase.gov/sbmd-service/mdjson/](https://api.sciencebase.gov/sbmd-service/mdjson/).

**\(2\) Metadata Repositories**: In the Defaults section, add two Metadata Repositories.

1. Select **ScienceCatalog** from the Repository drop-down menu. Enter “SA Science Catalog” as the collection title.
2. Select **data.gov** from the Repository drop-down menu. For the collection title, enter "Data.gov USFWS Science Applications". 

![Science Applications settings](.gitbook/assets/image%20%287%29.png)

{% hint style="info" %}
The metadata repository information must be exactly the same for each record with no variations in spelling, spaces, capitalization, etc. Specifying this information in Settings is the best way to ensure the repository information will be consistent across records. It is strongly recommended that you do not type these in by hand on individual metadata records.
{% endhint %}

**\(3\) Parent Identifier**: Under publishing, enter the ScienceBase identifier for your SA Region's ScienceBase project folder in the "Default Parent Identifier" field.

![](.gitbook/assets/image%20%283%29.png)

## Defaults

**Defaults** include settings for **Language**, **Character Set**, **Country**, and the _\*Import URL_ \*\(used for defining the default URL for importing\).

The following defaults will be pre-loaded:

* default language: English
* default character set: UTF-8
* default location: USA

Also included in **Defaults** are the **Metadata Repositories** \(online databases for storing metadata\). Once entered in **Settings** these can then be selected for projects and products so that they are flagged to a metadata repository of your choice. See SA Specific Settings for Metadata Repository information above.

## Publishing Settings

SA metadata will be published directly to ScienceBase \(and from there be sent to the Science Catalog and data.gov\).

In the **Default Parent Identifier**, enter your LCC's ScienceBase project folder's ScienceBase ID \(SBID\). **Default Community** and **Default Organization** are free text fields to describe where your Default Parent Identifier is located.

![](.gitbook/assets/image.png)

## Export Settings

See the [Export section](data-management/export.md#export-options) for information about the options available for Exporting.

## Profile and Validation Settings

Allows a user to import a custom metadata profile and/or a custom validation schema.

