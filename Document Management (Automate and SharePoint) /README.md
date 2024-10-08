# Document Management System

## Overview

This project expands upon the core Document Management System (DMS) functionality with powerful customization for organization, approval, and metadata management. Building upon the features described in the original readme, we've further enhanced the system for increased usability and efficiency.

## Enhanced Features:

### Granular Permissions:

**Inheritance Broken:** Specific permissions granted for read, edit, and other actions to designated groups, ensuring precise control over document access. (Originally mentioned)
### Custom Metadata Management:

**File Status Tracking:** A "Status" column categorizes files as Approved, Rejected, or Pending for efficient filtering and grouping. (New addition)

**Approver Identification:** An "Approver Name" column stores the individual who approved or rejected each file, providing clear accountability. (New addition)

### Organized Folder Structure:

**Type-Based Folders:** Dedicated folders ("CSV", "PDF", "MP4", "JPEG") automatically group files based on their extensions, simplifying navigation and retrieval. (New addition)
### Automated Workflows:

**Approval-Driven Status Update:** A Power Automate flow triggered by file creation updates the status based on the approval outcome (Approved/Rejected), respectively moving files to designated folders. (New addition)
**Weekly Rejected File Cleanup:** Another flow automatically deletes Rejected files older than one week, streamlining storage management. (New addition)

### Enhanced Views:

**Calendar View:** Month-based calendar view for documents with associated deadlines or dates. (Originally mentioned)
**Standard Views:** Customizable list views with columns like title, author, date, and status. (Originally mentioned)
**All Documents View:** Comprehensive listing of all documents in the library. (Originally mentioned)
## Visual Cues:

**JSON formatting:** Color-coded status labels (green for Approved, red for Rejected) in views and columns offer quick visual indicators. (New addition)


### Additional features:

**Version Control and Approval Workflows:** Track changes and implement review/authorization processes to ensure document accuracy and control.
User Access and Security: Granular permissions (read, write, delete, upload, manage) assigned to user groups for secure document access control.

**Auditing and Logging:** Track user actions within the SharePoint environment for enhanced accountability and transparency.
Benefits:

**Improved Accessibility:** Intuitive folder structure and categorized views simplify document access and retrieval.
Enhanced Collaboration: Granular permissions and clear approval trails ensure proper control and accountability.
** Added Approved date from Column**: to know the days passed frpm the Approved date 

**This enhanced DMS system empowers users with efficient document management, clear access control, and automated workflows, contributing to a more organized, collaborative, and secure workspace.**
# Exported  Automated Flows


**Approval-Driven Status Update**: 
[Approval-DrivenStatusUpdate_20231218080909.zip](https://github.com/CodePointCreativesPowerPlatform/Project-1-Document-Management-/files/13701083/Approval-DrivenStatusUpdate_20231218080909.zip)

<img width="150" alt="Screenshot 2023-12-18 111646" src="https://github.com/CodePointCreativesPowerPlatform/Project-1-Document-Management-/assets/89215713/c27cff73-1042-4681-83d0-61c6fced4841">
<img width="150" alt="Screenshot 2023-12-18 111655" src="https://github.com/CodePointCreativesPowerPlatform/Project-1-Document-Management-/assets/89215713/41d35592-1c2c-4460-9150-096bdaffd6f4">
<img width="150" alt="Screenshot 2023-12-18 111747" src="https://github.com/CodePointCreativesPowerPlatform/Project-1-Document-Management-/assets/89215713/9d4fdabb-5edf-4c59-864e-17fcf1e87571">
<img width="150" alt="Screenshot 2023-12-18 111806" src="https://github.com/CodePointCreativesPowerPlatform/Project-1-Document-Management-/assets/89215713/b4b457d4-146f-46f8-8628-e8744a59b87d">
<img width="150" alt="Screenshot 2023-12-18 111821" src="https://github.com/CodePointCreativesPowerPlatform/Project-1-Document-Management-/assets/89215713/2ca33f1f-7027-4829-ae26-54760735621f">

**Rejected File Cleanup Flow**:
[RejectedFileCleanup_20231218081009.zip](https://github.com/CodePointCreativesPowerPlatform/Project-1-Document-Management-/files/13701081/RejectedFileCleanup_20231218081009.zip)


<img width="150" alt="Screenshot 2023-12-18 112225" src="https://github.com/CodePointCreativesPowerPlatform/Project-1-Document-Management-/assets/89215713/83566cd5-1931-4eee-aa42-2539b79cc379">

## Snapshots From Document Library

<img width="300" alt="Screenshot 2023-12-18 113312" src="https://github.com/CodePointCreativesPowerPlatform/Project-1-Document-Management-/assets/89215713/5526a703-fbc2-48e1-b160-dda9343face7">
<img width="300" alt="Screenshot 2023-12-18 113328" src="https://github.com/CodePointCreativesPowerPlatform/Project-1-Document-Management-/assets/89215713/92949b7d-9221-4d31-982f-4d4a2f869de5">
<img width="300" alt="Screenshot 2023-12-18 113353" src="https://github.com/CodePointCreativesPowerPlatform/Project-1-Document-Management-/assets/89215713/831c71a0-62a1-4e96-a9a3-6035a9b94227">
<img width="300" alt="Screenshot 2023-12-18 113430" src="https://github.com/CodePointCreativesPowerPlatform/Project-1-Document-Management-/assets/89215713/8dfbaab0-4afa-4485-8a15-56bb89073474">





