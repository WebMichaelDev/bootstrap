# [Bootstrapmedia](https://bootstrapmedia.website/images/contactpage.png)

* [Luuk](#luuk)

* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Technical Support or Questions](#technical-support-or-questions)
* [Licensing](#licensing)




## Luuk

    Ombouwen naar een react app
    
    
    Homepage werkend maken het moet een offerte aanvraag stukje worden naam email wat voor een platform en dan wat text invoer en get started word dan submit 
    en onderaan de nieuwsbrief met mailchimp
- ![Homepage](http://bootstrapmedia.website/images/home.png)
  ![Homepagenews](http://bootstrapmedia.website/images/homenews.png)

    Contact pagina werkend maken
- ![Contactpage](http://bootstrapmedia.website/images/contactpage.png)

    Offertepagina werkend maken
- ![Offertepage](http://bootstrapmedia.website/images/offerte.png)

    Faq pagina omtoveren naar werkende zoekfuntie (ik denk dat er dan mongodb achter zou moeten)
- ![Faq](http://bootstrapmedia.website/images/faq.png)

    Coming-soon pagina werkende nieuwsbrief module
- ![coming-soon](http://bootstrapmedia.website/images/compingsoon-news.jpg)

    Wizard ombouwen (vragenlijst voor webdesign (onderaan de pagina links staat wizard)
- [Wizard](https://themes.getbootstrap.com/preview/?theme_id=7340&show_new=)

Vertaling inbouwen in de footer staat als een html/css stukje 
er moet kwa taal nederlands en engels in (misschien boven aan ook iets van een selector voor talen)

    hier hebben we het gekocht mocht je meer info nodig hebben
- [Extra info](https://themes.getbootstrap.com/preview/?theme_id=7340&show_new=)




## Documentation
(https://www.notion.so/Product-Wiki-fe02faa7a9a248ba919161b562ee2fff)


## File Structure
Moeten we nog uitbouwen maar kan pas als het een react app is

```
Bootstrapmedia
.
├── README.md
├── gulpfile.js
├── jsconfig.json
├── package.json
├── Documentation
│   ├── assets
│   │   ├── css
│   │   ├── img
│   │   │   └── faces
│   │   └── js
│   └── tutorial-components.html
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── assets
    │   ├── css
    │   │   ├── material-kit-pro-react.css
    │   │   ├── material-kit-pro-react.css.map
    │   │   └── material-kit-pro-react.min.css
    │   ├── img
    │   │   ├── arrow-left.cur
    │   │   ├── arrow-right.cur
    │   │   ├── assets-for-demo
    │   │   │   ├── example-pages
    │   │   │   ├── ourClients
    │   │   │   ├── presentationViewSectionComponent
    │   │   │   └── sections
    │   │   │       └── imgs.js
    │   │   ├── examples
    │   │   ├── faces
    │   │   ├── flags
    │   │   ├── loading-bubbles.svg
    │   │   └── sections
    │   ├── jss
    │   │   ├── material-kit-pro-react
    │   │   │   ├── components
    │   │   │   └── views
    │   │   │       ├── aboutUsSections
    │   │   │       ├── blogPostSections
    │   │   │       ├── blogPostsSections
    │   │   │       ├── componentsSections
    │   │   │       ├── ecommerceSections
    │   │   │       ├── landingPageSections
    │   │   │       ├── presentationSections
    │   │   │       ├── pricingSections
    │   │   │       ├── sectionsSections
    │   │   └── material-kit-pro-react.js
    │   └── scss
    │       ├── core
    │       │   ├── mixins
    │       │   └── variables
    │       ├── plugins
    │       └── material-kit-pro-react.scss
    ├── components
    │   ├── Accordion
    │   │   └── Accordion.js
    │   ├── Badge
    │   │   └── Badge.js
    │   ├── Card
    │   │   ├── Card.js
    │   │   ├── CardAvatar.js
    │   │   ├── CardBody.js
    │   │   ├── CardFooter.js
    │   │   └── CardHeader.js
    │   ├── Clearfix
    │   │   └── Clearfix.js
    │   ├── CustomButtons
    │   │   └── Button.js
    │   ├── CustomDropdown
    │   │   └── CustomDropdown.js
    │   ├── CustomFileInput
    │   │   └── CustomFileInput.js
    │   ├── CustomInput
    │   │   └── CustomInput.js
    │   ├── CustomLinearProgress
    │   │   └── CustomLinearProgress.js
    │   ├── CustomTabs
    │   │   └── CustomTabs.js
    │   ├── CustomUpload
    │   │   └── ImageUpload.js
    │   ├── Footer
    │   │   └── Footer.js
    │   ├── Grid
    │   │   ├── GridContainer.js
    │   │   └── GridItem.js
    │   ├── Header
    │   │   ├── Header.js
    │   │   └── HeaderLinks.js
    │   ├── InfoArea
    │   │   └── InfoArea.js
    │   ├── Instruction
    │   │   └── Instruction.js
    │   ├── Media
    │   │   └── Media.js
    │   ├── NavPills
    │   │   └── NavPills.js
    │   ├── Pagination
    │   │   └── Pagination.js
    │   ├── Parallax
    │   │   └── Parallax.js
    │   ├── Snackbar
    │   │   └── SnackbarContent.js
    │   ├── Table
    │   │   └── Table.js
    │   └── Typography
    │       ├── Danger.js
    │       ├── Info.js
    │       ├── Muted.js
    │       ├── Primary.js
    │       ├── Quote.js
    │       ├── Rose.js
    │       ├── Small.js
    │       ├── Success.js
    │       └── Warning.js
    ├── index.js
    ├── logo.svg
    └── views
        ├── AboutUsPage
        │   ├── AboutUsPage.js
        │   └── Sections
        │       ├── SectionContact.js
        │       ├── SectionDescription.js
        │       ├── SectionOffice.js
        │       ├── SectionServices.js
        │       └── SectionTeam.js
        ├── BlogPostPage
        │   ├── BlogPostPage.js
        │   └── Sections
        │       ├── SectionBlogInfo.js
        │       ├── SectionComments.js
        │       ├── SectionSimilarStories.js
        │       └── SectionText.js
        ├── BlogPostsPage
        │   ├── BlogPostsPage.js
        │   └── Sections
        │       ├── SectionImage.js
        │       ├── SectionInterested.js
        │       ├── SectionPills.js
        │       └── SubscribeLine.js
        ├── ComponentsPage
        │   ├── ComponentsPage.js
        │   └── Sections
        │       ├── SectionBasics.js
        │       ├── SectionCards.js
        │       ├── SectionCarousel.js
        │       ├── SectionContentAreas.js
        │       ├── SectionFooter.js
        │       ├── SectionJavascript.js
        │       ├── SectionNavbars.js
        │       ├── SectionNotifications.js
        │       ├── SectionPills.js
        │       ├── SectionPreFooter.js
        │       ├── SectionTabs.js
        │       └── SectionTypography.js
        ├── ContactUsPage
        │   └── ContactUsPage.js
        ├── EcommercePage
        │   ├── EcommercePage.js
        │   └── Sections
        │       ├── SectionBlog.js
        │       ├── SectionLatestOffers.js
        │       └── SectionProducts.js
        ├── ErrorPage
        │   └── ErrorPage.js
        ├── LandingPage
        │   ├── LandingPage.js
        │   └── Sections
        │       ├── SectionProduct.js
        │       ├── SectionTeam.js
        │       └── SectionWork.js
        ├── LoginPage
        │   └── LoginPage.js
        ├── PresentationPage
        │   ├── PresentationPage.js
        │   └── Sections
        │       ├── SectionCards.js
        │       ├── SectionComponents.js
        │       ├── SectionContent.js
        │       ├── SectionDescription.js
        │       ├── SectionExamples.js
        │       ├── SectionFreeDemo.js
        │       ├── SectionOverview.js
        │       ├── SectionPricing.js
        │       └── SectionSections.js
        ├── PricingPage
        │   ├── PricingPage.js
        │   └── Sections
        │       ├── SectionFeatures.js
        │       └── SectionPricing.js
        ├── ProductPage
        │   └── ProductPage.js
        ├── ProfilePage
        │   └── ProfilePage.js
        ├── SectionsPage
        │   ├── Sections
        │   │   ├── SectionBlogs.js
        │   │   ├── SectionContacts.js
        │   │   ├── SectionFeatures.js
        │   │   ├── SectionHeaders.js
        │   │   ├── SectionPricing.js
        │   │   ├── SectionProjects.js
        │   │   ├── SectionTeams.js
        │   │   └── SectionTestimonials.js
        │   └── SectionsPage.js
        ├── ShoppingCartPage
        │   └── ShoppingCartPage.js
        └── SignupPage
            └── SignupPage.js
```


## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">




## Reporting Issues




## Technical Support or Questions

If you have questions or need help integrating the product please [contact us](https://www.bootstrapmedia.website/contact) instead of opening an issue.



## Licensing

- Copyright 2020 Bootstrapmedia (https://www.bootstrapmedia.website)





