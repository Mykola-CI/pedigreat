# Pedigreat
Pedigreat is a fictional brand name, which occurred to me when I was contemplating on the project. Googling this brandname gives no exact matches save one in Nigeria that is related to construction development. 

In this project the Pedigreat is an imaginary small-scale business solution in canine and pet-sitting service sector. It teams up experienced dog-lovers who have turned their passion for dogs into a career.    
In order to facilitate boarding part of the business the Pedigreat develops a net of local house owners willing to provide a second-home boarding for Pedigreat clients. The business is based in Berkshire, UK, known for its exceptional walking paths, pet-dedicated playgrounds and amazing meadows. 

In contrast to the existing Uber-like large nets of amateur pet-sitters or big companies blanketing vast territories, Pedigreat position themselves as serving Berkshire communities only, targeting local pet owners. Pedigreat challenges to exercise individual approach policy equipped with in-depth knowledge of local landscapes, resources and lifestyles. Pedigreat personnel stress that they don't sell hours, they rather sell emotions and passion for their furry clientele. 

To facilitate the main business objectives the Pedigreat team has launched a front-end web-site as a first stage of its further development.   
The site can be accessed at the following link  [Pedigreat Web-Site](https://mykola-ci.github.io/pedigreat/index.html)

![Pedigreat Responsive Web-Mockup](documentation/screenshots/3-devices-black-resized.png "The image of mobile, tablet and desktop with the Web-site Mockup on screens")

--------
## User Stories
### First-time Users:
* _As a first-time user_, I want to easily understand the services offered by the pet-sitting website so that I can decide if it meets my needs.
* _As a first-time user_, I want to see testimonials from other pet owners who have used the pet-sitting service so that I can trust the quality of the service.
### Returning Users:
* _As a returning user_, I want to quickly access my account and view my pet-sitting bookings so that I can manage my reservations.
* _As a returning user_, I want to receive notifications about upcoming pet-sitting appointments so that I can prepare my pet and coordinate with the pet sitter.
### Frequent Users:
* _As a frequent user_, I want to earn rewards or discounts for using the pet-sitting service regularly so that I feel valued as a loyal customer.
* _As a frequent user_, I want to have a personalized experience on the website, such as seeing my favorite pet sitters or tailored service recommendations, so that I can quickly find and book the services I need.
### As a Pet Owner In General
* _As a pet owner_, I want to be able to easily find and book a pet sitter so that my pet is cared for when I am away.
* _As a pet owner_, I want to be able to read reviews about pet sitters so that I can choose a sitter I trust.
* _As a pet owner_, I want to be able to communicate with the pet sitter about my pet's needs so they are properly cared for.
* _As a pet owner_, I want to be able to pay conveniently and securely so I don't have to worry about payments.
_________
### Comments On User Stories
Technically the web-site is supposed to employ html & css tools only at the first stage of its development. The business model is adjusted to provide its functionality without undertaking complex back-end software that would manage the automation of scheduling, booking, billing, chatbot etc. That is why the business model and eventually its web-site assumes, at least for now, human-to-human contacts only when making appointments and booking services.

Yet the registration form will appear on one of the pages because Pedigreat offers promotions and cross-promotions, as well as email newsletters for the registered clients. Many of users' wants can be met in the newsletter communication and a relevant event marketing.

## Global functionality and navigation
The first user's hit will be the landing page and the banner. It is equipped with 
* Header with logo and navigation bar 
* Main Slogan followed by the button "Book Now" and the Themed Banner at the Background  

See the site navigation scheme in pdf: [Site Navigation Scheme](documentation/navigation-pedigreat.pdf)

![Navigation Scheme Screen](documentation/navigation-scheme-screen.png "Navigation Scheme Screen")

Navigation is provided by the following buttons within the navigation bar:
* Home (Landing Page)
* Gallery (Photo gallery)
* Services (description of Services and price cards)
* Contacts: 
    - Contact details for booking and any communication 
    - Invitation to join Community and Loyalty program

The 'Home' Page contains a button-link to the 'Contacts' Page.

   ![Book Now button under the Slogan](documentation/book-now-button.png)

'Home' Page also contains Learn More Links that lead to the Services Page

   ![Learn More link visual](documentation/learn-more-presentation.png)

The 'Contacts' Page contains the Invitation to fill out the Form and a Button encouraging to jump to the "Customer Registration Form".

   ![Invitation to Register Button](documentation/invitation-to-register.png)


Once the Form has been submitted User will get into the 'Response' Page as shown in the Site Mapping diagram above.

## Existing Features
The page is divided onto 3 global sections: Header, Main and Footer.   
The Main section of the Front page is divided onto 4 sections: Banner section, About Us, Services and Testimonials

### Header and Navigation Bar
The header takes a fixed position at the top of the screen.  
The header contains a clickable Logo Pedigreat, which leads User to the home page. The only hover effect for logo is a cursor-pointer transformation with no focus features. The header also takes on-board the navigation menu realized in 2 basic forms: for small and for larger screens above 765px.

The following visual is a presentation of how header looks on tablet-size screens. There are buttons for the menu items which change the lighting pattern on focus. 

![Header and Navigation Bar for larger screens](documentation/nav-bar-tablets.png)

The 'focus' effect in the form of animated lighting pattern delivered by means of css shadow effects:

* ![Presentation of focus effect on menu buttons](documentation/buttons-navbar-focus.gif)

The following visual is a presentation of how header looks on mobile-size screens. There is a conventional Burger Icon. 

* ![Header and Nav-bar with burger icon for smaller screens](documentation/nav-bar-burger-icon.png)

With the drop-down menu:

* ![Header and Navigation Bar drop-down menu for smaller screens](documentation/nav-bar-drop-down.png)

Where 2 basic effects were adopted for the site: 
- rotation of the burger icon 90º on touch
- drop-down menu transition 1sec ease-in-out

* ![Presentation of rotating burger icon](documentation/rotating-burger-icon.gif)

### Banner Section on the front page
The Banner on the front Page is arranged as a '::before' pseudo-class element in order to gain control over the background image opacity and filters without affecting the properties of the text contents.   

```
  .banner-landing::before {
  content: "";
  background: url() no-repeat center center/cover;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: -1;
  filter: blur(2px) opacity(100%);
}
```
At the same time the text slogan has the background of its own to provide for the required contrast, its opacity helping retain consistency throughout the major banner 

  ![Front Page banner - mobile and laptop views](documentation/banner-mobile-tablet-views.png)

The banner itself takes about 75% of the viewport height just enough to reveal a part of the next section - About Us.

### About Us and Services sections on the front page
About Us section tells User a few words about the Pedigreat team and its dedication, which is followed by the brief descriptions of 4 distinct types of services in offer.
* The About Us block consists of h3 heading, 2 text blocks and the image of collage portraits photos.
* The Service Descriptions block consists of 4 text cards with elegant curvy borders and smooth shadowing.
Both sections as well as the following Testimonials section are made coherent with the small left and right margins. Technically, this is attained by means of width 95% of their parent, max-width 400px (for responsive design at larger widths) and flex-centered layout.  

  ![About Us - Mobile view](documentation/mobile-about-us.png) ![Service Descriptions - Mobile view](documentation/mobile-service-intro.png)

### Testimonials section on the front page
This section is featured with 2 testimonials, which organized 
* as 2 cards with the photo of a pet-owner, name, occupation and the story
* each placed in a container with a thin border and smooth shadowing
* images are placed at the top left with the properties 
  - float: left and 
  - width: min(20%, 100px) 

  ![Testimonials combined with Service cards - Tablet view](documentation/testimonials-section-tablet.png)

### Footer
Footer is the global element which is repeated across all the pages in the similar manner as Header.
Unlike Header its position is not fixed, it is pushed down by flex-property of the Main section: flex: 1 0 auto;.

The Footer contains:
* Address block
* 4 Social media icons, which change color on focus

![Footer Tablet View](documentation/footer-tablet-view.png)

![Footer Tablet View](documentation/footer-mobile-view.png)

The social media icons change color on hover:

![Hover effect on media icons](documentation/media-icons-hover.gif)

### Secondary banner and the other pages layout
Gallery, Services and Contacts pages have a common layout scheme, which differs from that of the front page. While the front page is dominated by the primary banner and the slogan, the other pages feature:
* secondary banner that takes up about 25% of the viewport height (25vh) and has a fixed property to remain still when content is scrolling

```width: 100%;  
  height: 25vh;  
  position: relative;  
  z-index: 1;
  background-image: url();
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  filter: brightness(50%) hue-rotate(-20deg);
  ```


* the content block/container that is shifted up by 15vh partly overlapping the secondary banner
  - the shift is performed by means of transform property ``transform: translateY(-15vh)``
* the width of the content container is set to 90%  

![Secondary Banner Showcase Gallery Page](documentation/secondary-banner-gallery-showcase.gif)
![Secondary Banner Showcase Services Page](documentation/secondary-banner-services-showcase.gif)

### Gallery Page

This common element in almost every site is organized in simple and nice masonry style. Live and dynamic view without gaps and borders gives a touch of reality.  
Photos are laid out with a 'column' property.
* default one column for mobiles
* column-count: 2 for the screens larger than 765px
* column-count: 3 for the screens larger than 1020px

The screens with 2 or 3 columns are featured with the additional yellow background from the adopted color scheme. This feature is applied in order to rectify suspended and unfinished graphics of the bottom part of the masonry.

![Gallery Bottom background pattern](documentation/gallery-bottom-background.png)

### Services Page

Besides Secondary Banner the Services page contains
* 4 price cards with short and explicit description of the service
* Notes to User about Pedigreat personnel and trainers

Features include:
* Icons inside the price cards - with clip-path feature

~~~
/* Shape services icons */
.services--cards--content img {
  width: clamp(60px, 30%, 80px);
  clip-path: polygon(0% 0%, 75% 0%, 100% 50%, 75% 100%, 0% 100%);
}

.clip-path-shadow {
  filter: drop-shadow(0px 2px 5px var(--COLOR-4));
  text-align: center;
}
~~~

![Price cards and icons](documentation/price-cards-services.png)

* Standard bullets replaced by Puppy-Dog-face icons for the unordered lists of the Notes section 

~~~
.ul-special-style {
  list-style: none;
  padding: 0;
  margin: 0;
  text-align: left;
}

.ul-special-style li {
  padding-top: 0.3rem;
  text-indent: -1rem;
}

.ul-special-style li::before {
  content: "🐶 ";
  padding-left: max(0.8rem, 4vw);
}

.ul-special-style span {
  position: relative;
  left: 0.8rem
}
~~~

![Notes about personnel](documentation/notes-personnel-bullets.png)


### Contacts Page

The Contacts Page contains 2 sections:
* Contact details which are not automated at this stage of development and include invitation to
  - dial a phone number, 
  - send message to email, 
  - text in WhatsApp.

* Invitation card encouraging Users to become a privileged customer
  - benefits are compiled in an unordered list with puppy-dog bullets 
  - the card is equipped with the button link to the Customer Registration Form

The Invitation card features an 'inset shadow' ``box-shadow: inset 0px 0px 13px 12px rgba(0, 0, 0, 0.1);``

![Invitation to become privileged customer](documentation/invitation-to-register-card.png)

### Customer Registration Form

This page is accessible if User opts to become a privileged customer and hits the 'Go On Register Now' button on the Contacts page.
User is encouraged than to fill out the form

![Registration Form](documentation/registration-page-pedigreat.png)

This form features a focus-within property that results in changing font size and color of the input label.

~~~
.customer-registration--block>div:focus-within label {
  color: rgb(51, 51, 160);
  font-size: 150%;
}
~~~

![Registration Form Focus effect](documentation/registration-form-focus.png)




  





