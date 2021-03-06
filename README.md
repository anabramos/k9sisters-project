# K9 Sisters

## About K9 Sisters
K9 Sisters is a website for dog sitting services in Amsterdam-West. It is my first project as part of the Diploma in Software Development at Code Institute.

The K9 Sisters project is a user centric (static) Front-End Development website for dog sitting services in Amsterdam-West and surroundings. It is targeted at dog owners who live and/or work in Amsterdam-West and who make use of dog sitting services regularly or sporadically. 

Link to live website: [K9 Sisters](https://anabramos.github.io/k9sisters-project/)

<img src="assets/design/am-i-responsive/am-i-responsive.png" style="width: 60%" />

## Table of Contents
- [Features](#features)
    * [Features to be Implemented](#features-to-be-implemented)
- [Testing](#testing)
    * [Component level Testing](#component-level-testing)
    * [User level Testing](#user-level-testing)
    * [Bugs](#bugs)
    * [Validator Testing](#validator-testing)
    * [Accessibility](#accessibility)
- [Deployment](#deployment)
- [User Experience (UX)](#user-experience-ux)
- [Design](#design)
- [Technologies Used](#technologies-used)
- [Credits](#credits)
- [Acknowledgements](#acknowledgements)

<a name="features"></a>

## Features

- Navigation Bar
    - The navigation bar is situated at the top of the page, with the logo of the K9 Sisters to the left and the menu to the right. The menu brings the visitor to the 4 main pages of the website: Home, Services, Booking, and Blog. 
    - An orange underline appears static under the menu page refering to where in the website the visitor is current in. This gives clarity of the navigation. A thicker orange underline appears when the mouse hovers on the other pages that are currently not opened (active).
    - The K9 Sisters logo also functions as an anchor link to the homepage.

        <img src="assets/design/features/navigation-bar.png" style="width: 60%" style="height: 100px">

- Hero Image & cover text
    - The hero image brings a very clear picture of the focus of the website together with its cover text. Here a visitor immediately knows what is the k9 Sisters company and what they will be able to find in this website.
    - A short animation is present in the cover text to call the attention of the visitor to the message on the text.
    - For the mobile version, in the cover text we see only the name of the company not to echo with the hero image.

        <img src="assets/design/features/hero-image-feature.png" style="width: 60%">

- About Us section
    - The about us section presents to the visitor the people behind K9 Sisters in a nice and funny way as well as the mission of the company. The text is accompanied by an old image of the two sisters who started out the K9 Sisters.
    - At the end of the 'About Us' section, visitors are invited through a link to book a free meet and greet with the K9 Sisters.

        <img src="assets/design/features/about-us-feature.png" style="width: 60%">

- What we offer section
    - In this section the visitor is offered a small teaser of some of the services offered by the K9 Sisters. 
    - The link under the three examples invites the visitor to check the overview of all services provided. 

        <img src="assets/design/features/what-we-offer-section.png" style="width: 60%">

- Testimonials section
    - Here the visitor can read testimonials of existing clients (dogs and humans) that support and validate the brand.
    - This gives the visitor more reassurance that the business is trustworthy. 

        <img src="assets/design/features/testimonials-section.png" style="width: 60%">

- Newsletter section
    - The newsletter section has an e-mail input field to collect subscriptions to the newsletter. 
    - The newsletter subscription gives the visitor access to unique content including discounts on the services.
    - When submitting a newsletter, the visitor is directed to a confirmation page.

        <img src="assets/design/features/newsletter-section.png" style="width: 60%">

- Newsletter confirmation section
    - The user receives a confirmation message that his subscription has been received. 
    - A button is also offering the user to return to the homepage.

        <img src="assets/design/features/newsletter-confirmation-section.png" style="width: 40%">

- Contact Us section
    - The contact us section provides information on how one can get in contact with the K9 SIsters via: telephone, e-mail and address. 
    - It also provides with an iframe map of the location where the business is located for reference and facilitating the visualization of the address in Amsterdam West.

        <img src="assets/design/features/contact-us-section.png" style="width: 60%">

- Footer
    - The footer will re-direct the user to our respective social media by opening the external pages in a new tab on the browser. 
    - The footer also credits the creator of the website. 

        <img src="assets/design/features/footer.png" style="width: 60%">

- Services page
    - In the services page visitors can access the full overview of services provided by the K9 Sister company.
    - The overview includes the prices per service and duration of each service. 
    - Icons are added to this page to give a better illustration of the sort or service that is being offered.

        <img src="assets/design/features/services-overview.png" style="width: 40%">

- Booking page
    - In the booking page there is a form for users to book their services as preferred.
    - The form collects data related to the owner (contact details) the dog (general details) and the service the costumer is booking (type of service, date of service and payment method of choice).
    - After filling in the form, the costumer can submit the form or clear (reset) its content.
    - When a form is submitted, the visitor is directed to a confirmation page.

        <img src="assets/design/features/booking-form.png" style="width: 30%">

- Booking confirmation
    - The user receives a confirmation message that his booking has been confirmed. 
    - A button is also offering the user to return to the homepage.

        <img src="assets/design/features/booking-confirmation.png" style="width: 40%">

- Blog page
    - In the blog page visitors can have access to a range of dog related content, created by the K9 Sisters. 
    - By scrolling down the visitor can see all published blog posts and click on 'continue reading' to open the entire article on a new page. 

        <img src="assets/design/features/blog-page.png" style="width: 40%">

- Full Article page
    - The visitor ca read the full article content in this page.

        <img src="assets/design/features/blog-full.png" style="width: 50%">

<a name="features-to-be-implemented"></a>

### Features to be implemented

- Implement carrousel gallery of testimonials from clients in the homepage.
- In the booking form give the possibility for users to add extra dogs to the bookings (for those who have more than one dog).
- Have a personalized booking confirmation page using the data inputted into the form (i.e. naming the dog's name and time of pick-up). 
- Payment processing feature.
- Create account/log-in features for regular clients.
- 

<a name="testing"></a>

## Testing

<a name="component-level-testing"></a>

### Component level Testing

- Compatibility & Responsiveness
    - The website was tested and it is working on different browsers: Google Chrome, Firefox, and Microsoft Edge.
    - Tested on different devices using Chrome DevTools and other available from myself and friends. 
    - The website is responsive on screen widths from 2560px to 320px.

- Navigation bar
    - All internal links within all pages from the navigation bar are working and opening the correct desired page.

- Newsletter subscription
    - The subscription form for the newsletter is working and redirecting users to the confirmation page.
    - The e-mail input filed is required, which means it won't accept any subscriptions with empty data.
    - The e-mail input field only accepts valid e-mail address with the correct e-mail syntax.

- Booking form
    - The booking form is working and redirecting users to the confirmation page.
    - All input fields are required for the booking except the 'allergies' field since this field might also not apply. If any of the fields is left blank, the user is asked to properly fill in the field.
    - For the mobile number field (input type="tel") I have used a pattern provided by [Martin Wolf](https://martinwolf.org/before-2018/blog/2015/04/html5-telephone-input-validation/) (see credits section of this document) to assure that only valid numbers can be filled in the booking form. 
    - The availability in the calendar was manually set to assure there is no possibility of booking services in the past or last minute. 

- Social media links (footer)
    - All social media links are working and opening on a separate new tab on the browser.
    - In the iframe map when clicked on "View larger maps", the link opens on a separate new tab on the browser.

<a name="user-level-testing"></a>

### User level Testing
Friends of mine tested the website in their own mobiles, laptops, etc. The website was also submitted in the peer-code-review channel on the CI Slack community.  

 - Overall Navigation 
    - No issues reported.

- Website Responsiveness
    - Issue reported with footer spacing on screen widths larger than 1256px. Changes to address this issue were implemented by giving containers and background a minimum height (in viewport height). 
    - Issue reported with font-size being too small on screen sizes with width 1024px to 768px. Changes to address this issue were implemented by giving font-sizes a relative units of measurements. 
    - Issue reported with alignment of iframe map in mobile screens being too close to the left instead of central. Changes to address this issue were implemented by giving the element a specific margin within the respective media query.

- Booking form
    - Issue reported with mobile number field that was accepting non numeral input. Changes to address this issue were implemented by using an existing pattern attribute (see credits section of this document).

- Newsletter subscription
    - No issues reported.

<a name="bugs"></a>

### Bugs
While building the website a lot of things were not working as expected. As I used only HTML5 and CSS, most of the 'bugs' are as a matter of fact just a miss-use of CSS styling. This happened mostly because in the beginning of the process of building the website I was using id attributes and selectors to style my HTML. Half-way through the process I realized the best approach was to create more general CCS style class rules and use those to create the behaviors expected on the HTML documents. These fixes and changes can be seen in my commit messages documentation, initiated by the prefix 'fix:' or 'style: fix'. Some recurrent bugs I encountered were:

- Horizontal scroll present on small screen devices, normally caused by the margin or padding or other elements that create overflow. After identifying which element was creating the overflow I fixed it by changing the value of the left and right margin/padding. 

- Footer with a lot of space beneath it caused by HTML documents with very few content. I solved this by adding a minimum height value (viewport height measurement) to the respective container and background of the page that was presenting this bug. This assures the footer stayed on the bottom of the page.

<a name="validator-testing"></a>

### Validator Testing

- HTML
    - No errors or warnings returned from the [W3C Markup Validator Service](https://validator.w3.org/)

- CSS
    - No errors or warnings returned from the [W3C CSS Validator Service](https://jigsaw.w3.org/css-validator/)

<a name="accessibility"></a>

### Accessibility

- The color pallet and contrast for the website was tested on [WebAIM](https://webaim.org/resources/contrastchecker/)
- The website has been tested on lighthouse for accessibility. 
    - index.html
        
        <img src="assets/design/lighthouse/acessibility-index.png" style="width: 50%">

    - services.html

        <img src="assets/design/lighthouse/acessibility-services.png" style="width: 50%">

    - booking.html

        <img src="assets/design/lighthouse/acessibility-booking.png" style="width: 50%">

    - blog.html

        <img src="assets/design/lighthouse/acessibility-blog.png" style="width: 50%">

    - booking-confirmation.html

        <img src="assets/design/lighthouse/acessibility-confirmation-booking.png" style="width: 50%">

    - newsletter.confirmation.html

        <img src="assets/design/lighthouse/acessibility-confirmation-newsletter.png" style="width: 50%">

    - blog-post-1.html/ blog-post-2.html/ blog-post-3.html/ blog-post-4.html

        <img src="assets/design/lighthouse/acessibility-full-blog.png" style="width: 50%">

<a name="deployment"></a>

## Deployment

The website was deployed using GitHub Pages. For that, the following steps were taken:
1. From the GitHub repository page go to 'Settings'.
2. From 'Settings', scroll until the 'GitHub Pages' section.
3. At the 'GitHub Pages' section open the dedicated GitHub Pages tab by clicking on the link.
4. In the new tab select the main branch using the dropdown menu and click 'Save'.
5. A link will be provided where the website is now published.

- Forking
    - To use this project as a reference or starting point, or even to propose changes to it, you can fork this repository by following these steps: 
        1. From the GitHub repository page click on 'Fork' in the top-right corner.
        2. Create a new repository with a new name based on this project. 
        3. Make sure to credit the project in case you decide to use any of the original code.

<a name="user-experience-ux"></a>

## User Experience (UX)
The user experience for the website is built with 3 personas in mind. Each persona presents a different user story and different goals when accessing the website. 

- Personas 
    - Persona 1: Frequent costumer.
    - Persona 2: Sporadic costumer.
    - Persona 3: Potential costumer (first time visitor).

- User stories

    - A Frequent consumer:
        - I already know the brand and make use of their services on a regular basis.
        - I trust and vouch that their service is of quality.
        - I want to be directed to the booking form quickly (Solution: Direct link to booking form on navigation bar).
        - I want to receive tips and updates related to their blog and potential holiday discounts (Solution: Possibility to subscribe to the newsletter).

    - A Sporadic consumer:
        - I already know the brand and make use of their services sporadically.
        - I trust their service is of quality.
        - I want to check the prices of the services easily as I may have forgotten it since my last booking (Solution: Direct link to services overview on navigation bar).
        - While in the website, I might be interested in reading their latest article piece with tips on how to care for my pup (Solution: Direct link to blog on navigation bar).

    - A Potential consumer:
        - I am a first time visitor to the website. I do not know the brand and have never used their services.
        - I do not trust the brand (yet) and would like to be convinced they are trustworthy (Solution: Testimonials from clients avaliable on the homepage).
        - I want to have a clear overview of the services provided (Solution: Direct link to services overview on navigation bar).
        - I want to be able to meet the people who will take care of my dog before making a decision (Solution: Option to book a free meet & greet session).
        - I want to have a financial incentive to committing with my first booking (Solution: Discount on the first booking if you sign the newsletter).

- K9 Company goals with the website:
    - Attract more customers.
    - Generate returning costumers.
    - Demonstrate professionalism, competence and qualification in the services provided.
    - Get potential customers to sign to our newsletter and book a meet & greet session.

<a name="design"></a>

## Design

- Colors
    - The website colors are inspired by the complimentary colors of orange and blue. It uses different shades of blue to create contrast between text and background, and the orange is used to reinforce borders and highlight certain features/sections in the website.

        <img src="assets/design/color-palette/mycolors.jpg" style="width: 60%" style="height: 120px">

- Fonts
    - The website uses a combination of Bebas Neue & Montserra fonts, with a fall back to sans-serif. These fonts are popularly paired together. Bebas Neue is used in the website for high-level headings while Montserra is used for regular text and low level headings. The fonts were compared and taken from [Google Fonts](https://fonts.google.com/).

- Icons
    - This website makes use of icons from [Font Awesome](https://fontawesome.com/) to give a new visual element and reinforce the content already displayed. The Icons are used to indicate social media links on the website's footer and make a distinction in the types of activities/services provided by the K9 Sisters.

- Images
    - All images for this project were taken from [Unsplash](https://unsplash.com/). For further details on each image, please see the credits section of this README document. 

- Wireframes 
    - I have used [Moqups](https://moqups.com/) to draft my wireframes. These can be found in their respective folder 'wireframes' under the project's assets folder.

<a name="techlonogies-used"></a>

## Technologies Used

- Languages
    - [HTML5](https://en.wikipedia.org/wiki/HTML)
    - [CSS](https://en.wikipedia.org/wiki/CSS)

- Libraries & Frameworks
    - [Google Fonts](https://fonts.google.com/)
    - [Font Awesome](https://fontawesome.com/)

- Tools
    - [Gitpod](https://www.gitpod.io/)
    - [Github](https://github.com/)
    - [Google Chrome Developer Tools](https://developer.chrome.com/docs/devtools/)
    - [Moqups](https://moqups.com/)
    - [Coolors (color schemes generator)](https://coolors.co/)
    - [Unsplash](https://unsplash.com/)
    - [W3C HTML Validation Service](https://validator.w3.org/)
    - [W3C CSS Validation Service](https://validator.w3.org/)
    - [Am I Responsive?](http://ami.responsivedesign.is/)
    - [WebAIM](https://webaim.org/resources/contrastchecker/)

<a name="credits"></a>

 ## Credits

- Content
 
    - For the booking form input field type "tel" I have used the pattern attribute value provided by [Martin Wolf](https://martinwolf.org/before-2018/blog/2015/04/html5-telephone-input-validation/) 2015. This assured that only numeric numbers in a certain pattern could be inputted into the form.  
    
    - All other code was written by myself: Ana Ramos Barretto.

- Media

    - All images for this website were taken from [Unsplash](https://unsplash.com/).

        - index.html

            - Hero-image: Photo by [Anna Dudkova](https://unsplash.com/@annadudkova) 

            - Two young girls holding a dog: Photo by [Leah Hetteberg](https://unsplash.com/@leahhetteberg) 

            - Four dogs on a leash in a park: Photo by [Matt Nelson](https://unsplash.com/@mnelson) 

            - Brown short coated sog lying on a grey dog bed under a blanket: Photo by [Jaime Street](https://unsplash.com/@jamie452) 

            - Border Collie jumping through a yellow training hoop: Photo by [Andrea Lightfoot](https://unsplash.com/@andreaelphotography)

            - Dog wearing a shirt and a hat: Photo by [Charles Deluvio](https://unsplash.com/@charlesdeluvio) 

            - Hairy dog kissing woman in black shirt: Photo by [Tamas Pap](https://unsplash.com/@tamasp) 

            - Long-coated brown dog wearing sun glasses: Photo by [Alan King](https://unsplash.com/@alanking) 

        - booking-confrimation.html

            - Brown and white pomeranian working on an iPad: Photo by [Cookie de Pom](https://unsplash.com/@cookiethepom) 

        - newsletter-confirmation.html

            - Brown and white long haired dog sitting on a desk with 2 screens: Photo by [Pavel Herceg](https://unsplash.com/@pavelherceg)

        - blog.html

            - Brown labrador retriever drinking water from a fountain: Photo by [Rafael Ishkhanyan](https://unsplash.com/@rafael_ishkhanyan)

            - Brown long coated dog drying paws on blue towel: Photo by [Jaime Street](https://unsplash.com/@jamie452) 

            - Woman gives biscuits to two seated dogs: Photo by [Chewy](https://unsplash.com/@chewy)

            - Dog treats on wooden table: Photo by [Susan Q Yin](https://unsplash.com/@syinq)

<a name="acknowledgements"></a>

## Acknowledgements

A huge thanks to my mentor Samantha Dartnall, the CI slack community and tutoring team, the Proud Unicorns hackathon team, and my friends who tested the website at least 1000x. 