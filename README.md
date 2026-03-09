# Enforcing-mandatory-fields-using-UI-policies-and-migrating-changes-with-update-sets

1. Creating UI Policy

Log in to the ServiceNow instance.

Navigate to System UI → UI Policies.

Click New.

Select the required table (e.g., Incident).

Define the condition for the UI Policy.

Save the UI Policy.

2. Creating UI Policy Actions

Open the created UI Policy.

Add UI Policy Actions.

Select the field that should be mandatory.

Enable the Mandatory option.

3. Creating Update Set

Navigate to System Update Sets → Local Update Sets.

Click New and create an Update Set.

Set the created Update Set as Current.

4. Capturing Changes

All the UI Policy configurations will automatically be captured in the active Update Set.

5. Migrating Changes

Export the Update Set as an XML file.

Import it into another ServiceNow instance.

Preview and commit the Update Set.
