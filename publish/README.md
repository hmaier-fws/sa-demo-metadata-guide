# Publish

\[NOTE: the Publishing instructions still need some editing/refinement.\]

LCC metadata is published to ScienceBase in your LCC community's project folder. You must have a ScienceBase user account with write access to this folder. Once the mdJSON metadata is published in ScienceBase, the records will be synced with the LCC Science Catalog \(the Science Catalog updates overnight with new/updated mdJSON\).

### ![](../.gitbook/assets/publish_screenshot_overview.png)

## Before You Begin

Please read through ALL instructions before you begin the publishing process. After you understand how the publishing function works, please read the[ **testing instructions**](https://github.com/tpatterson1996/lcc-metadata-manual/tree/287090b07635d0e76a714278ce1f6c4aac3594cc/publish/instructions-for-testing-publishing.md) and proceed with testing a record before you try to publish any of your real records.

## Overview of Publishing to the Science Catalog

The following describes what happens when you publish from mdEditor:

1. mdEditor outputs an mdJSON file.
2. The mdJSON file is transmitted via a web service to mdTranslator.
3. mdTranslator translates the mdJSON file into sbJSON and XML.
4. ScienceBase imports the sbJSON and attaches the XML and mdJSON files to the ScienceBase item.
5. The record is sent to data.doi.gov and the LCC Science Catalog if the requisite metadata repositories are specified.

