# Testing Publishing

For tracking issues, please use the github thread [here](https://github.com/adiwg/mdEditor/issues/128) and sign up for notifications via email.

{% hint style="info" %}
Note: Please use a testing folder before you update your real records. Consult the [**Instructions for Testing Publishing**](https://github.com/tpatterson1996/lcc-metadata-manual/tree/287090b07635d0e76a714278ce1f6c4aac3594cc/publish/instructions-for-testing-publishing.md) section for more information.
{% endhint %}

1. Determine your workflow for testing:

   If you **DO NOT** already have items on ScienceBase. Choose a project and its products to test.

   **BEST MANAGEMENT PRACTICE**: It's recommended that you export a project and its products into its own mdEditor file. Set default parent identifier as a ScienceBase folder.

   If you **DO** already have items on ScienceBase, choose one of the following approaches. _Note that it will be harder to test without it affecting your real records._

   _**Approach 1**_ - Take a simple project and product set, and make a copy of the mdEditor records. In the test version, delete all ScienceBase IDs \(SBIDs\) and parent IDs. The SBID will either be located in the citation, or if you imported the record from SB, the SBID will be the record identifier. Set default parent identifier as a folder.

   _**Approach 2**_- Publish directly to a real record if you are okay with the risk it presents.

2. Set your **Default Parent Identifier** in Settings.
3. Select one project with its associated products to test.
4. Follow the publishing instructions above for the scenario that applies to you.
5. Look for any errors in the third column. If you see an error that is 400 and red, it’s a problem that you can address. However, if it’s a 500 level error in red, that is a ScienceBase error that is outside the scope of the mdEditor.

   ![](../.gitbook/assets/publishing_error.png)**NOTE:** Any unsolvable issues can be submitted on the issues page for mdEditor: [https://github.com/adiwg/mdEditor/issues](https://www.gitbook.com/book/adiwg/mdeditor/edit#). You must have a github account in order to post.

   Advanced users can check errors using the console. Consult the **Advanced Users** section of this manual to learn more.

6. Verify that your test records have published as expected in your folder on ScienceBase \(or to the real record if that’s how you are testing\).
7. After you are satisfied with how your test records published to ScienceBase, you can proceed with publishing your real record.
8. Update your mdEditor settings to your real Default Parent Identifier.
9. Using the record you just tested, proceed with publishing to the real location on ScienceBase.
10. Make sure any test SBIDs are removed entirely from the record you want to actually publish.
11. Verify that the real records have updated as expected.
12. Proceed with publishing your other records to their real locations.

