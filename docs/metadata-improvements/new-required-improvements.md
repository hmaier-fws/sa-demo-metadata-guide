# New Required Improvements

## Must Do Metadata Improvements

### Multi-LCC / CASC Co-funded Protocols

\(1\) Follow the new [Multi-LCC / CASC-cofunded protocols](../multi-lcc-and-co-funded-projects/).

### data.gov

\(2\) For items that will be sent to data.gov, list the LCC Network Data Steward first in the list of Responsible Parties \(\#0\). Data.gov only shows the first contact and the data steward should be listed first.

### Funding

\(3\) Add funding “administrators” for all LCC allocations in Funding/Other Contacts \(as opposed to assuming the administrator is the LCC if FWS is listed as the funding source\).

The previous guidance on how to list LCC funding was based upon the existence of only a single contact field for funding allocation source. The addition of the “Other Contacts” field to meet the needs for multi-LCC and CASC co-funded projects provides new functionality to better clarify funding sources and administrators. Having to interpret the situation where FWS is listed as the funding source to mean it was LCC funding is not a logical and best practice to move forward on. The lack of the LCC name in the funding source will muddle our ability to accurately understand funding moving forward beyond LCCs. As we move into SA-centric data management and even broader use of mdEditor, it will be even more vital to have clear indications of who provided funding. The funding administrator field can differentiate from multiple sources within a single agency \(e.g., within FWS can differentiate programs like SA, MB, Refuges, etc.\).

Note: You may be able to use the injector script to fix this issue. Matt Heller will provide guidance.

### Extents

\(4\) Spatial extents should be included for all projects and applicable products. Products can inherit extents from their parent project. For projects without an extent already, you can use the LCC geography. We will provide geoJSON files for all LCC geographies that you can import into mdEditor.

This enables consistent search and discovery via the Science Catalog and allows users to search for resources using a map select tool. It will also allow any future functionalities based on geography to be automatically applied to your items without any further changes needed \(for example, if identifying congressional districts is identified as a need in the future, these could be automatically assigned to records based on the spatial extent\).

### Keywords

\(5\) LCC End User Type is required for projects AND products. An oversight in the first version of metadata requirements only had this required for projects but it should also be entered for all products.

### Taxonomy

\(6\) Add Taxonomy via new functionality in mdEditor. This is required for Projects and optional for Products \(but strongly recommended\) if you have specific species or taxonomic groups as part of your metadata record.

This will enable consistent taxonomic searching in the Science Catalog and will ensure the LCC records will be compatible with future metadata records that will be generated from mdEditor for non-LCC projects.

## Lower Priority Metadata Improvements

### Funding

\(7\) Complete in-kind and matching fund information for all projects. Ideally this should be completed for all projects but the priority is to complete and fix all agency funding information first.

### Contacts

\(8\) Every Individual contact who belongs to an organization should have their organization identified in “Member of Organization.”

### Keywords

\(9\) Choose GCMD Keywords for all projects and products. This is the only keyword set that can provide some consistent keywords across all of the records.

