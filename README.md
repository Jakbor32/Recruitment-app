# Recruitment-app

User-friendly recruitment platform designed to streamline the hiring process, built with PowerApps, Power Automate (Flow), and SharePoint. It helps HR teams efficiently manage candidate applications, track progress, and automate workflows.

---

## Plan outline

### 1. Application Description

This application is a comprehensive HR solution designed to facilitate the secure recruitment of new employees. It focuses on ensuring that sensitive data, such as personal information and job applications, remains confidential and inaccessible to unauthorized users within the system.

The system was developed using a combination of powerful Microsoft technologies, including SharePoint, Power Automate, PowerApps Canvas App - modern controls and themes. By leveraging PowerApps, we provide a seamless user interface for HR professionals to manage the recruitment process. Teams Approvals and Outlook notifications are integrated for streamlined communication and decision-making. Additionally, the application automatically generates PDF documents for recruitment-related forms, improving efficiency and reducing manual paperwork.

![recruitment app](https://github.com/Jakbor32/recruitment-app/blob/main/media/app/photos/add_request_screen.JPG)

### 2. Application Features

#### PowerApps:

- **Submit, Edit, or Delete Requests**: Users can submit new requests, edit existing ones, or delete them directly from the application interface.
- **Authorized Access**: Access to the application is based on security groups, with two levels of access: regular access and restricted access.
- **HR Request List**: HR personnel have access to a complete list of all requests, with full visibility and management rights. Regular users do not have access to this list.
- **My Requests**: Regular users can view and manage only their own requests.
- **Request Preview**: Users can preview the details of a selected request, including all relevant information.
- **Request Browser in PDF Format**: HR personnel can view and download request forms in PDF format. Access to these PDFs is restricted to HR users only.

#### Power Automate:

- **Request Approval via Teams Approval**: The application integrates with Microsoft Teams to facilitate the approval process for requests.
- **Email Notifications**: Users receive email notifications upon the acceptance or rejection of their request.
- **Comment Tracking**: Comments added during the approval process are saved and visible to subsequent approvers, ensuring that feedback is easily accessible and traceable.
- **Request Status Updates**: The status of requests changes dynamically throughout the approval or rejection process. A built-in registry tracks the progress of each request, with SharePoint being used to view the approval history and status updates.
- **PDF Document Generation**: Requests are automatically generated as PDF documents, ensuring consistent and professional documentation.
- **Correction Module for Rejected Requests**: If a request is rejected, the applicant receives a unique link to directly access the application and make corrections to the specific request that was rejected.

#### SharePoint:

- **Centralized Data Storage**: SharePoint is used to store and manage all data related to requests, ensuring secure and organized data management.
- **Audit Trails**: SharePoint tracks all actions performed on requests, providing a clear audit trail for compliance and transparency.
- **Restricted Access**: Only HR personnel have full access to the SharePoint data. Other users have no access.
- **Data Security**: To ensure data security, users cannot submit or modify requests directly through SharePoint. All request-related activities must be handled within the PowerApps application, ensuring that only authorized personnel can make changes to sensitive data.

### 3. How the Process Works

### 4. Technologies

- **Microsoft PowerApps**
- **Microsoft Power Automate**
- **SharePoint**
- **OneDrive for Business**
- **Microsoft Teams**
- **Outlook**
- **Microsoft 365 Groups**

### 5. System Requirements

- **Microsoft PowerApps** - PowerApps Per User, PowerApps Per App
- **Microsoft Power Automate** - Power Automate Per User, Power Automate Per Flow
- **SharePoint** - SharePoint Online Plan 1, SharePoint Online Plan 2
- **OneDrive for Business** - OneDrive for Business Plan 1, OneDrive for Business Plan 2
- **Microsoft Teams** - Microsoft 365 Business Standard, Business Premium, Enterprise E3, Enterprise E5
- **Outlook** - Exchange Online Plan 1, Exchange Online Plan 2

### 6. Installation and Configuration

#### 1. SharePoint:

- [Link to configure list and columns](https://github.com/Jakbor32/recruitment-app/blob/main/media/sharepoint/lists/README.md)
- [Link to configure sharepoint list security and groups](https://github.com/Jakbor32/recruitment-app/blob/main/media/sharepoint/security/README.md)
- [Link to configure sharepoint views](https://github.com/Jakbor32/recruitment-app/blob/main/media/sharepoint/views/README.md)

#### 2. PowerApps:

- [Link to configuration](https://github.com/Jakbor32/recruitment-app/blob/main/powerapps/README.md)

#### 3. Power Automate:

- [Link to configuration](https://github.com/Jakbor32/recruitment-app/blob/main/power-automate/README.md)

### 7. Using the Application

### 8. Security and Access

### 9. Troubleshooting

### 10. Future Development and Roadmap
