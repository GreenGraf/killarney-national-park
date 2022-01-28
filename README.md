# Killarney National Park

Travel and information website for one of Ireland's most famous destinations.

Take a Look [Here](https://greengraf.github.io/killarney-national-park/)

<br>

![Am I Responsive](assets/screenshots/Screen-Responsivness.JPG)

## Portfolio Project 1

Situated in the south west of the island, Killarney National Park is one of the most biodiverse places in Ireland, and is a popular destination for tourists and locals alike. As well as possessing varied and breathtaking scenery, the park has major historical significance too. Not only was it the first national park in Ireland but it is also home to a beautiful example of Victorian architecture in the form of Muckross House and Gardens, complete with a working traditional farm. 

### Purpose

Because there is so much to see and do in the park, visitors can be overwhelmed choice. The aim of this website is to clearly outline the best areas to visit, the ways in which the park can be traversed, and, through a contact form, act as a way of getting in touch with the park staff should anyone have any questions.

<br> 

## User Experience Design

### Strategy 

## Existing Features

* Navigation Bar

    * The navigation bar is on all three pages. On smaller screens, it collapses into a hamburger menu. This was achieved through pure CSS. The CSS was found on [here](https://dev.to/ljcdev/hamburger-css-no-js-2dfa) and copied. It has been edited to suit the design of this website.
    * The navigation bar has links to the homepage, visit page, and contact page. The logo, KNP, also acts as a homepage button.

![Navbar](assets/screenshots/Main-navbar.JPG)

<br>

* Hero Section
    * The hero section, with its striking image and cover text, is designed to immediately get the attention of the user and briefly describe the function of the website.

<br>

![Hero Section](assets/screenshots/hero-section.JPG)

<br>

* Social Proof
    * The purpose of this section is to instill trust in KNP. Having mainstream brands, who feature and rate KNP highly, makes KNP aspirational and will confirm to the user that it's a reliable and popular location. 
    * Positioning it directly beneath the hero section will quickly negate any hesitation the user might have, and convince them to explore the website further.

![social proof](assets/screenshots/social-proof.JPG)

* Activities Section

    * This section is designed to showcase what you can do in the park with images and text. 

![Activities](assets/screenshots/activities-cards.JPG)   

<br>

* Quote Section
    * The aim of the quote section is to create an emotional response and connection with the user.
    * Having an original voice of a previous visitor gives the site more authenticity.
    * It could make it easier for the user to imagine themselves there.

![Quote](assets/screenshots/social-proof-card.JPG)  

* Footer 
    * The footer section — which is on every page — acts as a consistant area that gives the most important information for getting in touch with the park.
    * This section also has social media icons so users can keep up with all that's going on at the park.

![Footer](assets/screenshots/footer.JPG) 

* Visit Us Section
    * This section describes some of the key attractions at the park.
    * High-quality images suppliment the descriptive text, in order to whet the users appitite for visiting the park. 

![Visit](assets/screenshots/visit-cards.JPG) 

* Contact Page
    * The sole purpose of this page is to allow the user to easilly get in touch with the park.
    * The user will need to enter a first name, email, and message to trigger a positive response from the submit button. The user is not required to enter their second name, but can do so if they choose.

![Contact](assets/screenshots/contact-page.JPG)

### Features Left to Implement 
* Seperate pages for the most significant parts of the park which describes them in further detail.
* Maps of park trails that visitors can take whe they get there. 

## Testing

The website was deployed and tested on the most common screen sizes, down to 320px. As I was testing it, I noticed positioning errors here and there, but the vast majority of them have been fixed. The only areas where there are still issues are on the contact page, where the contents of the contact form appear to be offset to the right of the form. Unfortunately, I didn't have time to fix this but I will attempt to fix it at a later date. Apart from that, the only other responsiveness issue that I came across was the line height spacing in the footer, between the "Email Us" section and the "Call Us" section. This only occurs on the Visit page and the Contact page. It does not occur on the Index page. I'm not sure why this is happening but I didn't have time to figure it out. Again, I will attempt to remedy this at a later date.

Thankfully, after a lot of back and forth, I managed to get the hamburger menu working — styled and positioned appropriately. It also appears at an appropriate break-point, as expected.

### Validator Testing

* HTML
    * No errors occured after auditing every page with the official [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgreengraf.github.io%2Fkillarney-national-park%2Findex.html)
* CSS
    * No errors occured after auditing every page with the official [(Jigsaw) Validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fgreengraf.github.io%2Fkillarney-national-park%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

* Lighthouse — Dev Tools
    * I used Lighthouse to test my sites accessability and it received a very good score on desktop and mobile.
    * I also tested the site with [WAVE](https://wave.webaim.org/) and found some accessibility alerts which I easilly fixed.

![Lighthouse](assets/screenshots/lighthouse.JPG) 

![WAVE](assets/screenshots/wave.JPG)   

## Deployment

* The site was deployed to GitHub pages. The steps to deploy are as follows:
    * In the GitHub repository, navigate to the Settings tab
    * From the source section drop-down menu, select the Master Branch
    * Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

There is a link to the live site at the begining of this README.md but for convienience I'll paste the full link here: https://greengraf.github.io/killarney-national-park/

## Credits

I like to say a massive "Thank You" to my mentor, Ben Kavanagh. He's a fantastic motivator and extremely helpful. Also a big thanks to all the helpful people in the Slack community, especially Dave !

### Content

* The icons used in the footer are from [Font Awesome](https://fontawesome.com/)
* The favicon was generated using [Favicon.io](https://favicon.io/favicon-generator/)
* The hamburger menu was created originally by https://dev.to/ljcdev/hamburger-css-no-js-2dfa
* The navbar styles were helped by this YouTube video: https://www.youtube.com/watch?v=W-nIX17Gg-Q&t=97s&ab_channel=AngelaDelise
* The code for the block quote was taken from here: https://codepen.io/cliftwalker/pen/XJaEXY
* This post on Stack Overflow helped me with responsiveness: https://stackoverflow.com/questions/61150660/how-to-make-image-responsive-in-flexbox-with-set-width
* My inspiration for the footer came from this design: https://www.awwwards.com/inspiration/niarra-travel-footer



