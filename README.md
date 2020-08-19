## Upload SalesForce File(s) in SharePoint Online Document Library 
- Upload file from SalesForce to SharePoint Online
- View/download file in salesforce
- Delete file from Salesforce 
- Generate public link for sharepoint file and can be share with external users.



## Pre-requisites :
- IIS version : 10
- .NET framework version : 4.7
- Web-Installer : Need to install Web-Installer
- Make sure that 'TempDownloads' folder is present in root folder.

## Parameters Settings :
Please refer ParametersSetting.txt to set parameters used in application.

## SharePoint Settings :
Please create following Meatadata columns in SharePoint Libraries(Internal/External)
- Classification: Single Line of text
- Description: Multiple Line of Text(Plain Text)
- UploadedBy: Single Line of text
- UploadedDate: Single Line of text
- ModifiedBy: Single Line of text
- ModifiedDate: Single Line of text

## How to enable external sharing for the SharePoint site:
 This application is alllow to share files uploaded in SharePoint Document Library to External Users(Users who don't have sharepoint access).
Please refer EnableSharePointExternalSharingSettings.docx file to enable external sharing for site to access public link for external user.
This setting is done in SharePoint Administrator Portal by SharePoint Admins only.


## How to Publish web deployment package to IIS
please refer "How to publish web deployment package to IIS.docx" file to publish web deployment package to IIS.

 
