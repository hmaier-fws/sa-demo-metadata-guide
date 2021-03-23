# Project Entry Guidance

The Project Entry Guidance section will cover how to create a metadata record for an LCC project.

## Before You Begin

### **Adjust your mdEditor** [**Settings**](../settings.md)**:**

**Metadata Repositories**: Make sure your default settings are correct for the LCC Science Catalog and data.gov. See [Settings](../settings.md).

**Parent Identifier:** In the publishing settings, enter your LCC's ScienceBase project folder's identifier in the "Default Parent Identifier" field.

### **Select the LCC Project Profile**:

After creating your project record initially and before you begin adding metadata, select **lccProject** from the **Profile** drop-down in the main menu. This will limit the number of available tabs and only show tabs that contain fields that are applicable to LCC project metadata.

![](../.gitbook/assets/profile_lccproject.PNG)

### **Make sure your contacts are loaded into mdEditor:**

In mdEditor, contacts are created separately from individual records and then stored within a library in mdEditor. Once contacts have been entered or imported into mdEditor, they can be used in any metadata records.

{% hint style="danger" %}
You should maintain a single list of your contacts. Having duplicate copies of the same contact is not desirable. It can create confusion as you edit and manage your metadata records and introduce unnecessary errors.
{% endhint %}

## Edit a Project

1. Import or create your project record \(see [workflow](../getting-started/)\).
2. Pick "project" as the **Resource Type**
3. Select the LCC Project Profile: from the Main Menu \(Top Navigation Bar\) select "**lccProject"** from the profile drop-down menu.
4. Fill out metadata information for the following tabs:
   * [Main Tab](record-main-copy.md)
   * [Metadata Tab](metadata-tab.md)
   * [Keywords Tab](keywords-tab.md)
   * [Taxonomy Tab](taxonomy-tab-projects.md)
   * [Extent Tab](extent-tab.md)
   * [Documents Tab](documents-tab-projects.md)
   * [Funding Tab](funding-tab.md)
5. If applicable, [associate](associating-records.md) your project with other metadata records.

## Required Fields for Projects

### **Main Tab**

* Title
* Status
* Language
* Resource Type
* Point of Contact
* Main Citation
  * Identifier
  * Online Resource URI
  * Responsible Parties 
* Description
  * Abstract
* Time Period
  * Start Date
  * End Date

### **Metadata Tab**

* Metadata Status 
* Metadata Contacts
* Metadata Identifier
* Parent Metadata
  * Title 
  * Identifier
    * Identifier
    * Namespace
* Metadata Repositories

### **Keywords Tab**

* ISO Topic Category
* LCC Project Category 
* LCC Deliverable Types
* LCC End User Types
* GCMD Keywords \(Best Practice\)

### Taxonomy Tab

* Taxonomic classifications

### **Extent Tab**

* Geographic Extent

### **Funding Tab**

* Allocation
  * Amount 
  * Currency 
  * Source 
  * Recipient
  * Other Contacts 
  * Matching Funds
  * AwardID
* Time Period
  * Start Date
  * End Date

