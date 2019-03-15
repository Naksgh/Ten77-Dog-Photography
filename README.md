# Ten77 Dog Photography
Link to the live website on GitHub Pages : https://naksgh.github.io/ten77/

## Project Overview

For my first milestone project I developed a website to promote Ten77 Dog Photography, an independent business based in the North East of England. Ten77 was launched by Nick, a retired police dog handler, who offers an informal photography service to provide potential customers with portraits or action shots of their pets. 
With Nick’s permission I have developed this website with the aim that it will provide a platform for his potential customers to gather information about the service, view Nick’s previous work and easily contact him with any queries.


## UX 

The website is designed to cater for a variety of people interested in Nick's work. The anticipated visitors to the site would be potential customers, potential collaborators, existing customers and local business competition. Each visitor will naturally have a different goal when visiting the website and I have aimed to accommodate for all of these. My main aims of the project were therefore to showcase Nick's work, provide sufficient relevant information and create an accessible platform through which to communicate with Nick. Listed below are my anticipated User Stories:
* A prospective customer, who would like examples of the style of animal photography Nick is able to create in order to decide if they would like to use the service, would be able to access these by visiting the gallery. 
* A prospective business collaborator, who would like to approach Nick with a business proposition, could achieve that by visiting the contact page or pressing the Ask Nick button.
* A prospective customer, looking for any further information regarding the service such as pricing, could contact Nick through the Ask Nick button or by visiting the contact page.
* A prospective customer, who would like to find out if there are any other information outlets for Ten77 Dog Photography, could do so by visiting the social media links in the footer of each page.
* A prospective customer, who would like to find out about any new offers or local promotions, could do so by visiting the monthly offer board in the middle of the home page.
* A prospective customer or collaborator, who would like to find out more about Nick and his background, could achieve this by visiting the About Us page.

While planning the website I created a WireFrame for the index image: https://imgur.com/S8jVcDW <br>
I then used this same template when developing the additional pages, changing only the middle section (content) on each to fulfil the aims of that page. 

## Features

1. Allows customers to contact Nick, by having them fill out the form in 'Contact Us' page.
2. Allows customers to contact Nick, by having them fill out the form in the 'Ask Nick' button
(please note that the modal box is not actually working and is only for display purpose)
3. Allows prospective clients to view Nick's sample work, by visiting the 'Gallery'
4. Allows prospective clients to find out more about Nick and his background, by visiting the 'About Us' section
5. Allows prospective customers to view this month's offer, by visiting the 'This Month's offer' board on the main page
(please note that the modal box is not actually working and is only for display purpose)
6. Allows prospective clients to view reviews about Nick's work, by visiting the bottom part of the index page
7. Allows any visitors to view alternative social medias for Ten77, by visiting the footer of any page
8. Allows any visitors to navigate back to the main page, by clicking the logo above the nav on any of the pages

## Technologies Used

This project has used Cloud9, which is a cloud-based integrated development environment allowing you to write, run and debug your code using just the web browser. <br>
https://aws.amazon.com/cloud9/?origin=c9io <br> 
The newest version of Hypertext Markup Language (HTML5) was used to build the structure of the website, while the newest Cascading Style Sheets (CSS3) was used for describing the presentation of the documents written in HTML.  <br>
https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5 <br>
https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3 <br>
Furthermore this project has used Bootstrap 3.3.7 Framework which provided a variety of pre-made CSS styles and Java Script components, which I specifically used for the modal and carousel. <br>
https://getbootstrap.com/docs/3.3/getting-started/#download-cdn <br>
Custome CSS styles were also used <br> 
(../assets/css/style.css)<br>
jQuery was used to run the required Java Script to implement the modal pop-up and carousel (included with Bootstrap 3.3.7). 
Google Fonts were used to style the fonts used.<br>
https://fonts.google.com/<br>
CDNJ's hover.css library was used for hover effects. <br>
https://cdnjs.com/libraries/hover.css<br>
Font awesome icons were used in this project. <br>
https://fontawesome.com/<br>
All of the art belongs to Nick, the rightful owner, and I have received his permission to use all of it in my project.<br>
https://www.facebook.com/ten77dogphotography/<br>

## Testing 

A prospective customer, who would like examples of the style of animal photography Nick is able to create in order to decide if they would like to use the service, would be able to access these by visiting the gallery. 
1) go to 'Gallery' page on the website
2) once loaded click on any image 
3) a new tab will open that will take the user to the main gallery of Ten77 Dog Photography Facebook page

