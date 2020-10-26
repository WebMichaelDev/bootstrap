# [Bootstrapmedia](https://bootstrapmedia.website/images/contactpage.png)

* [Luuk](#luuk)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Technical Support or Questions](#technical-support-or-questions)
* [Licensing](#licensing)
* [Useful Links](#useful-links)



## Luuk

    Homepage pagina werkend maken en de nieuwsbrief met mailchimp
- [Homepage](http://bootstrapmedia.website/images/home.png)
            (http://bootstrapmedia.website/images/homenews.png)

    Contact pagina werkend maken
- [Contactpage](http://bootstrapmedia.website/images/contactpage.png)

    Offertepagina werkend maken
- [Offertepage](http://bootstrapmedia.website/images/offerte.png)

    Faq pagina omtoveren naar werkende zoekfuntie (ik denk dat er dan mongodb achter zou moeten)
- [Faq](http://bootstrapmedia.website/images/faq.png)

    Coming-soon pagina werkende nieuwsbrief module
- [coming-soon](http://bootstrapmedia.website/images/compingsoon-news.jpg)

    Wizard ombouwen (vragenlijst voor webdesign (onderaan de pagina links staat wizard)
- [wizard](https://themes.getbootstrap.com/preview/?theme_id=7340&show_new=)


Vertaling inbouwen in de footer staat als een html/css stukje 
er moet kwa taal nederlands en engels in (misschien boven aan ook iets van een selector voor talen)

    hier hebben we het gekocht mocht je meer info nodig hebben
- [Extra info](https://themes.getbootstrap.com/preview/?theme_id=7340&show_new=)




## Quick start

- Buy from [Creative Tim](https://www.creative-tim.com/product/material-kit-pro-react)


## Documentation
The documentation for the Material Kit PRO React is hosted at our [website](https://demos.creative-tim.com/material-kit-pro-react/#/documentation/tutorial).


## File Structure
Within the download you'll find the following directories and files:

```
material-kit-pro
.
├── CHANGELOG.md
├── ISSUE_TEMPLATE.md
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


## Resources
- Demo: <https://demos.creative-tim.com/material-kit-pro-react/#/components>
- Download Page: <https://www.creative-tim.com/product/material-kit-pro-react>
- Documentation: <https://demos.creative-tim.com/material-kit-pro-react/#/documentation/tutorial>
- License Agreement: <https://www.creative-tim.com/license>
- Support: <https://www.creative-tim.com/contact-us>
- Issues: [Github Issues Page](https://github.com/creativetimofficial/ct-material-kit-pro-react/issues)
+ [Material Kit Free React](https://demos.creative-tim.com/material-kit-react/#/)
+ [Material Kit Free](https://demos.creative-tim.com/material-kit/index.html)
+ [Material Dashboard Free React](https://demos.creative-tim.com/material-dashboard-react/#/dashboard)
+ [Material Dashboard Pro React](https://demos.creative-tim.com/material-dashboard-pro-react/#/dashboard)
+ [Material Dashboard Free HTML](https://demos.creative-tim.com/material-dashboard/examples/dashboard.html)
+ [Material Dashboard Pro HTML](https://demos.creative-tim.com/material-dashboard-pro/examples/dashboard.html)
+ [Material Dashboard Free Angular](https://demos.creative-tim.com/material-dashboard-angular2/dashboard)
+ [Material Dashboard Pro Angular](https://demos.creative-tim.com/material-dashboard-pro-angular2/dashboard)


## Reporting Issues

We use GitHub Issues as the official bug tracker for the Material Kit PRO React. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Material Kit PRO React. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.


## Technical Support or Questions

If you have questions or need help integrating the product please [contact us](https://www.creative-tim.com/contact-us) instead of opening an issue.



## Licensing

- Copyright 2020 Creative Tim (https://www.creative-tim.com/)

- Creative Tim [license](https://www.creative-tim.com/license)



## Useful Links

- [More products](https://www.creative-tim.com/bootstrap-themes) from Creative Tim
- [Tutorials](https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w)
- [Freebies](https://www.creative-tim.com/bootstrap-themes/free) from Creative Tim
- [Affiliate Program](https://www.creative-tim.com/affiliates/new) (earn money)

##### Social Media

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Google+: <https://plus.google.com/+CreativetimPage>

Instagram: <https://www.instagram.com/CreativeTimOfficial>
