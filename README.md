# Project 1 - Static Website
# Vintage Denim Store

This website has been built for fictionary Denim store ReDenim, selling second hand jeans located in Edinburgh Scotland. The site provides information about the stores, services, their ideology and ways to contact them. The website was designed to cater towards an audience with interest in sustainable fashion, recycling, upcycling, vintage and styling services. The sites purpose is to attract potential customer for a visit or to reach out as the store does not have online platform for selling their items but is specialised in providing tailored service at store. 

![Am I Responsive](https://github.com/HMuraja/Portfolio1-The-Vintage-Denim-Store/blob/3efb387e724385235a5a5ad86f7b5f6649d0e784/readme-media/redenim-mockup.png)

## Features 

### Navigation Bar
  - A navigation panel and the store logo are present at the same location, top of the page, on all three pages. 
  - Each of the navigation panel items is linked to the page with the corresponding name. 
  - Navigation panel items are highlighted if the linked page is being viewed, working therefore an indicator of the current location. 
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![navigation](https://github.com/HMuraja/Portfolio1-The-Vintage-Denim-Store/blob/3efb387e724385235a5a5ad86f7b5f6649d0e784/readme-media/redenim-navigation.png)

### Footer

  - On the bottom of each page there is a footer containing the address, opening time and social media icons acting as link to the ReDenims social media accounts. 
  - If the icons are clicked, they will lead to the Instagram and facebook front pages. 
  - On the top of the footer there is header stating, “Visit Us!” informing the viewer that the information below should lead them to the store. 
  - This footer is present at the same location in identical form on all three pages, so the viewer has a quick access to the information for visiting the store. 
![Footer](https://github.com/HMuraja/Portfolio1-The-Vintage-Denim-Store/blob/3efb387e724385235a5a5ad86f7b5f6649d0e784/readme-media/redenim-footer.png)


### Home Page

  - Home page for this website contains an introduction statement and image as well as description of what ReDenim does.
  - The introduction image and description are on the top of the page and viewer will see this as the first thing when searching information about ReDenim. 
  - Introduction statement describes in one sentence what ReDenim is: “Sustainable option for fast fashion. Located in Edinburgh Stockbridge neighbourhood”. 
  - The background photo of jeans stacked on a shelf creating immediately an idea that ReDenim is a store with selection of jeans. 
  - Second part of the home page describes in more detail what the store offers and narrows this down into three topics that are squared in their own boxes. This information about should deepen the viewers understanding of ReDenims services and how it stands out among other retailers. 
  - The section detailing the denim expertise has a hyperlink to the services page, provide a seamless transition to more information on services page.


![Home Page](https://github.com/HMuraja/Portfolio1-The-Vintage-Denim-Store/blob/3efb387e724385235a5a5ad86f7b5f6649d0e784/readme-media/redenim-homepage.png)

### Service Page

 - Services page details the 4 types of services offered. These services are divided onto 4 boxes that lay next to each other or after each other depending on what size of viewport is used.
 - Above each service title there is a image giving the viewer a hint of the content before reading the text. 
 - Under some of the service links there is statement of cost of the service. 
 - A hyperlink is embedded into each one of the service texts, providing an easy and seamless access to the page with the query form in case viewer has any questions.


![Service Page](https://github.com/HMuraja/Portfolio1-The-Vintage-Denim-Store/blob/3efb387e724385235a5a5ad86f7b5f6649d0e784/readme-media/redenim-serices.png)

### Contact Us Page 

  - The contact us page offers a query form for the viewer in case they want to contact ReDenim about any other questions. 
  - This query form requires first name, second name, email, purpose of the query which is a dropdown menu, a text field for writing free text and a submit button stating “Send My Query”. 
  - As a background there is pile of folded jeans just keep up with the theme and also to provide a darker background that still looks interesting. 
  - All the fields require entry before being able to send the query. If the submit button is pressed before sending without filling all the field a message will pop up requesting to fill the missed field. 
  - If the field is selected the border will turn orange indicating for the viewer which box is selected.
  - The dropdown menu with the purpose of the query has 4 options: General, Repair and Tailoring, Fit and Style consultation and Donation and Recycling. 
  - Once the form has been completed and sent page will take you into the window from Code Academy informing that form was successfully completed. 

![Contact Us Page](https://github.com/HMuraja/Portfolio1-The-Vintage-Denim-Store/blob/3efb387e724385235a5a5ad86f7b5f6649d0e784/readme-media/redenim-contact.png)

### Features Left to Implement

- Page for explaining teh history of denim and jeans.
- A page with a quide for finding the best fit for the jeans.

## Testing 

- Websites responsiveness alternative screensizes was tested using chrome developer tools
- The CSS file stylesheet.css raw dta was copied and pasted on CSS Validator Jigsaw W3 text area. No erros were detected. Please see figure below or the following links:
http://jigsaw.w3.org/css-validator/validator$link
or
http://jigsaw.w3.org/css-validator/check/referer (for HTML/XML document only)
 
- All three files were run on the HTML Validator with following results.
  - When testing the index.html no errors were detected.
  - When checking services.html two errors were detected. Both were concerning stray end tags of “div” on lines 75 and 76. Strayed end tags corrected and second check performed without any further errors detected.
  - Contactus.html ran into two errors. First error occurred due to having “name” attribute twice on line 43 of file. One of the attributes removed to fix the issue. Second error occurred due to having “type” attribute for the textarea element on line 51. Bug fixed by removing the “type” and it’s value from the text area element attributes. Contactus.html ran again without any errors.

### Validator Testing 

- HTML
  - All three files were run on the HTML Validator [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
  - Two of th files had errors first time around:
     - When checking services.html two errors were detected. Both were concerning stray end tags of “div” on lines 75 and 76. Strayed end tags corrected and second check performed without any further errors detected.
     - Contactus.html ran into two errors. First error occurred due to having “name” attribute twice on line 43 of file. One of the attributes removed to fix the issue. Second error occurred due to having “type” attribute for the textarea element on line 51. Bug fixed by removing the “type” and it’s value from the text area element attributes. Contactus.html ran second time without any errors.

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://hmuraja.github.io/Portfolio1-The-Vintage-Denim-Store/


## Credits 

 - Gitpod was used to program and pre-view the webpage. Github was the repository for the files during the process and currently the storage for the finalized code. 

 - Coding Institute’s I love Running Project was a source for inspiration particularly when drafting the navigation menu and form for queries. 
 
 - Googles Developer Tool was used to test the webpage on different screen sizes and to troubleshoot any issues while building the website. 
 - W3 website was used as supporting material for the development of the site.



 ## Content
 - [Am I Responsive](https://ui.dev/amiresponsive) used to produce the image of webpage on different viewports.
 - [MyColorSpace](https://mycolor.space/) used to find complementary colors for the webpage.
 - [FontJoy](https://fontjoy.com/) used to find complementary fonts that I then used to create importable link in [Google Fonts](https://fonts.google.com/).
 - The icons used in this project were taken from [Font Awesome](https://fontawesome.com/)

 ## Media
 - Images are stock photos downloaded from [Pexels](https://www.pexels.com/). 
 - Images on Readme.md file are screenshot taken from this project.
