# Setting up a ZURB Foundation Site ad publishing it online with Github User Pages

Here is a short walk-though to get a single page on github as a user page.  If i left off an details please leave me comments in the issues tracker.  thanks

## Setting up the repository and adding a ZURB Foundation template

|              |              |
|        ---      |        ---      |
|1. Set up a new repo as in the previous demo | [art3870winter2017-sample1](https://github.com/instructian/art3870winter2017-sample1)|
|2. Browse to ZURB FOUNDATION|https://foundation.zurb.com/|
|3. Download  ZURB FOUNDATION FOR SITES| ![complete download][one]|
|4. Upzip the archive and copy all the files into your empty repository
|5. Add an "images" folder | ![folder structure][three]|
|6. Open the index.html file in your editor (ATOM is a great choice)
|7. Add the repo as a project folder in Atom | ![setting a project folder in atom][two]|
|8. Add the following block to the index.html file and customize it. |
```
<!-- SEO SECTION AND PAGE TITLE -->
    <meta name="web_author" content="editorial staff of meta tags"> <!-- who made the site? -->
    <meta name="description" content="Don't forget about about meta tags, search engine optimization and submitting your website to the search engines."> <!-- what is this site about? -->
    <meta name="keywords" content="web design, web authoring, template, art 3870" /><!-- what are some search keywords you might be using to find this sites? -->
    <meta name="author" content="Ian Pollock"><!-- who wrote the content of the site - who is it about? -->
    <meta name="robots" content="index, follow"> <!-- do you want to search engines to search your site? -->
    <meta name="revisit-after" content="3 month"> <!-- update the search results every X? -->
    <title>Ian Pollock Web Portfolio | About Ian Pollock</title>   <!-- change the title for each page title | page name-->
<!-- END (to see all of the text, scroll to the right)-->
```
|9. Understand the ZURB Foundation X Y Grid structure |Learn the All-New XY Grid by ZURB Foundation! https://www.youtube.com/watch?v=tjjVKGeoi3A
Online Documentation https://foundation.zurb.com/sites/docs/xy-grid.html |
|10. Set up a basic home page for your portfolio using the grid||
|11. Create a new commit message||
|12. Commit the change||
|13. Push Origin to upload| |

## Publishing your USER Page

|   |   |
|---|---|
|1. Go to your Repository on Github|
|2. Go to the Repository Settings | ![go to the repo settings][four]|
|3. Scroll to the Settings > GitHub Pages Section under settings | ![pages settings][five]|
|4. Choose master branch as source and save
|5. scroll down to the Settings > GitHub Pages Section to see the URL for your site (it might take a few minutes to go live) |![pages settings][six]|
|6. Congratulations! You can now share this link with everyone and they can see your work live on the web.||
|7. For extra credit keep working to make an awesome portfolio and link it to a custom domain name.||

### EXTRA CREDIT  - buy and add you own domain name


### Here are some ZURB Foundation - XY GRID - tutorials.

1. Learn the All-New XY Grid by ZURB Foundation! https://www.youtube.com/watch?v=tjjVKGeoi3A
2. COMPREHENSIVE SESSION https://zurb.com/university/lessons/learn-the-flexbox-based-powerhouse-xy-grid
3. ALTERNATIVE BASIC INTRO https://www.linkedin.com/learning/learning-foundation-6/basic-setup-of-the-xy-grid


[one]: images/step1.png "DL Foundation for Sites - Complete"
[two]: images/step2.png "Add Project Folder"
[three]: images/step3.png "Add images folder"
[four]: images/step4.png "go to settings"
[five]: images/step5.png "choose master branch"
[six]: images/step6.png "go to the link to see your site"