A prospective business collaborator, who would like to approach Nick with a business proposition, could achieve that by visiting the contact page or pressing the Ask Nick button.
1) go to 'Contact Us' page on the website
2) once loaded try submitting an empty message with no e-mail to ensure an error message would appear 
3) try submitting an empty message without the @ sign in the e-mail field to ensure appropriate error message would appear
4) try submitting an empty message with an actual email address to ensure the appropriate error message appeared
5) try submitting a message with a real email to make sure it works

A prospective customer, looking for any further information regarding the service such as pricing, could contact Nick through the Ask Nick button.
1) open any page except 'Contact Us' 
2) locate and press the 'Ask Nick' button
3) Try submitting an empty message without any of the fields filled in to make sure the appropriate error message appeared
4) Try submitting an empty message without the @ sign in the email field to make sure the appropriate error message appeared
5) Try submitting an empty message with a real email address to make sure an appropriate message appeared
6) Try submitting a message with a real email address but no name, to make sure it goes through. The name field is not marked as required on the 'Ask Nick' form.

A prospective customer, who would like to find out if there are any other information outlets for Ten77 Dog Photography, could do so by visiting the social media links in the footer of each page.
To visit the social links in the footer:
1) open any page
2) scroll to the bottom 
3) press on the Facebook, Instagram or Twitter social icons in the footer to be re-directed to the respective website (please note that Ten77 Dog Photography is only using Facebook outside of this project, so the Twitter and Instagram icons are going to direct the user to their main websites)

A prospective customer, who would like to find out about any new offers or local promotions, could do so by visiting the monthly offer board in the middle of the home page.
1) go to the Monthly Offer board located in the middle of the home page
2) read the information & press the 'Sign up' button 
3) submit an empty form to make sure that error message will appear
4) submit a form with only the name to make sure that error message will appear
5) submit a form with the name and an email address without the @ sign to make sure the appropriate error message would appear 
6) submit a form with both fields filled in to make sure it works

A prospective customer or collaborator, who would like to find out more about Nick and his background, could achieve this by visiting the About Us page.
1) go to 'About Us' section on the webpage 
2) read the content 

When viewing the website in desktop mode it appears the same in Chrome, Firefox and Opera browsers. The only exception being the border element on the top of the footer and the bottom of the nav bar. This border appears the same in Chrome and Opera but different in Firefox (thicker black border, opposed to a white one with a thin dark underline). <br>
I also experienced a  challenging bug with the social media icons through out the project. The icons would not appear in real time on certain smaller devices (phones and tablets) and would always appear on laptops and PC's (desktop size devices). <br>
Clearing the cache and cookies on smaller devices has fixed the issue. <br>
The mobile first approach was used when creating this website, therefore there are some responsive elements to the site
<br>

### Index:
* There are 2 logo images, the larger one is displayed at MD and above, while the smaller one can be seen on small devices and below.
* The offer alert above the logo picture on the index page is hidden on small devices. 
* The main navbar collapses from four icons on a single row to two icons over two rows on medium and smaller devices.
* In desktop view, the offer board (Jumbotron) has both a shadow effect and colored margins on the left and right side, these disappear on medium devices and below using media queries.
* The Reviews section collapses into a row per review on medium devices and below, whilst on bigger devices they share a single row.
### Gallery: 
* The album on small devices will collapse into one picture per row, whilst on medium and above devices it will show three pictures over three rows.
### About us: 
* The content text changes its font-size using media queries.
* On smaller devices the carousel will not display at all, instead a static image will be used. On medium and above devices the carousel with appear showcasing 3 images.

## Deployment 

For deployment I used GitHub Pages. These are the steps I took: 
1) open the browser 
2) go to www.github.com 
3) log in into your account 
4) go to your repositories 
5) choose the right repository 
6) go to the Settings 
7) scroll down to the GitHub Pages section which is located 3/4 down the page
8) select master branch as the source
9) the deployed GitHub page link will be visible at the top a few minutes later
There are no differences between the deployed and the development versions.

## Credit 

### MEDIA
* All pictures in the gallery and about us section were used with the permission from the rightful owner Nick
* Rachel Shelley and Samuel Wetton have both given permission to use their images in the review section

### ACKNOWLEDGEMENT 
* Thank you Nick for allowing me to create this website
* Thank you Chris Zielinski, my mentor, for supporting me throughout the creation of this project
