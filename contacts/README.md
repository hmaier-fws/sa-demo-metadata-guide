# Contact Entry Guidance

Contacts are individuals or organizations that can be referenced by other contacts, projects, or products. Contacts contain information such as the names of individuals or organizations, email address, physical address, website, and phone number so that viewers of metadata can communicate with those affiliated with a metadata record. Contacts also enable users to know who is involved in the creation and maintenance of projects and products, funding of projects, and creation and maintenance of metadata.

## General Info on Contacts

In mdEditor, contacts are created separately from individual records and then stored within a library in mdEditor. Once contacts have been entered or imported into mdEditor, they can be used in any metadata record. Editing a contact in the mdEditor contact library will update the contact information included in any metadata record that uses that contact. Editing a contact in mdEditor will also update contact information on ScienceBase once the record is published.

{% hint style="danger" %}
You should maintain a single list of your contacts. Having duplicate copies of the same contact is not desirable. It can create confusion as you edit and manage your metadata records and introduce unnecessary errors.
{% endhint %}

Copying contacts will change the ID and the name \(the name will be “Copy of ….”\) but all the other information will be the same

It is recommended that you leave contacts in mdEditor in between work sessions. This allows you to readily add contacts to projects and products.

{% hint style="info" %}
It is recommended that when you export records, you also export your entire contact list. If you do not export your contact list, and you later import a record that contains a contact not in your library, you may receive an error and have to re-enter the contact to that record.
{% endhint %}

## Best Practices for Contacts

* Always spell out acronyms and organization names.
* Make sure your contacts are loaded and accurate in mdEditor before creating or editing your metadata records. 

## Contacts Seed File

The "contacts seed file" contains pre-filled information and standard naming conventions for all LCCs, common federal agencies, and the LCC Network Data Steward. Using this file will increase consistency across all LCC metadata records for common contacts and reduce the amount of processing needed before records go into the Science Catalog.

## Importing Contacts from ScienceBase

When you import a ScienceBase record, mdTranslator will automatically load all sbJSON contacts into Main/Citation/Responsible Parties. You MUST review this to check for errors and inconsistencies introduced during translation. Delete any duplicate or extraneous contacts or any errors. Then continue with edits to meet requirements, follow best practices, and add other contacts as desired.

