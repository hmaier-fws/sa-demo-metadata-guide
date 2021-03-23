# for LCC/CASC Products

## Applicability

Refer to this protocol if:

* One or more LCCs co-funds a project with one or more CASCs without distinct sub-parts that could be attributed to either an LCC or CASC. This protocol is for the product metadata.

## Metadata Responsibility

The co-funding LCC data manager is responsible for processing the CASC project and product metadata for inclusion in the LCC Science Catalog. The CASC data manager will complete their metadata responsibilities for the CASC records as well.

## Co-funded Product Workflow

### Workflow Option 1

1. Import the sbJSON for the CASC record.
2. Delete the SBIDs specific to the CASC record.
3. Modify the metadata to meet LCC metadata requirements.
4. Complete the additional metadata requirements for a cofunded product.

### Workflow Option 2

1. Create a record from scratch in mdEditor
2. Copy the title, abstract, and other pertinent info from the CASC ScienceBase record. 
3. Complete the additional metadata requirements for a cofunded product.
4. Associate this LCC product record with the LCC version of the project record you created

Note: The LCC copy of the CASC metadata should not include the data.gov tag. As a general rule, the entity who owns/hosts the data should be responsible for sending information to data.gov. In this case, the CASC is hosting the product/data on ScienceBase and they will be sending their information to data.gov directly.

In addition to standard metadata requirements, complete the following for the co-funded product record. All are required unless otherwise noted.

## Main/Point of Contacts

Add the collaborating LCC\(s\) and CASC\(s\) as a “collaborator.”

## Main/Citation/Responsible Parties

Add the collaborating LCC\(s\) as a “collaborator.”

{% hint style="info" %}
The lead LCC should be listed as “administrator” and does not need to be added again as a “collaborator.”
{% endhint %}

## Main/Citation/Online Resource

Include the link to the CASC's ScienceBase product page as an online resource.

* Name the link with “X Climate Adaptation Science Center ScienceBase Product Page.”

## Main/Abstract

Add the following text as as the last sentence:

“This product was co-funded by the \[A, B, C\] Landscape Conservation Cooperatives and \[X, Y, Z\] Climate Adaptation Science Centers. An alternate reference to this product can be found here: \[insert CASC ScienceBase URL\].”

* Example: “This project was co-funded by the Gulf Coast Prairie Landscape Conservation Cooperative and the South Central Climate Adaptation Science Center. An alternate reference to this product can be found here: [https://www.sciencebase.gov/catalog/item/5887c1c3e4b02e34393da82d](https://www.sciencebase.gov/catalog/item/5887c1c3e4b02e34393da82d).”

The CASC will include a parallel statement in the Summary field for their ScienceBase record \(and link back to the LCC record\).

## Main/Supplemental Information

Add the following text \(Best Practice\):

“This product was co-funded by the \[A, B, C\] Landscape Conservation Cooperatives and \[X, Y, Z\] Climate Adaptation Science Centers. An alternate reference to this product can be found here: \[insert CASC ScienceBase URL\].”

* Example: “This project was co-funded by the Gulf Coast Prairie Landscape Conservation Cooperative and the South Central Climate Adaptation Science Center. An alternate reference to this product can be found here: [https://www.sciencebase.gov/catalog/item/5887c1c3e4b02e34393da82d](https://www.sciencebase.gov/catalog/item/5887c1c3e4b02e34393da82d).”

## Associated

Since the CASC metadata is outside the LCC communities in ScienceBase, you must manually associate the LCC/CASC products both in mdEditor Associated and directly on ScienceBase.

### Associations in mdEditor

1. Make the normal project/product association back to the LCC version of the project record you created.
2. Manually associate the LCC/CASC product as an “alternate” relationship in the Associated tab.
3. Populate the association type as “alternate”.
4. Enter the appropriate resource type.
5. Copy the CASC’s product title to populate the title field.
6. Enter the CASC as the “administrator” in the Responsible Parties section.
7. Add the CASC ScienceBase item URL to the Online Resource section. This is important to provide discovery and access to items outside of the LCC Science Catalog.
8. Add the ScienceBase and/or Digital Object Identifier of the CASC product.

![](https://lh5.googleusercontent.com/4EADVJYG-c8gq2il2fU-ttIyN7ly3IxNBpO_eIxQ9DGHzFGZzQcdUpPV5M4DgP6-GVj44iFOWzberaOTSSoHcjVklZExfx8-GUtYMlT5UaZrnKorcKqQqZdD0o7Z8y6lH7XGudjz)

![](https://lh4.googleusercontent.com/DTpBB7E9FNNuJsQZbdlMUeaZvUyynlp4k1bI_kxF4suv7pvLb_AmBXZx5AJkGzdPwmFNRdYZ0keeWyudeFn7-4i7Jt-YGSq_j3ZrOTyQ_R-nUMzCTunOoi3-QPS7nfvVxoG_9561)

_Figure 1: Example of mdEditor entry in Associated tab for LCC/CASC co-funded project. This is entered in the LCC project record’s Associated tab to indicate this is an “alternate” reference to a CASC project._

### Associations in ScienceBase

The only associations that ScienceBase recognizes from mdJSON are parentProject/product relationships so it will not recognize the “alternate” association created in mdEditor. This association must be added by hand directly in ScienceBase.

1. Log in to your ScienceBase account to edit the appropriate LCC ScienceBase item. 
2. Click “Associate an Item” from the right side column of the ScienceBase page. 
3. Add an “alternate” association to the CASC ScienceBase item \(see Figure 2\).

![](https://lh3.googleusercontent.com/Y-WE_OLGwFwOsKRuYWCH4-PEBFF26VqhLpmJmbUIItDxpHMKZWDzDsASf8fK5Wz8auONqa97fi5Yw5VK2VfEIOkJfRTzVugHpEFOc2rNrJX83G06vL7eEYqzatSrsDXbGJ_NDAub)_Figure 2: Example of LCC product record for an LCC/CASC co-funded product. The association created directly on ScienceBase identifies this GCP LCC product record as an “alternate” of the South Central CASC product record._

## Distribution

Include the CASC weblinks and identifiers that you just entered in the mdEditor Associated tab in the Online Resource section.

* List the role of the CASC as “owner.” 

The Distribution links are critical for providing access to the actual data/tool/etc.

## Notifying CASCs

Enter your LCC/CASC co-funded Projects and Products on this [spreadsheet](https://docs.google.com/spreadsheets/d/1WBFGslnaqxlbcIJ-LmH4kRvobLkH166y58UpWw03rc8/edit?usp=sharing).

Ideally enter items on the spreadsheet after you have completed the co-funded metadata requirements and published to ScienceBase. If you prefer to enter on this spreadsheet before you have completed those steps, be sure to indicate the status of your edits/publishing in the "LCC Edits" column.

CASC data managers will refer to the spreadsheet so they know when to make edits on their end.

