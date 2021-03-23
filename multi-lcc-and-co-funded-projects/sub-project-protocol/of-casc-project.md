# Sub-project of CASC Project

When your project is a sub-project underneath a CASC project, complete the following requirements for the sub-project in addition to the standard metadata requirements. Products of a sub-project can be entered as normal \(i.e., treat the sub-project as a normal project for the purposes of the product metadata and associations\).

## Main/Points of Contact

Add the collaborating CASC as a “collaborator.”

## Main/Citation/Responsible Parties

Add the collaborating CASC as a “collaborator.”

The LCC funding the sub-project or distinct product is the “administrator” in the sub-project metadata and should be included as such according to standard metadata contact requirements.

## Main/Abstract

Add the following text as the last sentence:

“This project is a sub-project of the \[X\] Climate Adaptation Science Center project described here \[insert hyperlink to CASC ScienceBase URL\].”

* Example: “This project is a sub-project of the South Central Climate Adaptation Science Center project described here.”

## Main/Supplemental Information

Add the following text \(Best Practice\):

“This project is a sub-project of the \[X\] Climate Adaptation Science Center project described here \[insert hyperlink to CASC ScienceBase URL\].”

* Example: “This project is a sub-project of the South Central Climate Adaptation Science Center project described here.”

## Metadata/Metadata Contacts

Include the lead LCC as “publisher.”

Collaborating CASCs do not need to be listed here.

## Associated

Since the CASC metadata is outside the LCC communities in ScienceBase, you must manually associate the LCC/CASC projects both in the mdEditor Associated tab and directly on ScienceBase.

### Associations in mdEditor

Manually associate the LCC/CASC project as a “subProject” relationship in the Associated tab.

1. Populate the association type as “subProject”.
2. Enter the appropriate resource type.
3. Copy the CASC’s project title to the title field.
4. Enter the CASC as the “administrator” in the Responsible Parties section.
5. Add the CASC ScienceBase item URL in the Online Resource field. This is important to provide discovery and access to items outside of the LCC Science Catalog.
6. Add the ScienceBase Identifier of the CASC project.

The CASC associated items will not appear in the Science Catalog as standalone items, but will appear as links on the LCC record\(s\) in the Science Catalog under a header that labels the type of association. The assumption here is that your sub-project contains all LCC-relevant information and contributions and that the CASC project record is not needed. If you find that the LCC and CASC contributions cannot be teased apart into project and sub-project, then you should follow the co-funded protocol instead.

### Associations in ScienceBase

The only associations that ScienceBase recognizes from mdJSON are parentProject/product relationships so it will not recognize the “subProject” association created in mdEditor. This association must be added by hand directly in ScienceBase.

1. Log in to your ScienceBase account to edit the appropriate LCC ScienceBase item.
2. Click “Associate an Item” from the right side column of the ScienceBase page.
3. Add a “subprojectOf” association to the CASC ScienceBase item.

