# Project_1- 

# Ye Olde Fish and Chippe Shoppe 

## Introduction 

Ye Olde Fish and Chippe Shoppe is a site all about the shop and what the business strives to aim to achieve for its customers. It aims for customers to be able to see what there actually coming to when collecting there food with photos and also allows them to have a look at a menu before they arrive. 




### User Stories 

* As the organisation we want to be able to provide customers with a site to be able to browse the food menu prior to there arrival. 

* As a user I want to easily find information about prices in the shop. 

* As the organisation we want to provide customers with a map to be able to find us. 

* As the organisation we want to provide the customers with the ability to go from our site to other sites to do with us ie tripadvisor and facebook. 







## Wireframe mockups 



For my wireframes I used just normal pen and paper to sketch out the initial layout of the site as time went on the wireframes became outdated and I noticed un-practical and non friendly themes for people with accessibility issues. Therefore I did make changes and carried this out on a seperate programme. 

![Home Page Wireframe](documentation/wireframes/home-page.png)
![Menu Wireframe](documentation/wireframes/menu.png)
![Query page Wireframe](documentation/wireframes/query-page.png)

I completed the overall structure of the site from home page to menu page etc. I then put this into practice and layed it out via gitpod and noticed there was also a few more issues such as text and color contrast issues. 


## Features 



### Common Features for sites 

* Navigation Bar 

* The navigation bar features a common design across all of the pages and is in keeping with the shops logo and overall sites theme. 

* The navigation bar includes links on the logos on the left and right of the main  header the nav bar consists of a , Home, Menu, Queries/contact. The various title links head to the according website pages this allows the user to have easy navigation on the site. 

* The navigation bar is fully responsive, for smaller screens, the bar will become smaller text wise and group on the left still being obvious as a nav bar.   * A horizontal line appears under the page that is about to be selected done via the hover function I found that since the site only consisted of 3 pages it didn’t require a underline function to show which page was selected due to it saying below the nav bar on the page (Home,Menu,Queries). 

![Nav Bar](documentation/wireframes/navbar.png)

* Hero image 


* Each page includes a hero image with a text overlay to show that they are still on the same site and can navigate around and understand what page they are on within the site. 

* The image was carefully chosen via pixel as I wanted it to be light enough to ensure it draws the customer into the site. And to allow the text overlay with the title of the shop on there but not cause a contrast issue. 

![Hero Image](documentation/wireframes/hero.PNG)

* Footer  


* Each page includes a common footer which has just two buttons which allows them to access reviews of the shop from tripadvisor a well known review site within the food industry.   

* There is also a call to action for the user to then use the facebook page and tripadvisor to leave there reviews along with access to telephone numbers 


IMAGE 







### Home Page Features 




* Home page 




* The home page includes a brief description and intro to the shop showing what the team believe in and what they want to achieve for customers along with the reassurance to customers of the hard work that everyone works for. 

* There are also a small inline-block element of photos showing the shop along with the food served to entice customers to come and buy from us.   

* Further down there is a call to action for customers with a contact number f they chose to visit us or to even place an order via the phone. 

* Also another inline-block element which consists of different fish for sale and what they are like as a product. 


IMAGE 




### Menu Page Features 




* Menu page   

* The main section of the Menu page is just a menu set out to allow visitors to see a detailed menu with prices and also sizes. It offers to a wide range of customers from Adults, Children and seniors. 




### Customer feedback/Queries page 




* The main section of this page is to allow customer to reach out to us with any questions or issues they may face or be concerned about. A small dialogue above the contact form shows that there may be a small wait upon reply from filling the form out however will be answered as quick as possible. 


IMAGE 




* There is also a map to allow customers to locate us and find us which is embedded in the page via google maps. 


IMAGE 







* Hidden Page 




* There is only one page that is hidden and not viewable. This page is the page that customers are greeted with when they fill out the contact form. This is important so customers know that they have submitted something to the site and that the “submit” button is actually doing something. 


IMGAE 




## Future Enhancements 




In future enahncements I would like to try and combine a online ordering system, this therefore will mean customers can organise food without even leaving the house.  

I would also be interested in also adding a gallery page to allow customers to see all the food before commiting to buy. 



## Testing 

I took a methodical and a two stage process on development I was continuiosly testing the site to ensure that there wasn’t any obvious issues with the sites such as simple links directed me to the correct pages. When I started to style the site and to give it its own “theme”. I checked that when styling the site in the launch window that the stlyes were being applied accrodingly.  




For the second part of my testing once the site was completed I used a more structured way of testing and used the “WAVE Report” webiste to see that all my HTML code was correct without any errors in the code. I then carried out testing on multiple devices and software this allowed me to asses any issues in the code or the layout depending on what was hosting the site.  

Testing was performed with the following devices/browsers: 

* 2560 x 1440p 

* Google Chrome (laptop) 

* Firefox (laptop) 

* Microsoft Edge (laptop) 

* iPad: 1536 x 2048 display 

* iOS Safari (ipad) 

* iPhone Xr: 828 x 1792 display 

* iOS Safari 






* Interesting Bugs 

*  One interesting issues I faced when coding the site was that there was an issue with the “sticky” element of my nav bar. I found this fault in early stages of development and found that it was because of a fault in my coding and this was due to me adding an extra “div” element in the site and was therefore only being the sticky bar within the element itself rather than it being an independent element and moving freely across the whole site. I addressed this issue and changed my code accordingly. 




* Another fault that I did find was the fact that when shrinking the size of the screen down the media query wasn’t applying the correct parpameters to the “fish section” the inline boxe elements were aligning left. 


## Validator Testing  




* HTML  

* No errors were returned when passing through the official W3C Validator. 

VALIDATOR OF HTML WAVE! LINKS 




* CSS 

* No errors were returned when passing through the official (Jigsaw) Validator  

LINK TO CSS VALIDATOR 


* Lighthouse 

* I generated a lighthouse report for the deployed site through the Google Chrome Dev Tools. I generated both a desktop and mobile report.  

* For the initial desktop report, the SEO score had a warning that the site did not have a description within the meta tags, to resolve this and improve the score a description was added to the site. 



LIGHTHOUSE REPORT?  



* For the initial mobile report, the performance score was 79 due to the size of the hero image. To resolve this and improve the score a smaller image was created for the hero image on mobile devices. Utilising the media queries to call the smaller image on mobiles. 





## Deployment

This project has been deployed to GitHub Pages.
From the repository, I went to the "Settings" tab and selected "Pages" from the sub-menu.
Once there, I selected the "main" branch from the dropdown, and then clicked the Save button.

The deployed site can be found [here](https://olivertrain1221.github.io/Ye-olde-fish-and-chip-shop).

### Local Deployment

If you would like to make a clone of this repository, you can type the following command in your terminal:

- `git clone https://github.com/Olivertrain1221/Ye-olde-fish-and-chip-shop.git`

Alternatively, if you are using Gitpod, you can simply click on the green Gitpod button at the top of the repository, and this will create a new workspace in your Gitpod account. [This link](https://gitpod.io/#https://github.com/Olivertrain1221/Ye-olde-fish-and-chip-shop) will do the same thing for you if you do not see the green Gitpod button. 

## Credits 




### Content   

* 



### Media  

* 