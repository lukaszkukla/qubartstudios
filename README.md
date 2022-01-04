![QubartStudios](assets/images/QubArtSudiosJakubTomczykPhotographyLogo-350x182.jpg "Qubart Studios")

# Qubart Studios 

# goal for this project
Welcome to Qubart Studios. This is a professional photographer's website. The domain of Qubart Studios is wedding photography. 

The site targets potential cusotmers who are planning their weddings. It gives an overview of previous artwork and backs it up with strong customer testimonials.

Customers can get in touch with the studio direclty by the phone, through the contact form or social media.

The main goal of the project is to give a modern look to the old website and learn along the way.

# table of contents

* [UX](#ux "UX")
    * [user goals](#user-goals "user goals")
    * [user stories](#user-stories "user atories")
    * [site owners Goals](#site-owners-goals)
    * [user requirements and expectations](#user-requirements-and-expectations)
         * [requirements](#requirements)
         * [expectations](#expectations)
     * [design choices](#design-choices)
        * [fonts](#fonts)
        * [icons](#icons)
        * [colours](#colours)
        * [structure](#structure)
    * [wireframes](#wireframes)
    * [features](#features)
        * [existing features](#existing-features)
            * [navigation bar](#navigation-bar)
            * [landing page](#landing-page)
            * [about section](#about-section)
            * [events section](#events-section)
            * [contact section](#contact-section)
            * [footer](#footer)
        * [features to be implemented](#features-to-be-implemented)
    * [technologies used](#technologies-used)
        * [languages](#languages)
        * [tools and libraries](#tools-and-libraries)
    * [Testing](#testing)
        * [unfixed bugs](#unfixed-bugs)
    * [deployment](#deployment)
    * [credits](#credits)
    
# UX

## user goals
* visually appealing, including images
* easily navigated around
* quality and valuable content
* easily found contact details
* form to directly contact the club

## user stories
* as a user, I want to see professional artwork of the photographer
* as a user, I want to contact studio by phone
* as a user, I want to contact studio by email
* as a user, I want to contact studio through website
* as a user, I want to contact studio by facebook
* as a user, I want to contact studio by instagram
* as a user, I want to get back to home page easily
* as a user, I want to see recent artwork
* as a user, I want to see testimonials of previous customers
* as a user, I want to see basic information about the studio

## site owner goals
* modernise the existing website
* increase traffic to the website
* increase customer conversion
* optimise organic SEO

### requirements
* clearly visible contact details and methods
* information about services
* visaully appealing, neat and tidy design
* responsive desing to accomdate modern screen sizes

### Expectations
* I expect to see contact details on every page
* I expect all contanct details to be correct
* I expect all links to work
* I expect all external links to open in new tabs
* I expect fast website load without loss of image quality
* I expect confirmation message on form submission
* I expect webiste will work on phones, tablets and laptops

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

## Design Choices

### Fonts
I used [Google Fonts](https://fonts.google.com/ "Google Fonts"). The main text is [Noto Sans](https://fonts.googleapis.com/css2?family=Noto+Sans&display=swap "Noto Sans"). [Poppins](https://fonts.google.com/specimen/Roboto+Slab?query=rob "Poppins") is used for the headers and the navigation bar. 

### Icons
I used [Font Awesome library](https://fontawesome.com/ "Font Awesome") for extra visual cues.

### Colours

~~I have used [Colourmind](https://colormind.io/ "colourmind") to help in the selection of my colour scheme. I selected the initial colour that I wanted the reast of my pallet to fit with and then used the generator to create the pallet, it can be seen [here](wireframes/colour_pallet.JPG "Generated Colour Pallet"). However when I tested the contrast of the colours in [WebAIM](https://webaim.org/resources/contrastchecker/ "WebAIM"), the contrast ratio from the text colour to the background colour was not good enough and failed tests, they can be seen [here](wireframes/contrast-checker.JPG "Failed tests"). After adjusting the colours manually, I gained a pallet that still gave great impact and had great contrast, these are the results for the contrast checker are [here](wireframes/contrast-checker-adjusted.JPG "Adjusted Colour Pallet").~~


~~I will explain the uses of the varius colours below, starting from top to bottom.~~


![Colour Pallet](wireframes/new-colour-pallet.JPG)
 
 * #fbfbfb - main background colour
 * #fff - navigation bar colour
 * #3d8bca - input buttons color
 * ~~#92579F - This colour will be used as a backgroung behind any images used.~~
 * ~~#121A18 - This colour will be used as a text colour also the navigation and footer background colour.~~

### Structure
Website is mobile first with min-size of iPhone 5/SE (320px)for styling purposes. The screen size breakpoints that I will be using are from [Bootstrap breakpoints](https://getbootstrap.com/docs/5.0/layout/breakpoints/ "Bootstrap").

| Screen Size | Breakpoint |
| ----------- | ---------- |
| x-small     | <576px     |
| small       | => 576px   |
| medium      | => 768px   |
| large       | => 992px   |
| x-large     | => 1200px  |

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Wireframes
I have used [Balsamic](https://balsamiq.com/wireframes/ "Balsamic") to develop my wireframes for my website. I initially created the mobile version and then the wireframes and then scalled it up for both tablet and desktop. Because a requirement is to give little but quality information to the user to make them want to engage with the club, a one-page website is used. This gets the user through the content and quickly to the contact form and details via scrolling or directly via the navigation bar.

The wireframes are below:


### [Desktop Wireframe](wireframes/T4Tri_desktop.png "Desktop wireframe")
### [Tablet Wireframe](wireframes/T4Tri_tablet.png "Tablet wireframe")
### [Phone Wireframe](wireframes/T4Tri_phone.png "Phone wireframe")

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Features

## Existing Features

### Navigation Bar

The navigation bar is fully responsive to allow for various screen sizes. It includes links to manover around the site easily and the club logo which doubles as a link back to the home screen.

+ Desktop (>=992px)
\
&nbsp;
    ![Navigation bar](wireframes/nav-bar-desktop.JPG)
    -   Spanning the full width of the device and with all links (Home, About, Events, Contact) to navigate visible, this gives ease and clear use to the end user.

    -   In order for the user to visably see which of the links they are hovering over there is a bar below the text.

    ![Navigation bar on hover](wireframes/nav-bar-hover.JPG)
    \
    &nbsp;
    -   For the user to know that a link has been clicked there is also a visual aid of the text changing colour.

    ![Navigation bar on focus](wireframes/nav-bar-focus.JPG)
    \
    &nbsp;


+ Small devices (<992px)
\
&nbsp;
    - As the navigation bar would be unuseable in the desktop version on smaller devices, it takes on a hamburger style.

    \
    &nbsp;
![Nav bar on small devices](wireframes/nav-bar-small.JPG)

    - When pressed, it opens up the main menu with all the links available then.

    \
    &nbsp;
![Nav bar on small devices expanded](wireframes/nav-bar-small-expanded.JPG)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;
### Landing Page

+ The landing page image
    - The image gives the user instant knowledge of what is involved in the club, and with added animation draws their eye to the site.
    - The text gives instant information to the user on what the club is. With the added animation of fading in slightly behind the image, it makes the user keep interest. 
    \
    &nbsp;

    ![Landing Page](wireframes/landing-page.JPG)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;


### Welcome Section

+ The welcome section gives a brief introduction to the user on what T4Tri is and who is welcome.
    \
    &nbsp;

    ![Welcome Section](wireframes/welcome.JPG)
    \
    &nbsp;

+ To speed up user interation, there is a *'Join Us'* button that directly links to the contact form. This button has a hover effect on it in the form of an animation to allow the user to know that it is something to be pressed.
    \
    &nbsp;

    ![Welcome Button](wireframes/welcome-button.JPG)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

### About Section

+ The about section gives a brief, and attemped humerous, description of the diceplins of triathlon with the adition of a character showing the user what is involved, even if they do not want to read the descriptions. It is also responsive to suit the different screen sizes.
    \
    &nbsp;

    *Desktop*

    ![About Section on Desktop](wireframes/about.JPG)
    \
    &nbsp;


    *Laptop*
    
    ![About Section on Tablet](wireframes/about-laptop.JPG)
    \
    &nbsp;

    
    *Phone and Tablet*
    
    ![About Section on Phone](wireframes/about-phone.JPG)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

### Events Section

+ This is where the most upcoming club events are shown. It includes an icon to quickly show if it is a social or a race event to the user. Also, on the larger screen sizes it includes some images to break up the screen.
    \
    &nbsp;

    *Large device*

    ![Events Section on Large Display](wireframes/events-large-device.JPG)
    \
    &nbsp;

    *Small device*

    ![Events Section on Small Display](wireframes/events-small-device.JPG)

    \
    &nbsp;
+ The date and location are also shown with the added function of a link to the directions of the event via Google Maps. There is also a label added, and animation for extra information to the user that it is a link to follow.
    \
    &nbsp;

    ![Events Section Directions](wireframes/events-directions.JPG)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

### Contact Section

+ The contact section allows the user to quickly send a message to the T4Tri club. it also has a map of the location of the club base.
    \
    &nbsp;

    ![Contact Section](wireframes/contact.JPG)
    \
    &nbsp;

+ The text fields are all required fields and will not alow the user to submit until they are completed, this includes a validation on the email to ensure it is in a valid format. There is also a hover effect on the submit button to give the user feedback that it is and active button.
    \
    &nbsp;

    ![Contact Section](wireframes/contact-email.JPG)
    \
    &nbsp;

+ On submission of the form, the user is bought to a page showing that their details were received.
    \
    &nbsp;

    ![Contact Section](wireframes/contact-received.JPG)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

### Footer

+ The footer contains the social media links related to T4Tri and the copyright text. These social links all open in a new tab for ease of use to the user and also, so the user has an ability to easily come back to T4Tri's site.
    \
    &nbsp;

    ![Contact Section](wireframes/footer.JPG)
    \
    &nbsp;

+ There is also a hover effect over the links, again to improve user experiance.
    \
    &nbsp;

    ![Contact Section](wireframes/footer-hover.JPG)
    \
    &nbsp;

## Features to be Implemented

+ Contact form to send message to T4Tri instead of leading to a dummy page.
+ Links to club sponsors websites.
+ Add a shop for club clothing to be purchased.
+ Add a library of structured workouts for all activities.

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Technologies used

## Languages
* [HTML](https://en.wikipedia.org/wiki/HTML "HTML")
* [CSS](https://en.wikipedia.org/wiki/CSS "CSS")

## Libraries & Framework
* [Google Fonts](https://fonts.google.com/ "Google Fonts")
* [Font Awesome library](https://fontawesome.com/ "Font Awesome")
## Tools
* [Gitpod](https://www.gitpod.io/ "Gitpod")
* [Github](https://www.github.com/ "Github")
* [Balsamic](https://balsamiq.com/wireframes/ "Balsamic") ****
* [W3C HTML Validation Service](https://validator.w3.org/ "W3C HTML")
* [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/ "W3C CSS")
* [Bootstrap](https://getbootstrap.com "Bootstrap") ****

* [Colourmind](https://colormind.io/ "colourmind") ****

* [Font Awesome library](https://fontawesome.com/ "Font Awesome")
* [Google Fonts](https://fonts.google.com/ "Google Fonts")
* [Unsplash](https://unsplash.com/ "Unsplash") ****
* [Box Shadow Generator](https://html-css-js.com/css/generator/box-shadow/ "html-css-js.com") ****
* [TinyPNG](https://tinypng.com/ "TinyPNG")
* [Photoshop](https://www.adobe.com/ie/products/photoshop.html "Adobe Photoshop")

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Testing

I feel that the site has hit the goals required by all parties. The site responds nicely to all different screen sizes, the images look clean and sharp on all device sizes with very little, large blank spaces. It allows the user to navigate around easily and aslo make contact via the contact form or social media simply. It The content is simple and to the point and the site is not overcrowded as to put the user off.
\
&nbsp;

I have encountered several issues during testing. 
 + I initially decided to create the site with a minimum width of 992px as my largest styling, however the site just did not look right so added an x-large screen size.

 + In my wireframes, I had designed to only have a 'Join Us' button on the larger screen sizes. While I was developing the site, this did not make sence. There was such a long scroll with it being a one-page site, I felt I needed to speed up the movement for someone who was instantly interested so included it on all screen sizes.

 + On actual smaller devices, instead of on Chrome Developer, the main navigation menu did not show the 'Contact' link. I simply changed the styling of the links and the changed the ul to flex-start and all is now clearly visable.

 + I was having issues with the navigation bar scrolling about 15px when I scrolled down on smaller devices whilst working on Chrome Developer. I lost a lot of time trying to figure out the issue, but when I tried the site on an acual device, the navigation bar stayed fixed as the code dictated. This was a bug in Chrome Developer and not with my site.

 + The main navigation on smaller devices was initially set to 90vh, however on testing on a physical device, the user could see the site scrolling at the bottom if they were to slide up or down. This looked very poor and clumsy on the eye, so I adjusted it to 100vh to cover it up.

 + I found that I was repeating alot of code in my style.css file in order to center items. I created a class to do this and then applied it whee needed.

 + All my buttons were styled completly differently. I added an animation to all buttons so there is a continuity between them all.

 + When I was validating HTML code, I had one error showing. This was in the contact form where I had a method of '#'. I was under the understanding that POST method should have been used, but when I did, it caused an error instead of going to my contact.html page. After a while I tried using GET and it worked solving my validation problem. The results of my validation for HTML and CSS are below.

    - HTML (index.html) validator [results](wireframes/html-validate.JPG "W3C HTML")
    - HTML (contact.html) validator [results](wireframes/html-contact-validate.JPG "W3C HTML")
    - CSS validator [results](wireframes/css-validate.JPG "W3C CSS")
\
&nbsp;

 + On testing on a physical mobile device, I thought that the google search bar looked odd, being white and my header a dark colour. For user experiance and to make it look cleaner and more fluid, I changed the colour to match using the following code.

 ```

 <meta name="theme-color" content="#121A18">


 ```

 + When going through my UX section, to ensure that all my goals were met for the project, I noticed that I had missed one, 'As a user, I want to know that the club is well established'. I adjusted the text in the welcome section to suit.
\
&nbsp;

## Unfixed Bugs

My learning has limited my use of the hamburger for smaller devices. It works nicely to open the menu up, but a tap of the hamburger again should close the menu down again. It does not do this, and the link has to be selected to enable the user to exit out of it. From my research it seems that all the streamline methods are using JavaScript and I am yet to learn this.


\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Deployment

Following writing the code then commiting and pushing to GitHub, this project was deployed using GitHub by the following steps.

+ Navigate to the repository on github and click 'Settings'.
+ Then select 'Pages' on the side navigation.
+ Select the 'None' dropdown, and then click 'master'.
+ Click on the 'Save' button.
+ Now the website is now live on https://sam-timmins.github.io/T4Tri-triathlon-club/
+ If any changes are required, they can be done, commited and pushed to GitHub and the changes will be updated.

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Credits

For code insperation, help and advice,
* [Simen Daehlin](https://github.com/Eventyret "Simen Daehlin")



* [Mark Caron](https://medium.com/@heyoka/responsive-pure-css-off-canvas-hamburger-menu-aebc8d11d793 "Marc Caron")
\
&nbsp;

For readme template and structure,
* [Sam Timmins](https://github.com/sam-timmins/T4Tri-triathlon-club)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

