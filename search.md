## How to implement search in your asciibinder generated documentation?
- The fork of repo generates the data.json which is indexed in frontend
- By default there is a page called search.html which is persent in your _templates directory where all the search results are displayed
- We use elasticlunr a javascript library to index and search the data in the documentation
