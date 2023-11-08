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

![Presentation of focus effect on menu buttons](documentation/buttons-navbar-focus.gif)

The following visual is a presentation of how header looks on mobile-size screens. There is a conventional Burger Icon. 

![Header and Nav-bar with burger icon for smaller screens](documentation/nav-bar-burger-icon.png)

With the drop-down menu:

![Header and Navigation Bar drop-down menu for smaller screens](documentation/nav-bar-drop-down.png)

Where 2 basic effects were adopted for the site: 
- rotation of the burger icon 90º on touch
- drop-down menu transition 1sec ease-in-out

![Presentation of rotating burger icon](documentation/rotating-burger-icon.gif)

### Banner Section on the front page
The Banner on the front Page is arranged as a '::before' pseudo-class in order to gain control over the background image opacity and filters without affecting the properties of the texts. At the same time the text slogan has the background of its own to provide for the required contrast. And it has opacity of its own which helps retain consistency throughout the major banner 

![Front Page banner - mobile and laptop views](documentation/banner-mobile-tablet-views.png)

The banner itself takes about 75% of the viewport height just enough to reveal a part of the next section - About Us. 




