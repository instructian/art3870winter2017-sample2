# Setting up a ZURB Foundation Site ad publishing it online with Github User Pages

Here is a short walk-though to get a single page on github as a user page.  If i left off an details please leave me comments in the issues tracker.  thanks

|              |              |
|        ---      |        ---      |
|1. Set up a new repo as in the previous demo|[art3870winter2017-sample1](https://github.com/instructian/art3870winter2017-sample1)|
|2. Browse to ZURB FOUNDATION|https://foundation.zurb.com/|
|3. Download  ZURB FOUNDATION FOR SITES| ![complete download][one]|
Upzip the archive and copy all the files into your empty repository
Add an "images" folder | ![folder structure][three]|
Open the index.html file in your editor (ATOM is a great choice)
Add the repo as a project folder in Atom | ![setting a project folder in atom][two]|
Add the following block to the index.html file and customize it.
```
<!-- MAKE SURE YOU TAKE ADVANTAGE OF THIS SECTION! -->
    <meta name="web_author" content="editorial staff of meta tags"> <!-- who made the site? -->
    <meta name="description" content="Don't forget about about meta tags, search engine optimization and submitting your website to the search engines."> <!-- what is this site about? -->
    <meta name="keywords" content="web design, web authoring, template, art 3870" /><!-- what are some search keywords you might be using to find this sites? -->
    <meta name="author" content="Ian Pollock"><!-- who wrote the content of the site - who is it about? -->
    <meta name="robots" content="index, follow"> <!-- do you want to search engines to search your site? -->
    <meta name="revisit-after" content="3 month"> <!-- update the search results every X? -->
    <title>Ian Pollock Web Portfolio | About Ian Pollock</title>   <!-- change the title for each page title | page name-->
    <!-- END! -->
```




|4. Fill in the fields (make sure you pay attention to the paths!)|![fill out the fields][two]|
|5. Create the Repository - check on your computer for the folder| ![check on your computer][three]|
|6. Upload the Repository to GitHub by creating a commit message and Publishing GitHub (first time only)|![publish][four]|
|7. Make changes to the read me file|
|8. Create a new commit message|
|9. Commit the change|
|10. Push Origin to upload| ![Push Origin][five]|

### Here is a Markdown Cheatsheet https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
### Here is a introduction to github that you should watch https://youtu.be/BCQHnlnPusY


[one]: images/step1.png "DL Foundation for Sites - Complete"
[two]: images/step2.png "Add Project Folder"
[three]: images/step3.png "Add images folder"
[four]: step4.png "New repo setup"
[five]: step5.png "New repo setup"
