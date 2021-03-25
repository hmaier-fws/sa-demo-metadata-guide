# Main Tab: Product

The **Main** tab allows for the creation and/or editing of primary metadata.

| Quick Reference: Product Main Tab | Required? |
| :--- | :--- |
| Basic Information: Title, Status | Required |
| Resource Type | Required |
| Point of Contact | Required |
| Citation: Title, Responsible Parties, Online Resource | Required |
| Citation: Identifier | Best Practice |
| Citation: Alternative Titles, Date | Optional |
| Description: Abstract | Required |
| Time Period: Start Date, End Date | Required |

## Basic Information

### Record ID \(Required\)

Will be auto-generated but can be edited.

### Title \(Required\)

Enter as informative a title as possible. Good titles, when they appear in a search, will be understood and/or traceable.

### Status \(Required\)

The **Status** drop-down menu allows you to select the status of your product. Choose status ONLY from the four following options: _completed_, _ongoing_, _proposed_, or _accepted_.

![](../.gitbook/assets/main_screenshot_updated.png)

## Default Locale

**Default Locale** allows for the selection of **Language**, **Character Set**, and **Country**. English, UTF-8, and USA will be selected by default, but you may change them if necessary.

![](../.gitbook/assets/default_locale.png)

## Resource Types \(Required\)

The Resource Type should be automatically filled in with the resource type you selected when you created your record. Name is optional - you can leave this blank.

{% hint style="info" %}
Products must have a specific resource type selected \(not just "product"\).
{% endhint %}

## Point of Contacts

Adding a point of contact gives LCC staff information on who to contact should they have a question regarding your project or product. From the **Role** drop-down menu, select **pointOfContact**. From the **Contacts** drop-down menu, select a contact from the list of contacts. See the [Contacts](../contacts/) section for information on creating contacts.

| Role | Contact | Required? |
| :--- | :--- | :--- |
| pointOfContact | LCC Network Data Steward | Required |
| pointOfContact | Your LCC | NOT Required \(\*see below\) |
| principalInvestigator | The Project PI | Best Practice |

\*Note: Given the transition away from LCCs, it is no longer required to add the LCC as a Main / Point of Contact in new or updated metadata records.

{% hint style="info" %}
The LCC Network Data Steward will serve as the long term contact/backup. This way, users have a point-of-contact even if there is a positional change within an organization. The LCC Network Data Steward should be included in addition to any point of contact that you want to add from your organization.
{% endhint %}

## ![](../.gitbook/assets/main_pointsofcontact.PNG)

## Citation

The **Citation** lets users know pertinent information about your project or product such as responsible parties, internal and ScienceBase identifiers, and any online resources that may relate to your item. Adding information in the citation will also allow users to find your item when they search for items that contain said information.

The following fields are required in citation:

#### Title \(Auto-Generated\)

Added automatically based on the title of your record.

#### Alternate Title \(Optional\)

Add an alternate title.

#### Dates \(Optional\)

Enter _acquisition_, _creation_, _revision_, or another date reference from the picklist and then enter the date.

#### Responsible Parties \(Required\)

This must include a point of contact, but may also include other responsible parties such as funders \(including your LCC\), partners, collaborators, and contributors. Collaborators could be intellectual participants while contributors could be intellectual and financial participants.

| Role | Contact | Required? |
| :--- | :--- | :--- |
| pointofContact | LCC Network Data Steward | Required |
| administrator | Your LCC | Required |
| principalInvestigator | The Project PI | Best Practice |

{% hint style="info" %}
For items that will be sent to data.gov, list the LCC Network Data Steward first in the list of Responsible Parties \(\#0\). Data.gov only shows the first contact and the data steward should be listed first.
{% endhint %}

#### Online Resource \(Required, if Available\)

Enter the Name and URL for the location where users can find the product \(e.g., ScienceBase page\).

{% hint style="info" %}
Important: The URLs to access and download products must **also** be included in the Distribution tab. Distribution Links is the only online resource that data.gov reads so without a URL there, users have no way to access the actual product from data.gov.
{% endhint %}

#### Identifier \(Best Practice\)

You may enter as many identifiers as desired. If you have internal LCC-specific IDs for projects, enter them here. Other optional identifiers include: Digital Object Identifier \(DOI\) and Archive Folder Name.

{% hint style="info" %}
**Best Practice**: Create and use internal identifiers that are unique within your LCC for projects and their products. Example: GNLCC2010-11.
{% endhint %}

{% hint style="info" %}
If your item does not have a ScienceBase ID \(SBID\) yet, ScienceBase will create one automatically upon publishing. If you imported your item from ScienceBase originally, then the SBID will already be included in Metadata/Metadata Identifier and you do not need to include it here. Note that if you edit an item that is already on ScienceBase without using its existing SBID, a duplicate item will be created on ScienceBase. Consult the [Publish](../publish/) section of this manual to learn more.
{% endhint %}

{% hint style="info" %}
If the product metadata was created by copying another mdEditor metadata record, this identifier needs to be edited/changed since it will reflect the copied record identifier. Only the mdEditor UUID changes to represent a new record when an item is copied. Consult the [Copy Records](../data-management/copy-records.md) section of this manual to learn how to make a copy.
{% endhint %}

## Description

**Description** allows for the addition of the **Abstract** as well as a Short Abstract, Purpose, Supplemental Information, and an Environment Description.

#### Abstract \(Required\)

Enter an Abstract

{% hint style="info" %}
Tip: Write your abstracts for projects in the present tense if the project is underway and past tense if it has been completed.
{% endhint %}

#### Short Abstract \(Optional\)

Enter a short description, limited to 300 characters, if desired

#### Supplemental Information \(Optional\)

Enter comments, if desired.

## Time Period

**Time Period** refers to project start and end date, or the date that the product was applicable \(e.g., time that a map is valid, date of publication, date of presentation\).

* **Required**: For each product, add a start date and end date.

![](../.gitbook/assets/main-time-period.PNG)

