![Hard Drivers](https://github.com/BAK2K3/hard-drivers/blob/master/assets/images/full-logo.png "Hard Drivers Logo")

# Hard Drivers

## Overview

This project is a static website for a fictitious Custom PC Building company, called Hard Drivers.  
It is developed primarily using HTML and CSS, with a small amount of javascript implemented for additional functionality.

[View website on Github Pages](https://bak2k3.github.io/hard-drivers/index.html)

---

## Project Concept

>**Hard Driver**  
hɑːd ˈdraɪvə | **Noun**  
*A CompTIA A+ certified computer magician, who has an abundance of love and pride for making your dream computer become a reality.*  

Hard Drivers is a customer budget based Custom PC Building company. Customers can obtain a _“no obligation”_ free specification for a custom build PC based on a budget of their choosing. Customers can also choose to include additional service packages to their specification, and request additional peripherals (i.e Monitor, Keyboard, Mouse, etc) to be paired perfectly with their brand new tailor-made computer. 

---

# UX

## Strategy

### Stakeholder Interview

**What are some of your most important considerations when using a company to buy a custom build computer?**

_“I don’t want to have to keep adding parts to see the costs skyrocket, then have to start removing things I think I need or want, in order to keep it within a budget”._  

_“I want someone to recommend exactly what I need”._    

_“I want to be able to contact the company straight away”._    

### Competitor Review

[PC Specialist](https://www.pcspecialist.co.uk/ "Pc Specialist Homepage"): A huge amount of options from the outset, with quite significant price ranges. Onus is on the customer to know what they want/need.

[Box](https://www.box.co.uk/ "Box Homepage"): A less specific focus on builds, with immediate attention drawn to peripherals rather than computer.

[Chillblast](https://www.chillblast.com/ "Chillblast Homepage"): Not very user friendly, a lot of information, a lot of options, and high selling point is pre-build next day PCs.

### Company Strategy

**Psychological Factors**
* Evoke a positive emotional response from the branding of Hard Drivers.
  * Make the branding strong, bold, and stand out.
  * Make the branding unique, and aesthetically pleasing.
  * Apply the branding consistently throughout the website.
  * Align the style and design of the pages to match the branding.
  * Minimalistic design approach, so as to not overwhelm the customer.
* Appeal to the customer by personalising the service.
  * Address the customer directly by repeatedly using the term _"You"_ and _"Your"_.
  * Make it clear that each customer is unique, and each computer will be build specifically for their needs.

**Pricing**
* Be transparent with cost.
    * The user decides the cost of the computer.
    * No hidden costs.
* Upsell as a separate entity.
    * Peripherals and Service packages are not included in initial budget.
    * The customer is not required to spend any more than their budget.

**Buyer Making Decision**
* Offer a _"No Obligation"_ quote/specification.
    * The customer will therefore not need to justify engaging with the company/website.
    * As such, they do not need to plan to engage with the company/website, other than stating a budget.
* Communicate that the hard work is taken away from the customer.
    * This suggests the user only needs to put in a small amount of effort to receive a full service in return.

**Product Considerations and Content Strategy**
* Minimalistic design, so at to draw attention, avoid overwhelming the customer, and encourage engagement.
    * The product is the _service_ provided by Hard Drivers, therefore strong colours, images, and headlines to engage with customer.
* Thin content where necessary, providing only the most important information from the outset.
    * Provide fuller content in sections of the website where the customer specifically wants further information.
* Every page has multiple "Enquire Now" buttons, so as to allow a user to immediately engage when they want to.
    * This "Enquire Now" should ultimately be a "Fast Track" service to allow a user to go from making the decision to enquire, to having made the enquiry, in as few interactions as possible.

### User Stories

1. `As a visitor to the website, I want to know what your company does.`  
2. `As a potential customer, I want to know what services you provide.`  
3. `As an interested customer, I want to know how much the service costs.` 
4. `As a convinced customer, I want to be able to easily make an enquiry.`

---

## Scope

Based on the research completed in the Strategy plane, and the subsequent User Stories (the _"why"_), the requirements were split into Non-Functional and Functional Requirements. The Non-Functional Requirements 
describe the overall intended goals of the project (the _'what'_) and when broken down act as 'Conditions of Satisfaction' for the User Stories, while the Functional Requirements details how these are going to be achieved (the _"how"_) 
through the specific features implemented.

### Non-Functional Requirements

**Encourage and Allow User Engagement**

* Every page must allow a user to engage with the business.
* The ability to engage is clear and stands out from other interactive aspects of the site.
* Engagement is done through completing an simple and intuitive enquiry form.

**Convey Ethos/Purpose**

* Outline key services on home page.
* Present further details on key services on separate page.
* Make sure the details provided are important, sellable, and merit being detailed in isolation.
* Make the descriptions bite sized and easy to digest.

**Instil User Confidence**

* The branding is clear, distinguishable, and recognisable.
* Relate to and refer to the customer.
* The website is minimalistic where necessary, intuitive, and user friendly. 

**Present Cost Approach**

* Communicate that the computer is customer budget based.
* Be transparent about cost of additional services and peripherals. 
* Provide detailed yet convincing breakdown of cost of service

### Functional Requirements

**Navigation bar (Navbar)**

Each page has a sticky navbar at the top. This provides a consistent layout and structure as the user navigates through the site. The logo is always centred, and is always the most prominent header on each page. On large devices, the navbar 
has a second row underneath the logo which displays the active page the user is on,  On mobile devices, the navigation links are hidden,
and activated with a "sandwich" (which is a server icon), which draw the links between the page logo and the current page's sub-heading. The consistent, simple, and intuitive navigation system would contribute to instilling user trust, and allows
users to reach all aspects of the site which aid the satisfaction of all user-stories.

**Footer**

Each page has a static footer at the bottom. This provides links Github, a second and more aestheticically stimulating link to the enquire page, and links to socials. The same background effect is used on the footer, but with the gradient
reversed, to provide an 'enclosed' look. Once again, this effect is subtle yet effective, and intends to produce a strong positive emotional response in order to instil trust in the user. The Enquire button is designed to grab the user’s attention, 
with a continuous glowing effect. This effect encourages the user to interact with the link, and therefore engage with the website. On mobile devices, the footer is similar in layout, with the only significant change being font size and positioning of the social links 
for a more user-friendly interface. As discussed, on the "Enquire" page, as opposed to having a second "Enquire" button on the bottom, this button has been converted into a "Submit" button, which removes the redundancy of a recursive link, 
and implements a function which is relevant and fits the contextual flow of the page. 

**Price Table**

A price table is available on multiple pages of the site. It provides the user with a full breakdown of the different tiers of service packages they can opt into when requesting a quote for their computer. The cost and benefits of these packages 
is explicitly clear, and a full screenreader-only description is available which explains which benefits are included in which package, and their associated costs. Each tier benefit contains a tooltip to provide additional information on the service included. 
On Modals, the tooltips are on the text of the benefits themselves,  while on the Desktop "Enquire" page, small self-descriptive icons sit at the end of each benefit that provide this tooltip.

**Enquiry Form**

The enquiry form allows the user to provide a small amount of personal details, and information regarding their requirements, in order to engage with the company and to receive a specification in response. 
Each field is categorised and grouped into the relevant fieldset, with each individual field being clearly separated and labelled. Out of 8 fields, 6 are required, and 2 are optional. The user must supply their name, email address, and phone number. 
They must then decide what type of computer they want, and their budget. In all viewports, the "Budget" field contains a tooltip which explicitly states the budget stated excludes the cost of the service package requested, and any potential optional peripherals to be quoted.
The user can at this stage decide to opt in to be quoted for an optional peripheral to be paired with their computer. The user must then select a package tier, and then optionally provide more 
information regarding their requirements if they should wish to do so. Initially, a colour picker was implemented into the form, however this resulted in quite an arduous addition;  considering this aspect of the engagement is essentially just a request for an initial quote,
this would have added nothing to the initial enquiry and added an additional unneccessary step towards requesting a quote, and was therefore removed. It was also found on mobile devices that the colour picker was limited, and therefore could have easily frustrated the user. 

**Modals**

Modals are implemented into the site to provide an additional degree of interactivity. They are also present to layer content where neccessary, so as to not compress to information into a single location. The modals either contain the price table, or a thank you message 
once the user has completed and submitted the enquiry form. 

**Viewport Control**

Where possible, the pages contain all information within the user's viewport. Where this is not possible on very small mobile devices, or on the enquiry page, an intuitive navigation system has been implemented to allow for only the content
of the page (not the headings) to be scrollable. By presenting all information on the screen at once, due to having a minimalistic design, this should produce a powerful emotional response from the user, as if the content had been designed for their specific needs,
and would ensure that no information is missed.  

**Responsive Layout and design**

Using Flexbox, the site is designed to be fluid, dynamic, and responsive to all screen sizes and resolutions. While certain breakpoints have been implemented to change the structure of the content, the priority was to implement flui 
The content of each page dynamically responds and adjusts to the users screen size, regardless of what device they are using, and regardless of how big or small their screen is. 

## Structure

### Informational Architecture and Interaction Design

#### Index Page

* Provides a full breakdown of the company, its ethos, and its purpose.
* Grabs customer's attention, engages, and encourages user to make an enquiry.
* **User Goal**:
    * Simple to interact with.
    * Explains business purpose.
    * Allows and encourages easy engagement.
* **Business Goal**:
    * Interest the user.
    * Engage the user.
    * Sustain the user.
    * Convey Company ethos and purpose.

#### About Page

* Explains how cost works.
* Instils trust by selling the brand and the service.
* Explains ethos and purpose.
* **User Goals**:
    * Obtain information about the company.
    * Understand how the cost works.
    * Understand how to use the service.
* **Business Goals**:
    * Convey company ethos.
    * Sell the brand.
    * Convince customer to engage with company.
    * Be transparent about cost, services, and purpose.

#### Enquire Page

* Allows customer to submit enquiry by providing a small amount of information.
* Offers a simple and intuitive method of enquiring.
* Uses a user-friendly interface.
* The feeling of achieving a lot from a small amount of input from the customer.
* **User Goals**:
    * A simple an intuitive form of communication.
    * Feel like little information needed to instigate engagement.
    * A positive user experience during form filling.
* **Business Goals**:
    * Instigate engagement.
    * Obtain customer information to proceed with service.
    
**Packages Page: A Discussion on Informational Architecture**

As a Business, Hard Drivers would primarily make the most amount of profit from the additional services provided on top of the custom build computers. 
As such, an additional page was initially planned called _"Packages"_, which provided the customer with a detailed breakdown of the additional services 
they could purchase in conjunction with their new computer. This can be seen from the original wireframe designs.

After reviewing the original plans and wireframes, and after additional consideration, it was considered that this information in isolation appeared to be quite _'content thin'_,
and could potentially make having a separate page for this content feel empty and isolated. In addition to this, it would be entirely possible for a customer to visit the index page,
engage with the site immediately as intended, and forgo this page entirely.  Given this information is integral for the business, consideration needed to be made as to 
where this content could be added. Having this information appear on the _"Index"_ page would defer from its minimalistic design and intention, and could potentially feel like 
over-selling from a customer perspective, and considering the intention, context, and grouping of information on the _"About"_ page, it was decided that the _"packages"_ information would 
overload this page or side-track its intention.

From a business perspective, this information needed to be accessible and hard to miss. However, as a consumer, you would not want to be over-burdened with aggressive overselling. 
The positioning of this information needed to be relevant, compliment the flow and structure of the other pages, along with their features and content, and needed to fulfil its business purpose
of being a mandatory part of the selling process, without being intrusive. 

A work-around to this was explored, and has been considered for implementation, whereby the _"packages"_ page is removed entirely, and reference can be made in the _"About"_ page, under Cost, 
to additional services being provided. This reference will link to a modal whereby the content initially planned for the _"packages"_ page is displayed. In doing this, the services can be subtly referenced,
without being intrusive, and can provide the user with the additional information if they request it. Furthermore, in the _"Enquire"_ page, under the _"packages"_ section, the decision has been made
to ensure no package is preselected, and to provide a link to the same modal as previously referenced. In doing so, the user must engage with this aspect of the sales process, fulfilling the business need,
however is not obliged to delve into the additional information if they do not wish to do so, which would potentially fulfil the customer need of not being overwhelmed with information unnecessarily.

## Skeleton

### Wireframes

Due to the resolution of the wireframe documents, it is recommended that these PDFs are downloaded, rather than using Github's native PDF viewer. 

* Header/Footer Wireframe: [Version 1](./assets/wireframes/header-footer-wireframe.pdf) | [Version 2](./assets/wireframes/header-footer-wireframe-v2.pdf)
* Index Page Wireframe: [Version 1](./assets/wireframes/index-wireframe.pdf)
* About Page Wireframe: [Version 1](./assets/wireframes/about-wireframe.pdf) | [Version 2](./assets/wireframes/about-wireframe-v2.pdf)
* Packages Wireframe: [Version 1](./assets/wireframes/packages-wireframe.pdf) | [Version 2](./assets/wireframes/packages-wireframe-v2.pdf)
* Enquire Wireframe: [Version 1](./assets/wireframes/enquire-wireframe.pdf) | [Version 2](./assets/wireframes/enquire-wireframe-v2.pdf)

---

## Surface

### Design

### Visual Effects

**Header**: The navbar's background image is filtered through a radial top focused gradient, and is intended to provide a subtle yet effective "electrical" effect, with a colour scheme consistent with the rest of the site. 

**Nav Links**: Each link offering a mild yet stimulating visual effect when either the link is engaged with or hovered over.

#### Colour Scheme

##### Logo Mock-Ups

Logo: [Full](./assets/images/full-logo.png) / [Small](./assets/images/small-logo.png)

##### Accessibility

---

# Future Feature Considerations

* **Process details in enquiry form**

* **GDPR information as personal information being processed**

* **Bot/Spam prevention on form completion**

* **Provide Live Service**

* **Gain Presence**

* **Smart Specification**

---

# Technologies Used

* The project was primarily written in HTML and CSS. Small snippets of Javascript were used to enhance user experience.
* The project was written and tested in the [Gitpod](https://gitpod.io/) IDE.
* The project uses [github](https://github.com/) for hosting source code, for utilising git version control, and for hosting the site on github pages.  
* The project's template was generated from [Code Institute's Gitpod Template](https://github.com/Code-Institute-Org/gitpod-full-template).
* The project uses [Boostrap](https://getbootstrap.com/) v4.5.3, a 'Mobile First' HTML/CSS Framework for simple and intuitive responsive web design.
* The project uses [jQuery](https://jquery.com/) v3.5.1, a Javascript library, for certain Bootstrap elements, and for form validation.
* The project uses [Popper.js](https://popper.js.org/) v1.16.1, a Tooltip and Popover Positioning Enginge, for Tooltips and dropdowns.
* The project uses [jsDelivr](https://www.jsdelivr.com/) as a Content Delivery Network for Bootstrap and Popper.
* The project uses [FontAwesome](https://fontawesome.com/) v5.15.1, a free icon-set/toolkit for web development.
* The project uses [Google Fonts](https://fonts.google.com/) for typography.
* The project's images were compressed via [tinyjpg](https://tinyjpg.com/) to be appropriately sized for web content.
* The project's accessibility was assesed via WebAim's [W.A.V.E](https://wave.webaim.org/) and Google Chrome's [Lighthouse](https://developers.google.com/web/tools/lighthouse).
* The project's screen-reader accessibility was tested using [Screen Reader for Google Chrome](https://chrome.google.com/webstore/detail/screen-reader-for-google/nddfhonnmhcldcbmhbdldfpkbfpgjoeh/related?hl=en)
* The project used Toptal's [Colorfilter](https://www.toptal.com/designers/colorfilter/) to assess how colourblind-friendly the site was.
* The project's contract ratio was assessed using WebAim's [Contract Checker](https://webaim.org/resources/contrastchecker/)
* The project's cross-browser compatability was enhanced using [Autoprefixer.io](https://autoprefixer.github.io).
* The project's HTML was validated using [W3C HTML Markup Validator](https://validator.w3.org/).
* The project's CSS was validated using [W3C Jigsaw CSS Validator](https://jigsaw.w3.org/css-validator/).
* The project's Bootstrap was validated using [Bootlint](https://github.com/twbs/bootlint).

---
# Testing

Testing documentation, processes, and outcomes can be found under [TESTING.md](TESTING.md).

---
# Deployment

## How this Project was Deployed

This project was deployed to GitHub pages via the following steps:

1. Log into [GitHub](https://github.com/).
2. From the list of Repositories, select [BAK2K3/hard-drivers](https://github.com/BAK2K3/hard-drivers).
3. From the Repositories sub-headings, select "Settings".
4. Under "Options", the first category of settings, scroll down to the GitHub Pages section.
5. From the dropdown list under the "Source" heading, select "master".
6. A second drop-down menu that appears should remain as the default value, "/root".
7. Press Save. 
8. On Page refresh, scroll back down to the GitHub Pages section, and the link to the deployed site will be available in a green sub-section with a tick icon next to it.

As this project was developed on the master branch, all changes made to the repository are immediately reflected in the deployed project.

## How to run this Project in your Browser

1. Install the [Google Chrome](https://www.google.co.uk/chrome/) or [Firefox](https://www.mozilla.org/en-GB/exp/firefox/new/) browser.
2. Install the applicable [GitPod](https://www.gitpod.io/docs/browser-extension/) Browser Extensions for your chosen browser.
4. Create a [GitHub](https://github.com/join) account. 
3. Log in to [Gitpod](https://gitpod.io/login/) using your GitHub account.
4. Visit Hard Driver's [GitHub Repository](https://github.com/BAK2K3/hard-drivers).
5. Open the respository in Gitpod:
    * Click the green "Gitpod" icon at the top of the Repository, or
    * Click this [link](https://gitpod.io/#https://github.com/BAK2K3/hard-drivers).
6. A new workspace will open with the current state of the master branch. Any changes made to the master branch after this point will not be automatically updated in your Gitpod Workspace.

## How to run this Project Locally

### Cloning the Repository

1. Visit Hard Driver's [GitHub Repository](https://github.com/BAK2K3/hard-drivers).
2. Click the "Code" dropdown box above the repository's file explorer. 
3. Under the "Clone" heading, click the "HTTPS" sub-heading.
4. Click the clipboard icon, or manually copy the text presented: `https://github.com/BAK2K3/hard-drivers.git`
5. Open your preferred IDE (VSCode, Atom, PyCharm, etc).
6. Ensure your IDE has supoport for Git, or has the relevant Git extension.
7. Open the terminal, and create a directory where you would like the Respository to be stored.
8. Type `git clone` and paste the previously copied text (`https://github.com/BAK2K3/hard-drivers.git`) and press enter.
9. The Repository will then be cloned to your selected directory. 

### Manually Downloading the Respository

1. Visit Hard Driver's [GitHub Repository](https://github.com/BAK2K3/hard-drivers).
2. Click the "Code" dropdown box above the repository's file explorer. 
3. Click the "Download ZIP" option; this will download a copy of the selected branch's repository as a zip file.
4. Locate the ZIP file downloaded to your computer, and extract the ZIP to a designated folder which you would like the repository to be stored.

### Opening the Repository 

1. Open your preferred IDE (VSCode, Atom, PyCharm, etc).
2. Navigate to the chosen directory where the Respository was Cloned/Extracted.
3. You will not have offline access to the contents of the project.

---

# Credits

## Content

* All text used throughout the site was written by myself.
* All business ideas and general development concepts were devised by myself. 

## Media

* All Photographs were sourced from [Unsplash](https://unsplash.com/). 
    * Hero-image.jpg is by [Photography Account](https://unsplash.com/@notsurewhyinamedmyselfthiss?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText).
    * Computer.jpg is by [Christian Wiediger](https://unsplash.com/@christianw?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText). 
    * Experts.jpg is by [Sean Do](https://unsplash.com/@everywheresean?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText).
    * processor.jpg is by [Zii Miller](https://unsplash.com/@anarchist?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText).
* The Header and Footer banner background was created in [Gimp](https://www.gimp.org/), using the Lava Generation effect.
* The Favicon was also created in [Gimp](https://www.gimp.org/), and converted to appropriate format using [favicon.io](https://favicon.io/).
* The conceptual Logo mock-ups were also created in [Gimp](https://www.gimp.org/).

## Code

* HTML/CSS: Implementation and utilisation of Flexbox was assisted by [CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/).
* HTML: Code Snippet taken from [StackOverflow](https://stackoverflow.com/questions/49780918/how-can-i-have-brand-and-navbar-on-separate-lines) and modified to utilise D-flex and Flex Column to create two rows for the Navbar.
* HTML: Code Snippet taken from [StackOverflow](https://stackoverflow.com/questions/5111964/disable-auto-zoom-field-zoom-on-input-tags-on-my-mobile-site-without-disabling) and implemented into Enquiry header to prevent auto-zooming on mobile devices.
* HTML/CSS: Inspiration for pricing table was taken from [Codeply](https://www.codeply.com/go/BmIqIeuNoD/bootstrap-4-comparison-table-options-table) and heavily modified.   
* HTML/CSS: Guidance on Bootstrap, Tooltips, Modals and general Bootstrap integration and usage was obtained from the [Bootstrap Documentation](https://getbootstrap.com/docs/4.5/getting-started/introduction/).         
* HTML/CSS: Guidance on general HTML/CSS usage was obtained from [Mozilla's Web Documentation](https://developer.mozilla.org/en-US/docs/Web/Reference).
* Javascript: Code Snipper taken from [StackOverflow](https://stackoverflow.com/questions/11866910/how-to-force-a-html5-form-validation-without-submitting-it-via-jquery) and modified to force a HTML5 Form Validation prior to form submission/modal pop up.
* CSS: An understanding of radial gradients was obtained from [Quirksmode](https://www.quirksmode.org/css/images/position.html).
* CSS: Guidance on removing additional spacing around Span elements was obtained from [StackOverflow](https://stackoverflow.com/questions/25667401/how-to-remove-the-space-between-two-span-tags).
* CSS: Code snippet taken from [CodePen](https://codepen.io/jpost-design/pen/EKZLzK) and modified to obtain a "glow button" effect.
* CSS: Code snippet taken from [CSS-Tricks](https://css-tricks.com/almanac/properties/b/box-shadow/) and modified to obtain a "double shadow" effect on "glow button" effect.
* CSS: Code snippet taken from [Hover.css](https://ianlunn.github.io/Hover/) for Hover Grow effect on links.
* CSS: Guidance on fixing Flex compatibility on IE11 obtained from [StackOverflow](https://stackoverflow.com/questions/21600345/flexbox-and-internet-explorer-11-displayflex-in-html).
* CSS: Guidance on changing placeholder text colour obtained from [W3Schools](https://www.w3schools.com/howto/howto_css_placeholder.asp).
* CSS: Code snippet taken from [StackOverflow](https://stackoverflow.com/questions/32265322/css-length-of-border-bottom) and modified for the 50% border on table cells.
* CSS: Guidance on fixing cell-padding collision with 50% border effect taken from [StackOverflow](https://stackoverflow.com/questions/10077386/how-to-display-the-after-content-outside-element). 
* CSS: Code snipper taken from [StackOverflow](https://stackoverflow.com/questions/12115833/adding-a-slide-effect-to-bootstrap-dropdown) and modified to obtain a fluid Nav dropdown transition.

# Acknowledgements

---
