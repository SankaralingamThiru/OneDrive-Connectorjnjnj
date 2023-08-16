# OneDrive-Connector

This OneDrive Connector allows you to integrate your app with Microsoft OneDrive. You can create, update, and delete folders on and files on your OneDrive using this module.

# Dependencies

• Mendix modeler 9.19.0.

• MicrosoftGraph 

• Encryption

# Configuration

Complete the Authentication and Authorizations configuration on the Microsoft Graph module and ensure your Authentication is Active.

Required permission:

• Files.ReadWrite, Files.ReadWrite.All  -  Delegated (personal Microsoft account)
• Files.ReadWrite, Files.ReadWrite.All, Sites.ReadWrite.All  -  Delegated (work or school account)
• Sites.ReadWrite.All  -  Application

Follow these steps to add permission: Go to your AD registered app (which you configured in authentication) ->API Permission -> Add a permission -> Microsoft Graph.

Add the 'SNIP_OneDrive_Overview' snippet on your page.

These microflows help you to create, modify, and delete Folders and Files on OneDrive.

• ACT_Create_DriveFolder - This microflow is used to Create a new folder on our app and Drive.

• ACT_Update_DriveFolder - This microflow is used to modify the existing folder name on our app and Drive.

• SUB_Delete_DriveFolder - This microflow is used to delete the specific folders on our app and Drive.

• ACT_Upload_Document - This microflow helps to store the document on Drive.

• SUB_Delete_Document - This microflow helps to remove the files from Drive.

• GetFragmentFile - This JavaAction splits a single file into multiple based on length.

Note: Do not modify this module, we would recommend you duplicate and move it to your module.

# Screenshots

![Folder Overview](https://github.com/SankaralingamThiru/OneDrive-Connector/assets/141998014/03b24e00-650b-4240-b6d3-3fdea4ddb7fc)


![Document Overview](https://github.com/SankaralingamThiru/OneDrive-Connector/assets/141998014/49b7a0b6-f0b5-46e0-b7f7-676211c6f0cb)
