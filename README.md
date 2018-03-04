# Simple-Image-Gallery
## A Web App that you can uplaod images, like an Imgur Clone
An image gallery that connects to a Azure storage blob where all uploaded images are saved. Images can have title and tags issued to them as well.

## Tools Used:

1. C#/ASP.NET Core 2.0.3.
2. SQL Database with Entity Framework as our ORM.
3. Azure Blob Storage.
4. CSS3 - some styling from a basic default App template.

## Azure Connection
You will need a connection string from your Azure storage account found under the keys options that has to be stored s a JSON string in the User Secrets of the application.

## Known Issues:

1. Bug for deleting images from Database has now been fixed. Follow how the process [here](https://github.com/johnmcraig/Simple-Image-Gallery/issues/1).

# Future Features to be Implemented

- A Search Query to find images by Title and Tag strings.
- Pagination - Page numbers on the gallery if it gets larger.
- Able to edit tags.

### Thanks where thanks need to be Credited

1. Wes Doyle - A freelance developer who has a tutorial to get started on this project from scratch.
2. Jeff Ammos - instructor of CCALearn, a bootcamp I attended for six months, who helped guide me on this application.

