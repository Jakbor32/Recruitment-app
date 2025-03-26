# Importing Flow and Troubleshooting Errors

## 1. Importing Flow

To import a Flow into Power Automate, follow these steps:

1. **Go to Power Automate** ([Power Automate Portal](https://flow.microsoft.com/)).
2. Click **Import** in the left panel.
3. Select the `.zip` file containing the exported Flow.
4. Click **Import** and wait for the process to complete.

## 2. Configuring Connections

After importing, Flow may require reconfiguring connections for services such as:

- **Microsoft Teams**
- **SharePoint**
- **Outlook**
- **Other services used in Flow**

### How to Create New Connections?

1. Go to **Data > Connections** in Power Automate.
2. Click **New connection**.
3. Select the service, e.g., **SharePoint**, and sign in with your account.
4. After creating the connection, return to the imported Flow and assign the newly created connection to the appropriate actions.

## 3. Troubleshooting Import Errors

If an error occurs during import, you may need to edit the `definition.json` file.

### Updating Links in `definition.json`

1. Open the `definition.json` file in a text editor.
2. Find and replace all default links (e.g., `http://contoso-my.sharepoint.com/`) with the correct domain for your organization.
3. Ensure that each table and list used in the Flow has the correct name and URL.

### Where to Find the Table ID?

If the Flow uses SharePoint data, the Table ID can be found in two ways:

1. Open the `definition.json` file and locate the `table` field—this contains the required ID.
2. Alternatively, navigate to the SharePoint document library or list:
   - Open the list and click **List settings**.
   - In the browser address bar, find the value `List={GUID}`—this is the Table ID.
   - Copy this ID and update it in `definition.json`.

## 4. Finalizing the Setup

After making the necessary changes:

- Save the edited `definition.json` file.
- Repackage the files back into a `.zip` format.
- Re-import the Flow into Power Automate.
- Test the Flow to ensure all connections work correctly.

