# O365.Documentor
About
-----
A console application which documents an Office 365 SharePoint site.
Use instructions from [here](http://en.share-gate.com/blog/how-to-build-an-inventory-before-sharepoint-migration) to export sites data and create an org chart in Visio to represent your Site Collection visually.

Getting Started
---------------
* Download the files in the Deployment folder
* Edit the Sukul.O365.Documentor.exe.config
* Provide values for the following keys:

Key  | Description
------------- | -------------
SiteCollectionURL  | the url of the SharePoint site collection
UserId  | user account to access the SharePoint site with. Needs to have admin access.
Password | password for the account above
OutputDirectory | directory where reports will be published
ContentTypeGroupName | the group name of content types to filter by
ColumnGroupName | the group name of site columns to filter by

* From the command line, run Sukul.O365.Documentor.exe and choose from the menus
![picture alt](http://pictures.sukul.org/blog/shailen/App.png "Office 365 Documentor")

Enjoy!
More reports will come as I find the time.

Shailen Sukul
[@shailensukul](https://twitter.com/shailensukul)



