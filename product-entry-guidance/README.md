# Product Entry Guidance

The Product Entry Guidance section will cover how to create a metadata record for an LCC product.

## Before You Begin

### Adjust your mdEditor [Settings](../settings.md):

**Metadata Repositories**: Make sure your default settings are correct for the LCC Science Catalog and data.gov. See [Settings](../settings.md).

**Parent Identifier**: In the publishing settings, enter your LCC's ScienceBase project folder's identifier in the "Default Parent Identifier" field.

### Select the LCC Product Profile:

After creating your product record initially and before you begin adding metadata, select **lccProduct** from the **Profile** drop down in the main menu. This will limit the number of available tabs and only show tabs that contain fields that are required for product creation.

![](../.gitbook/assets/profile_lccproduct.PNG)

### Make sure your contacts are loaded into mdEditor:

In mdEditor, contacts are created separately from individual records, and then stored within a library in mdEditor. Once contacts have been entered or imported into mdEditor, they can be used in metadata records.

## Edit a Product

1. Import or create your product record \(see [workflow](../getting-started/)\).
2. Choose the specific **Resource Type** that describes your product. Do not choose the generic "product."
3. Select the LCC Product Profile: from the Main Menu \(Top Navigation Bar\) select "**lccProduct"** from the profile drop-down menu.
4. Fill out metadata information for the following tabs:
   * [Main Tab: Product](main-tab-product.md)
   * [Metadata Tab: Product](metadata-tab-product/)
   * [Keywords Tab: Product](keyword-tab-product.md)
   * [Taxonomy Tab: Product](taxonomy-tab-product.md)
   * [Extent Tab: Product](extent-tab-product.md)
   * [Lineage Tab: Product](lineage.md)
   * [Distribution Tab: Product](distribution.md)
   * [Constraints Tab: Product](record-constraints.md)
   * [Dictionaries Tab: Product](dictionaries-tab-product.md)
   * [Documents Tab: Product](documents-tab-products.md)
5. If applicable, [associate ](associating-records-products.md)your products with other metadata records.

## Required Fields for Products

### Main Tab

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

### Metadata Tab

* Metadata Contacts
* Metadata Identifier 
* Parent Metadata
  * Title
  * Identifier
    * Identifier
    * Namespace
* Metadata Repositories
* Online Resource

### Extent Tab

* Geographic Extent

### Keywords Tab

* ISO Topic Category 
* LCC End User Types
* GCMD Keywords \(Best Practice\)

### Taxonomy Tab

* Taxonomic classifications

### Distribution Tab

* Distributor
  * Contact
  * Role
  * Online Option
    * URI

