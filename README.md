# DoggyWoggy

"Welcome to [DoggyWoggy](https://captain89.github.io/PortfolioProject1/) The meet and greet website for owners to take their furry best pals on a fun and friendly walk with others and there dogs too!" 

The website is targeted at dog owners who want to join in social walks with others and their dogs, instead of taking their pets on a walk alone. The site is designed to encourage users to see the different walks that we currently offer, and book or enquire with us about our services in relation to dog walking as a group.

![Responsive screenshot](assets/docs/screenshots/responsive.PNG)

# Features

## Current Features

* Navigation Bar:

    The fully responsive navigation bar includes the main logo which links back to the main website page itself, and also three other menu links: About us, Join in, and Contact. The links are highlighted bold with css animation when hovered over, and each link will take the user to the associated area of the site.

![Navigation bar screenshot](assets/docs/screenshots/navbar.PNG)


* The landing page image:

    The main landing page features an image of our beach walk, with some text overlay over the image to provide a useful 'hint' or 'nod' as to what the aim of the site is about.

![Landing page screenshot](assets/docs/screenshots/landingpage.PNG)

* About Us Section:

    The about us section is the main body of text for the website, housed in an eye catching, easy to read container that helps explain who we are, and what we do. Also inside the text section are two links, one to the 'Join in' section, and the other to the 'Contact' section. The site user is encouraged to read the about us content, as it is short and to the point, providing the user with an instant understanding of what services the site aims to provide, and to book a walk using the contact section below.

![About us screenshot](assets/docs/screenshots/aboutus.PNG)

* Join In Section:

    This section allows the site user to clearly see the three walks we have currently available, the beach walk, the woodland walk, and the city walk.

    The walks are explained through visual 'cards' containing images to a likeness of our walks as an example, and the images used are from the free image site [Pexels.com](https://www.pexels.com/).


    The Cards also contain useful information, such as the area of the intended walk, the day the walk is available on, and the time it is held unto. The site user is again encouraged to read this information as it is displayed in a contrasting, off-set color block that draws the users attention, meeting natural eye co-ordination as the eye naturally tends to read from left to right.

    It is noted that inspiration for this style of block, and its opacity layout was used from the Code Institute Love Running walkthrough project, 'Hero Image' section, Third video.

![Join in screenshot](assets/docs/screenshots/join-in.PNG)

* Contact Section:

    This section of the site contains a fully working web-based form, that the user can fill out using their details to book a walk, request information on dog breed safety (some dogs dont always play well with others) and equipment rental, such as leads, collars, whistles/lights, treats and mess-bags etc.

    The form implements use of a drop-down style selector, providing ease of use when selecting a category they wish to enquire further about, or when booking a walk using the site.

    The form also contains validation in the HTML, so the user cant submit an empty form, or any false email address.

![Contact screenshot](assets/docs/screenshots/contact.PNG)

* Footer Section:

    The website footer section contains three useful social media website links, Facebook, Instagram and Twitter. These are external working links, and when clicked will take the site user to the relevant websites, where it is intended they login to their account (if they have one) and view our social media page associated with that site.

    It is to be noted that the images used for the external site links were taken from [FontAwesome.com](https://fontawesome.com/), also in the bottom left corner of the site sits a copyright infringment logo, inspiration for this was used from the site: https://careerkarma.com/blog/html-copyright-symbol/ however the exact code itself was not copied and pasted.

![Footer screenshot](assets/docs/screenshots/footer.PNG)

* Features left to implement:

    There are no further features left to implement at this time.

# User experience UX / UI

## colors used

* Contrasting black and white, and multi shades of grey were implemented into the design structure of the site. This was to ensure good visibility and accessibility whilst using the site.

## Fonts used

* The main logo, and any headers used, contain the 'Lobster' font. This was a design idea, and not inspired from anything else. The main link to this font from Google Fonts can be found in the Credits section of this readme document.

* The main body of text, including the navbar menu links, about us section, meet up times, and enquiry form, are all 'Roboto' font, again this was a design idea, but advised by Google Fonts as a good contrast due to it working well with the aforementioned 'Lobster' font.


# Testing

Throughout the build process of DoggyWoggy, the site has undergone vigorous testing, using three different browsers: Chrome, Mozilla Firefox and Microsoft Edge, each with there own DevTools implemented into the settings.

These internet browsers were used to scope the stability of the DoggyWoggy website on the intended platform, being that different devices use different web browsers, regularly checking for issues and errors was paramount to the success of the final deployed product.

Browsers that were not checked that will be part of ongoing site maintenance and testing include:

* Safari Browser
* Opera 

The reason for this is to ensure users have a broader scale of ease of access, when using their preferred browser.

Currently, the site looks more visually appealing on devices with screen width between 8" to 15.6" in a widescreen format, 16:9 ratio. If the user however is to only view the site on a mobile platform, (because that might be all they have at the time), the site is displayed very well, due to its responsiveness, but can seem unfinished with the menu navigation bar links not stacking as originally intended. They still display nicely, but in horizontal format rather than vertical beneath the site logo.

Furthermore, the Join in section 'Cards' stack upon each other when the screen width is reduced as intended, but when pushed less than the absolute minimum of 306 pixels wide, the content displays out of bounds and glitches/ errors on screen. The current minimum screen size is recommended at 320 x 568 (iphone 5 dimensions).

## Validator Testing

* HTML
    
    No errors were returned when checking through the official [W3C validator](https://validator.w3.org/) tool.

* CSS

    No errors were found when checking through the offical [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/) tool.

## Site Bugs

During testing and build stages, some minor bugs appeared that took time to resolve. Dev Tools were used to locate and implement a fix, these were:

* Came across bug where font for hero-image overlay text would remain large when testing site dimensions via media query and responsiveness. The fix for this was changing the Rem value to a lower value, so to 1rem, from 1.5rem in the media query css rule. The text was now contained as the screen size gets smaller.

* Originally, the navbar section had a different animation style applied to it, (other than the current basic bold one) where when hovered over, a 0.5 second rule underline would follow the text, from left to right. This feature was removed during the early stages of testing, because it caused width and dimension errors where the navbar could not be re-sized if needed, and also the main logo h1 could not be moved using margin or padding.

## Unfixed Bugs

Currently, there are no major unfixed bugs present in the code. The site operates as intended on multiple platforms.

# Deployment

* The DoggyWoggy site was deployed to GitHub pages. The steps used to deploy the site are below:

    * In the GitHub repository, navigate to the Settings tab.
    * From the source section drop-down menu, select the Master Branch.
    * Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live site link can be found here: https://captain89.github.io/PortfolioProject1/

# Credits

## Content

* The font for the main logo and site section headers were used from [googlefonts](https://fonts.google.com/specimen/Lobster?query=lobster).

* The bottom left corner copyright infringment logo, inspiration was used from: https://careerkarma.com/blog/html-copyright-symbol/ however the exact code itself was not copied and pasted.

## Media

* The main hero image, and three 'card section' images were used from the free image source website, [Pexels.com](https://www.pexels.com/).

* Inspiration for the (Salmon) color block style, and its opacity layout was used from the Code Institute Love Running walkthrough project, 'Hero Image' section, Third video.
This is also commented in the [CSS](/workspace/PortfolioProject1/assets/css/style.css) file itself at the actual location of the working code, line 205.

* The icon images in the footer were used from [FontAwesome.com](https://fontawesome.com/).

## Other Resources

* Currently none used.




