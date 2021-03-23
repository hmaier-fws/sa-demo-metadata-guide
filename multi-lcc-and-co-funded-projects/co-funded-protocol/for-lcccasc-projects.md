# for LCC/CASC Projects

For projects and products that were co-funded with the CASCs, there are already ScienceBase items owned by the CASCs for the projects and products. In order for those projects and products to show up in the LCC Science Catalog, you need to create LCC metadata records that will link to the CASC records. The general approach is to make a copy of the CASC metadata in mdEditor \(or PTS\), modify the metadata to follow LCC metadata requirements, tag for the Science Catalog, add a statement in the abstract explaining the collaboration, and include a link back to the CASC ScienceBase records. The statement in the abstract and the links to the CASC ScienceBase records will clarify that these are alternate references for the same item \(not duplicative efforts\), and in the case of products, provide access to the actual data/tool/etc. hosted on ScienceBase.

## Applicability

Refer to this protocol if:

* One or more LCCs co-funds a project with one or more CASCs and there are not distinct sub-projects that can be attributed to an LCC or CASC separately. This protocol is for the project metadata.

## Metadata Responsibility

The co-funding LCC data manager is responsible for processing the CASC project and product metadata for inclusion in the LCC Science Catalog. The CASC data manager will complete their metadata responsibilities for the CASC records as well.

## Co-funded Project Workflow

### Workflow Option 1

1. Import the sbJSON for the CASC record.
2. Delete the SBIDs specific to the CASC record.
3. Modify the metadata to meet LCC metadata requirements.
4. Complete the additional metadata requirements for a co-funded project.

### Workflow Option 2

1. Create a record from scratch in mdEditor.
2. Copy the title, abstract, and other pertinent info from the CASC ScienceBase record. 
3. Complete the additional metadata requirements for a co-funded project.

In addition to standard metadata requirements, complete the following for the co-funded project record. All are required unless otherwise noted.

## Main/Point of Contacts

Add all collaborating LCCs and CASCs as a “collaborator.”

## Main/Citation/Responsible Parties

Add all collaborating LCCs and CASCs as a “collaborator.”

{% hint style="info" %}
The lead LCC should be listed as “administrator” and does not need to be added again as a “collaborator.”
{% endhint %}

