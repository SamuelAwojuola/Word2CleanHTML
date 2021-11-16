# Word2CleanHTML
This is to have an offline MS Word to Html converter to make creating and uploading files to my github repository easier.
On clicking the upload button, the assigned github repository will be opened and a generated file will be downloaded which you may then upload to the repository.
## Set Up
It requires that the repository with the layout and categories already be created. These then will be made into a select list from which the relevant the desired layout and category is selected. 
There are two versions here,
1. "Word2CleanHTML JSON.html" which generates the categories and layouts from a JSON file (githubLayoutsCategories.json) in the root directory. Edit the JSON file to,
* Set the github repository to open when you click the upload button. This would be the repository to which you intend to load the generated file. 
* Edit the list of categories,
* Edit the list of layouts
2. "Word2CleanHTML.html" which does not use any JSON file. To modify the layouts and categories list, you have to edit the html file itself.
