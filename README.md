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

* **Encourage and Allow User Engagement**
    * Every page must allow a user to engage with the business.
    * The ability to engage is clear and stands out from other interactive aspects of the site.
    * Engagement is done through completing an simple and intuitive enquiry form.

* **Convey Ethos/Purpose**
    * Outline key services on home page.
    * Present further details on key services on separate page.
    * Make sure the details provided are important, sellable, and merit being detailed in isolation.
    * Make the descriptions bite sized and easy to digest.

* **Instil User Confidence**
    * The branding is clear, distinguishable, and recognisable.
    * Relate to and refer to the customer.
    * The website is minimalistic where necessary, intuitive, and user friendly. 

* **Present Cost Approach**
    * Communicate that the computer is customer budget based.
    * Be transparent about cost of additional services and peripherals. 
    * Provide detailed yet convincing breakdown of cost of service

### Functional Requirements

* **Navigation bar (Navbar)**
Each page has a sticky navbar at the top. This provides a consistent layout and structure as the user navigates through the site. The logo is always centred, and is always the most prominent header on each page. On large devices, the navbar 
has a second row underneath the logo which displays the active page the user is on,  On mobile devices, the navigation links are hidden,
and activated with a "sandwich" (which is a server icon), which draw the links between the page logo and the current page's sub-heading. The consistent, simple, and intuitive navigation system would contribute to instilling user trust, and allows
users to reach all aspects of the site which aid the satisfaction of all user-stories.

* **Footer**
Each page has a static footer at the bottom. This provides links Github, a second and more aestheticically stimulating link to the enquire page, and links to socials. The same background effect is used on the footer, but with the gradient
reversed, to provide an 'enclosed' look. Once again, this effect is subtle yet effective, and intends to produce a strong positive emotional response in order to instil trust in the user. The Enquire button is designed to grab the user’s attention, 
with a continuous glowing effect. This effect encourages the user to interact with the link, and therefore engage with the website. On mobile devices, the footer is similar in layout, with the only significant change being font size and positioning of the social links 
for a more user-friendly interface. As discussed, on the "Enquire" page, as opposed to having a second "Enquire" button on the bottom, this button has been converted into a "Submit" button, which removes the redundancy of a recursive link, 
and implements a function which is relevant and fits the contextual flow of the page. 

* **Price Table**
A price table is available on multiple pages of the site. It provides the user with a full breakdown of the different tiers of service packages they can opt into when requesting a quote for their computer. The cost and benefits of these packages 
is explicitly clear, and a full screenreader-only description is available which explains which benefits are included in which package, and their associated costs. Each tier benefit contains a tooltip to provide additional information on the service included. 
On Modals, the tooltips are on the text of the benefits themselves,  while on the Desktop "Enquire" page, small self-descriptive icons sit at the end of each benefit that provide this tooltip.

* **Enquiry Form**
The enquiry form allows the user to provide a small amount of personal details, and information regarding their requirements, in order to engage with the company and to receive a specification in response. 
Each field is categorised and grouped into the relevant fieldset, with each individual field being clearly separated and labelled. Out of 8 fields, 6 are required, and 2 are optional. The user must supply their name, email address, and phone number. 
They must then decide what type of computer they want, and their budget. In all viewports, the "Budget" field contains a tooltip which explicitly states the budget stated excludes the cost of the service package requested, and any potential optional peripherals to be quoted.
The user can at this stage decide to opt in to be quoted for an optional peripheral to be paired with their computer. The user must then select a package tier, and then optionally provide more 
information regarding their requirements if they should wish to do so. Initially, a colour picker was implemented into the form, however this resulted in quite an arduous addition;  considering this aspect of the engagement is essentially just a request for an initial quote,
this would have added nothing to the initial enquiry and added an additional unneccessary step towards requesting a quote, and was therefore removed. It was also found on mobile devices that the colour picker was limited, and therefore could have easily frustrated the user. 

* **Modals**
Modals are implemented into the site to provide an additional degree of interactivity. They are also present to layer content where neccessary, so as to not compress to information into a single location. The modals either contain the price table, or a thank you message 
once the user has completed and submitted the enquiry form. 

* **Viewport Control**
Where possible, the pages contain all information within the user's viewport. Where this is not possible on very small mobile devices, or on the enquiry page, an intuitive navigation system has been implemented to allow for only the content
of the page (not the headings) to be scrollable. By presenting all information on the screen at once, due to having a minimalistic design, this should produce a powerful emotional response from the user, as if the content had been designed for their specific needs,
and would ensure that no information is missed.  