![](https://lh6.googleusercontent.com/4ewK_e-foCCi1kHOe9RiAG1Kuuc4VXIrB7S78S8goOtko3-DCZ9vj2wulFlwD7H_m_-IUfTTip8ssC_JHhJzqoD4bcguP-BvIimv2ctekLDadMNrOxEF-KBx7Ilr3uud0JodZmuJ)

_Figure 1: Example of mdEditor entry for Main/Point of Contact for an LCC/CASC co-funded project. Here, the project was a collaboration between the GCP LCC \(lead LCC\), the GCPO LCC, and the South Central CASC._

## Main/Citation/Online Resource

Include the link to the CASC's ScienceBase project page as an online resource.

* Name the link with “X Climate Adaptation Science Center ScienceBase Project Page.”

## Main/Abstract

Add the following text as the last sentence:

“This project was co-funded by the \[A, B, C\] Landscape Conservation Cooperatives and \[X, Y, Z\] Climate Adaptation Science Centers. An alternate reference to this project can be found here: \[insert CASC ScienceBase URL\].”

* Example: “This project was co-funded by the Gulf Coast Prairie Landscape Conservation Cooperative and the South Central Climate Adaptation Science Center. An alternate reference to this project can be found here: [https://www.sciencebase.gov/catalog/item/5887c1c3e4b02e34393da82d](https://www.sciencebase.gov/catalog/item/5887c1c3e4b02e34393da82d).”

The CASC will include a parallel statement in the Summary field for their ScienceBase record \(and link back to the LCC record\).

## Main/Supplemental Information

Add the following text \(Best Practice\):

“This project was co-funded by the \[A, B, C\] Landscape Conservation Cooperatives and \[X, Y, Z\] Climate Adaptation Science Centers. An alternate reference to this project can be found here: \[insert CASC ScienceBase URL\].”

* Example: “This project was co-funded by the Gulf Coast Prairie Landscape Conservation Cooperative and the South Central Climate Adaptation Science Center. An alternate reference to this project can be found here: [https://www.sciencebase.gov/catalog/item/5887c1c3e4b02e34393da82d](https://www.sciencebase.gov/catalog/item/5887c1c3e4b02e34393da82d).”

## Metadata/Metadata Contacts

Include the lead LCC as “publisher.”

Collaborating LCCs do not need to be listed here.

## Funding \(for Projects only\)

### LCC Allocations

Add a separate funding allocation for each year and each LCC that provided funding.

1. For LCC allocations, the source should be U.S. Fish and Wildlife Service \(or other agency that provided LCC project funding such as Bureau of Reclamation\).
2. Add the funding LCC as the “administrator” in the Other Contacts section \(see Figure 2\).

![](https://lh5.googleusercontent.com/FuzsddF2rFu5QQiRYIC7xLYOQrFWwHFoqIIMa0OuODOz52A3oSi1tAUUfh58HTjYmtKohXAGKwWfoKXdRXjol3J-A_zBCl6kddAGBjErEWIfSrSoYAkdmieraFzgSYR3jBwG0q26)_Figure 2: Example of mdEditor entry for an LCC funding allocation. Here, the UMGL LCC administered the USFWS funds. Additional allocations would be added for each LCC that provided funding to the project._

### CASC Allocations

1. List the source of CASC allocations as U.S. Geological Survey.
2. Add the funding CASC as the “administrator” in the Other Contacts section.
3. Check the matching funds box \(see Figure 3\).

![](https://lh3.googleusercontent.com/e4FV2qawV3ryt7S_SCo5t2i9cXraxJg4IfQB-M5d3mZjlYkblBVujR8c3a5ZU6M3sjETqxhSWwoEBwwdca7s2cD8-a0ZQMABXIPtCBHPbCAPZcEulOz2CSrfMC8Y-GjYssHOHYlL)

_Figure 3: Example of mdEditor entry for a CASC funding allocation. Here, the source is USGS and the CASC is the administrator since the funds did not flow through the LCC or FWS. The matching funds box is checked._

## Associated

Since the CASC metadata is outside the LCC communities in ScienceBase, you must manually associate the LCC/CASC projects both in mdEditor Associated and directly on ScienceBase.

### Associations in mdEditor

Manually associate the LCC/CASC project as an “alternate” relationship in the Associated tab.

1. Populate the association type as “alternate”.
2. Enter the appropriate resource type.
3. Copy the CASC’s project title to the title field.
4. Enter the CASC as the “administrator” in the Responsible Parties section.
5. Add the CASC ScienceBase item URL in the Online Resource field. This is important to provide discovery and access to items outside of the LCC Science Catalog \(see Figure 4\).
6. Add the ScienceBase Identifier of the CASC project.

![](https://lh4.googleusercontent.com/pXmGsY0ufzhw5K7T8Ml_8Sq88VFRp0f63T4HSZdnnOvP4xN4XtTYEVNXq9WrcK7r5wb0NHwcT1dMKtAbhVDKykWe-HSsYBp8GHOW2YsLgkMcOk1zUnFtFVAmKzAUGKAaeUKVdrGm)_Figure 4: Example of mdEditor entry for Online Resource. Online resource links must be added for associated items that do NOT have metadata in the LCC Science Catalog in order to ensure access and discoverability._

### Associations in ScienceBase

The only associations that ScienceBase recognizes from mdJSON are parentProject/product relationships so it will not recognize the “alternate” association created in mdEditor. This association must be added by hand directly in ScienceBase.

1. Log in to your ScienceBase account to edit the appropriate LCC ScienceBase item.
2. Click “Associate an Item” from the right side column of the ScienceBase page.
3. Add an “alternate” association to the CASC ScienceBase item \(see Figure 5\).

![](https://lh5.googleusercontent.com/s4tNZQxUK5yvtjEtAP-NWIKDvv1hY2IGjTxr7zHoDZnV931sZ9JRjLeHt4inqF0AIZSiHqjNM8-Ev30woD6tCngPnwG_CWnz2K-X8PBXOXLMqTTFtvOmId9C8WxdkAv-QxRBHSL4)

![](https://lh5.googleusercontent.com/FPfhTiqh2kFQ3B6MAawlBytGNKOkmlivoJBgL_Ehld7D1hSyR3EVF6V7eO_hZ5HB4eaq-WUPQ_kPWBIcAkyPTNTOLdSEZtJR0W5ROAWs0ylrLP_RQb_5zF0UEyCFuN4kDzdHT7Py)_Figure 5: Example of entering an association directly in ScienceBase. From the LCC project record, select “Associate an Item” and enter the SBID of the CASC project record and select “alternate” as the relationship type._

## Notifying CASCs

Enter your LCC/CASC co-funded Projects and Products on this [spreadsheet](https://docs.google.com/spreadsheets/d/1WBFGslnaqxlbcIJ-LmH4kRvobLkH166y58UpWw03rc8/edit?usp=sharing).

Ideally enter items on the spreadsheet after you have completed the co-funded metadata requirements and published to ScienceBase. If you prefer to enter on this spreadsheet before you have completed those steps, be sure to indicate the status of your edits/publishing in the "LCC Edits" column.

CASC data managers will refer to the spreadsheet so they know when to make edits on their end.

