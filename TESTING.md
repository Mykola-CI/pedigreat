# Testing

## Compatibility

* The Pedigreat site was checked with Chrome, Safari and Firefox browsers
  - __Chrome__

  ![Chrome Navigation](documentation/testing-screnshots/browsers/chrome-navigation.gif)

  ![Chrome Buttons Navigation](documentation/testing-screnshots/browsers/chrome-navigation-buttons.gif)

  - __Safari__

  ![Safari Home Page](documentation/testing-screnshots/browsers/safari-home.gif)

  ![Safari Navigation](documentation/testing-screnshots/browsers/safari-navigation.gif)

  - __Firefox__

  ![Firefox Navigation](documentation/testing-screnshots/browsers/firefox-navigation.gif)

  ![Firefox Navigation & Scroll](documentation/testing-screnshots/browsers/firefox-scroll-navigation.gif)

## Responsiveness
* Web-pages were checked with the [Chrome DevTools](https://developer.chrome.com/docs/devtools/)

  - __Home Page__

  ![DevTools Home Page Grow](documentation/testing-screnshots/devtools-gifs/home-grow.gif)

  ![DevTools Home Page Shrink](documentation/testing-screnshots/devtools-gifs/home-shrink.gif)

  ![DevTools Home Page Shrink](documentation/testing-screnshots/devtools-gifs/home2-shrink.gif)

  - __Gallery__

  ![DevTools Gallery Page Shrink](documentation/testing-screnshots/devtools-gifs/gallery-shrink.gif)

  - __Services__

  ![DevTools Services Page Shrink](documentation/testing-screnshots/devtools-gifs/service-shrink.gif)

  - __Contacts__

  ![DevTools Contact Page Shrink](documentation/testing-screnshots/devtools-gifs/contact-srink.gif)

  - __Registration Form__

  ![DevTools Registration Page Grow](documentation/testing-screnshots/devtools-gifs/registration-grow.gif)

  - __Response Page__

  ![DevTools Response Page Shrink](documentation/testing-screnshots/devtools-gifs/response-shrink.gif)

</br>  

-----

* Web-pages were additionally checked with Media Genesis' tool [Responsive Web Design Checker](https://responsivedesignchecker.com/)

  - __Desktops__

![Checker Desktop Sizes](documentation/testing-screnshots/checker-gifs/dt-sizes.gif)

![Checker Desktop Home Scroll](documentation/testing-screnshots/checker-gifs/dt-home-scroll.gif)

![Checker Desktop Navigation](documentation/testing-screnshots/checker-gifs/dt-navbar-clicks.gif)

![Checker Desktop Book Now](documentation/testing-screnshots/checker-gifs/dt-book-now.gif)

![Checker Desktop Gallery](documentation/testing-screnshots/checker-gifs/dt-gallery-scroll.gif)

![Checker Desktop Sizes](documentation/testing-screnshots/checker-gifs/dt-registration.gif)

![Checker Desktop Tablet Mobile](documentation/testing-screnshots/checker-gifs/dt-tablet-mobile.gif)

</br>

  - __Tablets__

![Checker Tablets Sizes](documentation/testing-screnshots/checker-gifs/tab-sizes.gif)

![Checker Tablets Navigation](documentation/testing-screnshots/checker-gifs/tab-navbar-clicks.gif)

![Checker Tablets Services](documentation/testing-screnshots/checker-gifs/tab-services-scroll.gif)

</br>

  - __Mobiles__

![Checker Mobiles Sizes](documentation/testing-screnshots/checker-gifs/mob-sizes.gif)

![Checker Mobiles Menu](documentation/testing-screnshots/checker-gifs/mob-menu.gif)

![Checker Mobiles RegForm](documentation/testing-screnshots/checker-gifs/mob-register.gif)


## Testing Links and Action Elements (Table Summary)


| __Feature__ | __Action__ | __Expected result__ | __Tested__ | __Comments__ |
| --- | --- | --- | --- | --- |
| __Navbar__ | | | | Available across all the pages | 
| Pedigreat | Click on the "Pedigreat" logo link | The user is redirected to the Home page | Yes | Tested from all pages |
| Home | Click on the "Home" link | The user is redirected to the Home page | Yes | Tested from all pages |
| Gallery | Click on the "Gallery" link | The user is redirected to the gallery page | Yes | Tested from all pages |
| Services | Click on the "Services" link | The user is redirected to the Services page | Yes | Tested on all pages |
| Contact | Click on the "Contact" link | The user is redirected to the Contact page | Yes | Tested from all pages |
| __Footer__ | | | | Available across all the pages |
| Facebook icon in the footer | Click on the Facebook icon | The user is redirected to the Facebook page | Yes | - |
| Twitter icon in the footer | Click on the Twitter icon | The user is redirected to the Twitter page | Yes | - |
| YouTube icon in the footer | Click on the YouTube icon | The user is redirected to the YouTube page | Yes | - |
| Instagram icon in the footer | Click on the Instagram icon | The user is redirected to the Instagram page | Yes | - |
| __Home page__ | | | | |
| "Book Now" button on the main banner | Click on the "Book Now" button | The user is redirected to the Contacts page | Yes | - |
| "Learn More" links in About Us section | Click on the "Learn More" link | The user is redirected to the Services page | Yes | - |
| "Learn More" links in Services section | Click on the "Learn More" button | The user is redirected to the Services page | Yes | Tested 4 links |
| __Services page__ | | | | |
| "Book Now" button in the Price Cards | Click on the "Book Now" button | The user is redirected to the Contacts page | Yes | Tested 4 buttons |
| __Contacts page__ | | | | | |
| "Go On Register Now" button | Click "Go On Register Now" button | User is redirected to the Customer Registration Form | Yes | - |
| __Registration Form page__ | | | | | |
| "First Name" input | Key in the first name | the name is displayed | Yes | required |
| "Last Name" input | Key in the last name | the name is displayed | Yes | required |
| "Mobile Number" input | Key in the number | the number is displayed | Yes | optional  |
| "E-Mail" input | Key in the e-mail| e-mail is displayed | Yes | required. If '@' is missing the popup appears 'please include @...' |
| "How did you know about us" drop down | select an option | the option selected and displayed | Yes | optional |
| "Enter Your Pet Name" input | key in a name | the name is displayed | Yes | required |
| "What services are you interested in" checkbox | check any number of options | the options checked displayed as tick mark | Yes | optional |
| "What size is your pet" radio buttons | select an option | only one option can be selected and displayed | Yes | optional |
| "Submit Form" button | click the button | User directed to the response page | Yes | in case one of the required fields was not filled in, the popup appears "Please fill in this field" |

## Validator Testing

* __HTML__

  - __Home Page__

![W3C Validator](documentation/testing-screnshots/validator-giffs/w3c-validation-pedigreat-2023-11-10.png)

![W3C Validator](documentation/testing-screnshots/validator-giffs/w3c-validation-pedigreat-index-html-23-11-10.png)

  - __Gallery Page__

![W3C Validator](documentation/testing-screnshots/validator-giffs/w3c-validation-pedigreat-gallery-html-23-11-10.png)

  - __Services Page__

![W3C Validator](documentation/testing-screnshots/validator-giffs/w3c-validation-pedigreat-services-html-23-11-10.png)

  - __Contacts Page__

![W3C Validator](documentation/testing-screnshots/validator-giffs/w3c-validation-pedigreat-contact-html-23-11-10.png)

  - __Registration Form__

![W3C Validator](documentation/testing-screnshots/validator-giffs/w3c-validation-pedigreat-customer-form-html-23-11-10.png)


* __CSS Validation__

![W3C CSS Validator](documentation/testing-screnshots/validator-giffs/w3c-validation-css-2023-11-10.png)

35 warning regarding the use of :root variables: "Due to their dynamic nature, CSS variables are currently not statically checked".

![CSS Validator warnings](documentation/testing-screnshots/validator-giffs/css-warnings-var-2023-11-10.png)

## Lighthouse Report

* __Home Page__

![Lighthouse Report Home page](documentation/testing-screnshots/lighthouse/lighthouse-home.png)

* __Gallery Page__

![Lighthouse Report Home page](documentation/testing-screnshots/lighthouse/lighthouse-gallery.png)

* __Services Page__

![Lighthouse Report Home page](documentation/testing-screnshots/lighthouse/lighthouse-services.png)

* __Contacts Page__

![Lighthouse Report Home page](documentation/testing-screnshots/lighthouse/lighthouse-contacts.png)

* __Registration Form__

![Lighthouse Report Home page](documentation/testing-screnshots/lighthouse/lighthouse-registration.png)

* __Response Page__

![Lighthouse Report Home page](documentation/testing-screnshots/lighthouse/lighthouse-response.png)

</br>


## Bugs Unfixed