* **Responsive Layout and design**
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
* The project uses [Google Fonts](https://fonts.google.com/) for custom web-fonts.
* The project's images were compressed via [tinyjpg](https://tinyjpg.com/) to be appropriately sized for web content.
* The project's accessibility was assesed via WebAim's [W.A.V.E](https://wave.webaim.org/) and Google Chrome's [Lighthouse](https://developers.google.com/web/tools/lighthouse).
* The project used Toptal's [Colorfilter](https://www.toptal.com/designers/colorfilter/) to assess how colour-blind-friendly the site was.
* The project's contract ratio was assessed using WebAim's [Contract Checker](https://webaim.org/resources/contrastchecker/)
* The project's cross-browser compatability was enhanced using [Autoprefixer.io](https://autoprefixer.github.io).
* The project's HTML was validated using [W3C HTML Markup Validator](https://validator.w3.org/).
* The project's CSS was validated using [W3C Jigsaw CSS Validator](https://jigsaw.w3.org/css-validator/).
* The project's Bootstrap was validated using [Bootlint](https://github.com/twbs/bootlint).

---

# Testing

## Testing User Stories

The User Stories were evaluated in conjunction with the Non-Functional Requirements and relevant Conditions of Satisfaction.

**As a visitor to the website, I want to know what your company does.**

On arrival to the homepage, the user is presented with the name of the company, the three main selling points of company, a _"call to action"_, and strong, relevant, and colourful imagery. The colour scheme adopted in the Logo/Header is consistent with
the content of the site, the images, and the footer's text, icons, and style. Three sub-headings are visible on the homepage which are extremely succinct, yet clearly convey the ethos and purpose of the business. Each subheading has a relevant icon to 
give users an emotional response to each subheading's content. The _"call to action"_  text on the home page also addresses the user, and clearly gives instructions as to how to enage with company and website on a "no-risk" basis, and what they will achieve from doing so,
further emphasising the ethos and company intention. The concept and interface is simple, easy to use and navigate, and is responsive on all devices and viewports. Viewing this page on a mobile device stacks the content in order of most importance from top to bottom.

> Non-Functional Requirement
> * Convey Ethos/Purpose 
>   * Outline key services on home page &#x2611;
> * Instil User Confidence 
>   * The branding is clear, distinguishable, and recognisable &#x2611;
>   * Relate to and refer to the customer &#x2611;
>   * The website is minimalistic where necessary, intuitive, and user friendly &#x2611;
> * Present Cost Approach 
>   * Communicate that the computer is customer budget based &#x2611;
> * Encourage and Allow User Engagement 
>    * Every page must allow a user to engage with the business &#x2611;

**As a potential customer, I want to know what services you provide.**

Once the user has engaged with the site, in the knowledge of the primary purpose of the business, they can proceed to make an enquiry through the Navbar, or through the footer link. However, if they require further information with regards to the services provided 
by the business, they have access to the _"About"_ page, which is the next contextually relevant link within the Navbar. This page offers further insight into the 3 selling points of the website/company. While maintaining the websites minimalistic design, 
each section offers a succinct amount of detail about each selling point, in the same informational order as displayed in the index page. Each section contains a relevant image, which once again dynamically resizes depending on viewport. These images are not available 
on mobile devices; while they undoubtedly produce a powerful emotional response, it was decided that the explicit and succinct nature of the text means displaying all of this information on a single viewport on smaller devices was much more effective 
(as per the viewport control discussion above) than allowing a user to scroll to view all content. For all viewports, the user can interact with a "Service Package" link which opens up a modal for the user, which displays the Package Table. 

> Non-Functional Requirement
>   * Encourage and Allow User Engagement 
>       * Every page must allow a user to engage with the business &#x2611;
>       * The ability to engage is clear and stands out from other interactive aspects of the site &#x2611;
>    * Convey Ethos/Purpose 
>        * Present further details on key services on separate page &#x2611;
>        * Make sure the details provided are important, sellable, and merit being detailed in isolation &#x2611;
>        * Make the descriptions bite sized and easy to digest &#x2611;
>    * Instil User Confidence 
>        *  The branding is clear, distinguishable, and recognisable &#x2611;
>        * Relate to and refer to the customer &#x2611;
>        * The website is minimalistic where necessary, intuitive, and user friendly &#x2611;

**As an interested customer, I want to know how much the service costs.**

All pages on the site make reference to the pricing structure of the business. The _"Home"_ page makes simple reference to it, the _"About"_ page elaborates on this pricing structure and presents users with the Package Table, and the _"Enquire"_ page provides 
both the Package Table and a tooltip on the Budget section of the form to explain the additional packages/peripherals are excluded from the cost of the customer's budget. On the _"Enquire"_ page, on large viewports, the user is presented with the package table 
next to the enquiry form. On tablets and mobile devices, this package table is hidden, and users are presented with a link to view package details (in the same style as that on the about page) via a modal. The colour design and structural layout of 
the Package Table is representative to that of the rest of the site to maintain consistency.  

> Non-Functional Requirement
>    * Encourage and Allow User Engagement 
>        * Every page must allow a user to engage with the business &#x2611;
>        * The ability to engage is clear and stands out from other interactive aspects of the site &#x2611;
>   * Present Cost Approach 
>        * Communicate that the computer is customer budget based &#x2611;
>        * Be transparent about cost of additional services and peripherals &#x2611;
>    * Instil User Confidence 
>        *  The branding is clear, distinguishable, and recognisable &#x2611;
>        * Relate to and refer to the customer &#x2611;
>        * The website is minimalistic where necessary, intuitive, and user friendly &#x2611;

**As a convinced customer, I want to be able to easily make an enquiry.**
    
The Enquire page allows a user to engage with the website through filling in a simple form. It is therefore, ultimately, the most important page on the site. It is is accessible within the Navbar, and within the footer of both the _"Index"_ page and _"About"_ page. 
In the footer of the enquiry page, the "enquiry" link is replaced with a "submit" link. The formatting and style are the same as the Enquire link (as seen in the Home page and About Page) to ensure consistency; it was considered that this may obfuscate the user, 
and the intention of this particular button, as it may not initially be clear that the usage of the persistent button has changed, but the alternative to this was to retain a recursive "enquiry" link at the bottom of the enquiry page, and to have a separate "submit" 
button at the bottom of the enquiry form. It was decided that the best solution to this was to replace the enquiry button with the submit button; this also works best for the mobile layout. Form submission is validated prior to submission, 
and users are alerted to any incomplete fields if necessary. On valid completion of the form, the user is presented with a thank you modal, informing them of the next steps, and the form is reset.

> Non-Functional Requirements
>    * Encourage and Allow User Engagement 
>        * Engagement is done through completing an simple and intuitive enquiry form &#x2611;
>        * The ability to engage is clear and stands out from other interactive aspects of the site &#x2611;
>    * Present Cost Approach 
>        * Communicate that the computer is customer budget based &#x2611;
>        * Be transparent about cost of additional services and peripherals &#x2611; 
>    * Instil User Confidence 
>        *  The branding is clear, distinguishable, and recognisable &#x2611;
>        * Relate to and refer to the customer &#x2611;
>        * The website is minimalistic where necessary, intuitive, and user friendly &#x2611;

## Functional Testing

Testing the Functional Requirements was completed manually, with each feature being tested as described below. 

1. Nav brand

2. Footer

3. Index

4. About

5. Enquire

6. Modals

7. Form Submission

8. Responsive/Viewport

## Browser Testing

Cross-Browser compatability was tested via applying the methodology described above within each browser detailed below.

1. Chrome/Firefox

2. Internet Explorer

3. Safari

## Automated Testing

Automated testing was completed via third party applications, in order to assess the markdown syntax and logical application of the languages/frameworks used. 

1. **[W3 Markup Validation](https://validator.w3.org/) - HTML Validation**
    * The project's HTML was validated using the automated W3 Markup Validator. 
    * The only error identified using this validator was the following: 
        * `Error: The element a must not appear as a descendant of the button element`
    * When the 'glass-button' and 'button-glow' classes were initially implemented, they were designed to house an anchor tag, so as to use the button as a link.
    * An issue was identified prior to the validation, in that when tabbing through the site, it caused the buttons to be highlighted twice.
    * In order to resolve this issue, and to fix the validation error, the glass-button and glass-button>a selector classes were merged, and applied to anchor tags only.
    * This resulted in the same visual effect as intended, prevented the "double tabbing", and resolved the HTML Validation Error.

2. **[W3 Jigsaw](https://jigsaw.w3.org/css-validator/) - CSS Validation**
    * The project's CSS was validated using the automated W3 Jigsaw Validator.
    * The only error identified using this validator was the following:
        * `negative values are not allowed : 0 0 -10px rgb(228, 30, 30, 0.9), inset 0 0 0 rgba(228, 30, 30, 0.9);` 
    * Initially, when debugging this validation error, I identified that the CSS worked as intended, and responded to the negative values.
    * I tested similar code on the validator, found on [CSS-Tricks](https://css-tricks.com/almanac/properties/b/box-shadow/):
        * `box-shadow:   inset -5px -5px 10px blue;`
    * This code did not throw any validation errors, therefore I determined this was a syntactical error, and amended the code as follows:
        * `0 0 -10px 0 rgb(228, 30, 30, 0.9), inset 0 0 0 rgba(228, 30, 30, 0.9)`
    * This produced an identical effect, and passed the validation.

3. **Bootstrap Linter**
    * Re-run and assess.

## Significant Bugs

**Development bugs:**

1. **Making image fully responsive and aesthetically logic for different viewports**
    * Started with absolute positioning of image in bottom right, but the image would sometimes overlap with content and required excessive viewport configurations.
    * Attempted finite height definition in px, however this was a similar outcome to the above, whereby it required consideration of "Min-height" as well as "Min-width" for viewports.
    * Attempted to add both the hero image and the "sales pitch" to a row, with Bootstrap col's, and to set the hero-image height in Viewport Height. However, this required the explicit definition of Div sizes, and image % size, which became cumbersome and less fluid.
    * Set the pages "content" size to viewport-px (height of header+footer), then set all sections of the page to be in Flex format, with the appropriate layout definitions being amended on each viewport. This allowed fully dynamic image sizing, and div resizing, for the size of the page, regardless of device height/width.
    * This concept was then implemented into the about and enquire pages. 

2. **Clicking the modal button on the Enquire page attempted to submit the form, highlighting incomplete fields on mobile, and triggering "this field needs completing".**
    * When initially implementing the Modal interface, a button was used to allow the user to bring up the packages modal. This issue was resolved by adding onclick="return false;" in button field. 
    * When adding the link to the package model in the about page, it was decided that a button was too obtrusive for the context of the layout, and therefore a customer hyperlink format was added. 
    * This also allowed the "Enquire" and "submit" button to maintain consistent, to achieve an aligned goal, without bleeding this feature onto other concepts. 

3. **When the content of the 'benefits' section of the table overflowed, the corresponding 'tick' boxes generated additional padding on the bottom of the cell, which conflicted with the 50% border concept implemented**
    * The issue came from "vertical-align: center;", as this uses padding to align the contents. Due to the nature of the ::after 50% border, this caused the border to sit on top of the padding, as opposed to the bottom of the cell as intended.
    * Solution: Set the td/th tags with position: relative;, and set the pseudo element to position: absolute;, then remove any padding from the pseudo element, and move that padding to the table element. 
    * https://stackoverflow.com/questions/10077386/how-to-display-the-after-content-outside-element

4. **Tooltips were being displayed on top of the text in mobile view, despite having "data-placement: right".**
    * This was resolved by using "data-placement: left", even though it wasn't clear why.

5. **Issue with file locations from CSS when pushing to github pages**
    * When the site was published to github pages, the links to internal pages were not working, and the images were not being pulled from the assets folder.
    * The error was caused by the internal links being prefaced with "/". Once removed, the links worked appropriately.
    * The links to images in the CSS file were defined as: "/assets/images/...". Therefore, when using Gitpod, the links would work appropriately. 
    * Given how the page is hosted on github, the assets were being searched for in: "github.io/assets/images/..."
    * This was resolved by using a relative file path, and removing the assets/ subdirectory, as such: "./images/...".

6. **Internet Explorer incompatibility**
    * Flexbox

7. **Users informed me that on some mobile devices the Navbar disappears (akin to safari) after click on a form input or pressing submit**
    * On some mobile devices, clicking on an input form "zooms in" on the input field. Alternatively, submitting an incomplete form "zooms in" on the input form not complete.
    * This obfuscates the layout of the page (fixed header with embedded scrollable div), requiring users to zoom out to use the page correctly.
    * While this doesn't necessarily break the layout of the page, it would require the user to zoom out in order to use the site correctly, creating a poor user experience.
    * This was fixed by adding: minimum-scale=1, maximum-scale=1 to the meta tag of the enquiry page.

**Other technical difficulties:**

1. **Github Commit Merge** 
    * On 27th October, I accidentally merged multiple git commits (df2b72005f9506c70c5d58fcb9964631462d7555/a8190a91b29cb1d4c3258e5d0f684390113bc646). While I researched how to undo the push, I was aware this would result in all of these changes being combined, and I wasn't fully comfortable 
    continuing with this as I didn't want to lose any more progress/commits. Accepted this single merge was an error, and moved on and learned from this. 

# Deployment
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
