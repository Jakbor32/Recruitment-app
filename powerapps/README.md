# PowerApps Canvas App Setup Guide

## 1. **Create a New Canvas App**

1. **Launch PowerApps Studio**:
   - Navigate to [PowerApps Studio](https://make.powerapps.com/) or open the **PowerApps Desktop** app.
   - Select **Create** from the left sidebar and choose **Canvas App**.
   - Choose **Tablet** or **Phone** layout depending on your app's needs.
   - Name your app and click **Create** to open a blank canvas.

---

## 2. **Enable Modern Controls and Themes**

1. To access app settings, click on the **App Settings** gear icon in the top right corner of the screen.
2. In the **Settings** menu, navigate to the **Updates** tab.
3. Under **News**, locate and enable the **Modern Controls and Themes** option. This will ensure that your app uses the latest UI controls and theme styles, improving visual appeal and performance.

---

## 3. **Add New Component from TreeView**

1. In **TreeView** on the left sidebar, locate and click on **Components**.
2. Click **New Component** at the top of the components pane. This will open a new, blank component editor.
3. At this point, you will import your YAML code for custom components.

---

## 4. **Paste YAML Code for the Component**

1. Inside the new component editor (where you see the blank screen), **right-click** anywhere on the white space.
2. From the context menu, select **Paste → Paste Code**.
3. Open your YAML file (e.g., `toast_notification.yaml`), copy the entire content, and paste it into the editor.

   The YAML content will be parsed and displayed within your component, allowing you to modify and use it within your app.

---

## 5. **Add New Screens and Paste YAML Code**

1. Now, proceed to **Screens** in the left sidebar and click **New Screen** to add a new blank screen.
2. On the new screen, **right-click** again on the white space and select **Paste → Paste Code**.
3. Copy and paste the content of another YAML file (e.g., `Add_request_screen.yaml`) to configure the new screen.
