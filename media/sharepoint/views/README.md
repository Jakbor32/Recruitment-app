# Configuring SharePoint Views for Access Control

## Creating a Restricted View

### 1. Navigate to List Settings

- Scroll down to the bottom and select **Create View**.
- Choose the default **All Items** view.  
  ![settings](../security/photos/list_settings.png)
  ![create view option](photos/create_view.png)

### 2. Adding an Access Control Column

- After adding the necessary columns, create an additional column to indicate restricted access.
- Name this column **access_blocked** (Text type).
- This column will serve as a visual cue for users without the required permissions.  
  ![access blocked column](photos/access_blocked_column.png)

### 3. Applying a Filtering Trick

- Open the **All Items** view settings and navigate to the **Filter** section.
- Set the filter condition:
  - **Comment begins with [Me]**
- This ensures that no records match the condition, resulting in an empty list.  
  ![filter option](photos/filter_option.png)

### 4. Styling the View

- Go to the **Style** section and select **Boxed, no labels**.
- This enhances the display of the restricted view.  
  ![style option](photos/style_option.png)

### 5. Configuring Mobile View

- Enable the option to make this the **default mobile view**.  
  ![mobile view](photos/mobile_view_default.png)

---

## Creating a Personal View for Advanced Users

Since our application does not include a built-in module for tracking version history, creating a dedicated view for version tracking can be helpful, especially for HR.

### Steps to Create a Custom View

1. Navigate to **Create View** and select **Standard View**.
2. Name the view, e.g., **my-view**.
3. Select all necessary fields that should be included in the view.
4. Mark this view as **Personal View** (only available to you).  
   ![standard view option](photos/create_standard_view.png)
   ![personal view](photos/personal_view.png)
   ![my view columns](photos/my_view_preview.png)

---

## View Access Restrictions Demonstration

Below are two screenshots demonstrating the results of the access control settings:

1. **Restricted User View:**

   - Only the **access_blocked** column is visible.
   - The user cannot modify, add, or delete records.
   - They also cannot add new columns to the view.

   ![normal view](photos/access_blocked_normal_user.png)
   ![normal view options column](photos/options_normal_view.png)
   ![no option to change view](photos/no_option_to_change_view.png)
   ![list 0 elements](photos/filter_list_0_elements.png)

2. **HR/Administrator View:**

   - Users with higher permissions can see additional columns.
   - They have the ability to add new columns to **my-view**.
   - Additional restrictions can be applied to prevent column modifications if necessary.

   ![advanced view - my view](photos/advanced_view_my_view.png)
   ![access to show columns](photos/posibility_to_show_columns.png)

---

By following this configuration, you can effectively restrict access to SharePoint views while allowing privileged users to perform necessary actions.
