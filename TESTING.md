# Testing

## Contents

This site has been tested using the following testing procedures

* [Code Validation](#Code-validation)  

* [Lighthouse Testing](#Lighthouse-Testing)

* [Browser Comaptibility](#Browser-Compatibility)

* [Manual Testing](#Manual-Testing)

* [Bug Reporting](#Bug-Reporting)


## Code Validation  

The site was run through noth wc3 and wc3 css validators.

![alt text](README-images/validator-testing-readme.png "Optional title")  

The results above apply no all pages, no errors were identified in the HTML files.  

![alt text](README-images/css-validator-testing-readme.png "Optional title")  

The results above apply no all pages, no errors were identified in the CSS file.   



## Lighthouse Testing  

I used lighthouse testing via Google Chrome Developer Tools and PageSpeed Insights.  

The site is tested against the following criteria;  

Performance  
Accessibility  
Best Practices  
SEO  

**Index**  

- Index desktop lighthouse score [here](README-images/Index-desktop-lighthouse.png "Optional title")  
- Index mobile lighthouse score [here](README-images/Index-mobile-lighthouse.png "Optional title")  

**About us**  

 - About us desktop lighthouse score [here](README-images/about-us-desktop-lighthouse.png "Optional title")  
 - About us mobile lighthouse score [here](README-images/about-us-mobile-lighthouse.png "Optional title")  

**Capabilities**  

- Capabilities desktop lighthouse score [here](README-images/capabilities-desktop-lighthouse.png "Optional title")  
- Capabilities mobile lighthouse score [here](README-images/capabilities-mobile-lighthouse.png "Optional title")  

**Opportunities**  

- Opportunities desktop lighthouse score [here](README-images/opportunities-desktop-lighthouse.png "Optional title")  
- Opportunities mobile lighthouse score [here](README-images/opportunities-mobile-lighthouse.png "Optional title")  

**Subscribe**  

- Subscribe desktop lighthouse score [here](README-images/subscribe-desktop-lighthouse.png "Optional title")  
- Subscribe mobile lighthouse score [here](README-images/subscribe-mobile-lighthouse.png "Optional title")  


## Browser Compatibility 
  
**Desktop**
  
Tested on Google Chrome Version 112.0.5615.138 (Official Build) (64-bit),  Microsoft Edge Version 112.0.1722.58 (Official build) (64-bit) and firefox Version 112.0.1 (64-bit)
  
**Mobile**
  
Tested on iphone 12 (iOS 16.3.1), iphone 13 (iOS 16.0) and 

## Manual Testing  

During the manual testing, I tested the sites functionality, usability and responsiveness.

**Functionality**

Home page  

Nav bar desktop 
Nav bar mobile  
Find Out More button  
Spinning globe on all devices  
View capabilities button  
Social media links in footer  

All features function as expected.

About us  

External links to Janes and Maxar
iframes  

All features function as expected.  

Capabilities  
Reveal the dog button  
img-zoom  
Google maps API  
Subscribe button  

All features function as expected  .

Form  
Form boxes  
checkboxes  
subscribe button  

All features function as expected.

**Usability**  

Some users found the images at the bottom of the page confusing. They were initally set to display a border on hover but there was no option to click on the actual image.

**Responsiveness**  

There were responsive issues on the Opportunities and Subscribe page, the default margin and padding that Bootstrap uses was causing overflow-x. To correct this, I added more bootstrap which removed the margin and padding.



## Bug Reporting

There were a few bugs discovered during the intial testing. I hadn't tested the responsiveness of the site on medium/large screens extensively and as a result;  
- iframes overflowed the container.  
- Form on the subscription page was not responsive in the way I orginally intended.  
- Images on the opportunity page were not responsive.  
- The nav bar was very cluttered on smaller screens meaning i needed to change the breakpoint for the collapsible navbar.  

I made the necessary changes by adding Bootstrap and adapting existing CSS to make the site more responsive for all screen sizes.  


