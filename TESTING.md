# Hard Drivers - Testing Documentation

The Main README documentation can be found under [README.md](README.md)

[View website on Github Pages](https://bak2k3.github.io/hard-drivers/index.html)

## Testing User Stories

The User Stories were evaluated in conjunction with the Non-Functional Requirements and relevant Conditions of Satisfaction.

**As a visitor to the website, I want to know what your company does.**

On arrival to the homepage, the user is presented with the name of the company, the three main selling points of company, a _"call to action"_, and strong, relevant, and colourful imagery. The colour scheme adopted in the Logo/Header is consistent with
the content of the site, the images, and the footer's text, icons, and style. Three sub-headings are visible on the homepage which are extremely succinct, yet clearly convey the ethos and purpose of the business. Each subheading has a relevant icon to 
give users an emotional response to each subheading's content. The _"call to action"_  text on the home page also addresses the user, and clearly gives instructions as to how to engage with company and website on a "no-risk" basis, and what they will achieve from doing so,
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

All pages on the site refer to the pricing structure of the business. The _"Home"_ page makes simple reference to it, the _"About"_ page elaborates on this pricing structure and presents users with the Package Table, and the _"Enquire"_ page provides 
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
>        * The branding is clear, distinguishable, and recognisable &#x2611;
>        * Relate to and refer to the customer &#x2611;
>        * The website is minimalistic where necessary, intuitive, and user friendly &#x2611;

**As a convinced customer, I want to be able to easily make an enquiry.**
    
The Enquire page allows a user to engage with the website through filling in a simple form. It is therefore, ultimately, the most important page on the site. It is accessible within the Navbar, and within the footer of both the _"Index"_ page and _"About"_ page. 
In the footer of the enquiry page, the "enquiry" link is replaced with a "submit" link. The formatting and style are the same as the Enquire link (as seen in the Home page and About Page) to ensure consistency; it was considered that this may obfuscate the user, 
and the intention of this particular button, as it may not initially be clear that the usage of the persistent button has changed, but the alternative to this was to retain a recursive "enquiry" link at the bottom of the enquiry page, and to have a separate "submit" 
button at the bottom of the enquiry form. It was decided that the best solution to this was to replace the enquiry button with the submit button; this also works best for the mobile layout. Form submission is validated prior to submission, 
and users are alerted to any incomplete fields if necessary. On valid completion of the form, the user is presented with a thank you modal, informing them of the next steps, and the form is reset.

> Non-Functional Requirements
>    * Encourage and Allow User Engagement 
>        * Engagement is done through completing a simple and intuitive enquiry form &#x2611;
>        * The ability to engage is clear and stands out from other interactive aspects of the site &#x2611;
>    * Present Cost Approach 
>        * Communicate that the computer is customer budget based &#x2611;
>        * Be transparent about cost of additional services and peripherals &#x2611; 
>    * Instil User Confidence 
>        * The branding is clear, distinguishable, and recognisable &#x2611;
>        * Relate to and refer to the customer &#x2611;
>        * The website is minimalistic where necessary, intuitive, and user friendly &#x2611;

## Functional Testing

Testing the Functional Requirements was completed manually, with each feature being tested as described below. 

**Navigation bar (Navbar)**

Unless specifically stated, all functionality for the Navbar was tested on every page.

* Visit all links within the navbar in every possible order to ensure they are functional and route correctly:
    * Home -> About // Home -> Enquire 
    * About -> Home // About -> Enquire
    * Enquire -> Home // Enquire -> About
* Click the main 'logo' on each page, to ensure it diverts the user back to the homepage.
* Ensure the height of the Navbar is a consistent height across each page. 
* Ensure Navbar elements (logo/links) maintain their position through navigation of the site. 
* Ensure all internal navigational links are not opened externally.
* Ensure the relevant active link is coloured accordingly depending on user's location on site.
* On small vertical viewports, ensure the Navbar maintains its position (i.e sticky) when the page's Viewport Control is scrollable (on the y-axis).
* When adjusting the horizontal viewport, ensure the "logo" and links reposition themselves dynamically to maintain their central position on the page.
* On large horizontal viewports, ensure the Navbar's background image zooms in/out accordingly when increasing/decreasing horizontal viewport. 
* On all viewports, ensure the Navbar's radial gradient maintains its appearance over the background image, and remains in a static position (regardless of background image's zoom effect).
* On small horizontal viewports, ensure the Navbar collapses, hides the row of navigation links, and provides the sandwich icon.
* On small horizontal viewports, ensure the "logo" changes to the 'stacked' design.
* When the collapsed Navbar is displayed, ensure that interacting with the sandwich icon displays or hides the dropdown navigational links appropriately.
* When the collapsed Navbar is displayed, ensure the links (when displayed) are aligned centrally, underneath the 'logo'.
* When the collapsed Navbar is displayed, ensure the links (when displayed) move dynamically when adjusting the horizontal viewport size (in either direction). 
* When the collapsed Navbar is displayed, ensure the dropdown (when displayed) does not close when the user interacts with another part of the current page.
* When the collapsed Navbar is displayed, ensure the dropdown does not overflow onto the Viewport Control/content of the page.
* Ensure the navigation links display the appropriate effects when hovered (desktop) over:
    * The link produces the 'grow' effect, and changes from inactive (white) to active (red).
    * If the link is already in an active state, it only displays the grow effect and does not change colour. 
* Ensure tabbing (desktop) navigates the user through the logical flow of the site:
    * Header --> Home --> About --> Enquire
* Ensure the navigation links display the appropriate effects when touched (mobile/tablet):
    * The link would 'grow', and change from inactive (white) to active (red) where applicable.
* Ensure screen readers read the text in the correct order:
    * Logo/Title --> Home --> About --> Enquire

**Footer**

Unless specifically stated, all functionality for the Footer was tested on every page.

* On each page, ensure the Github / Social links open to the correct webpage, and are opened externally.   
* On the "Home" and "About" pages, ensure the "Enquire" button correctly routes the user to the "Enquire" page.
* On the "Enquire" page, ensure the "Enquire" button states "Submit" - Functionality testing discussed on the "Enquiry Form" section. 
* Ensure on page load the "Enquire/Submit" button maintains its persistent 'glow' effect.  
* Ensure the Footer appearance is consistent across all pages, and maintains the same height. 
* Ensure Footer elements (Github - Enquire/Submit - Socials) maintain their position through navigation of the site.
* On large horizontal viewports, ensure the Footer's background image zooms in/out accordingly when increasing/decreasing horizontal viewport. 
* On all viewports, ensure the Footer's radial gradient maintains its appearance over the background image, and remains in a static position (regardless of background image's zoom effect).
* On all viewports, ensure the Enquire/Submit button's 'glow' effect does not overflow onto the Viewport Control/content of the page. 
* When adjusting the horizontal viewport, ensure the Footer elements reposition themselves dynamically to maintain equal distance, and central position within their containers.
* When adjusting the horizontal viewport, ensure the Footer elements' font sizes adjust themselves appropriately.
* On small horizontal viewports, ensure the Social links stack themselves (2x2), and maintain their functionality. 
* Ensure no visual effects are produced when the Github / Social Links are hovered over with the mouse (desktop).
* Ensure tabbing (desktop) navigates the user through the visual flow of footer:
    * Github --> Enquire/Submit --> Facebook --> Twitter --> Instagram --> Linkedin.
* Ensure hovering (desktop) over the Submit/Enquire button produces the 'grow' effect, and changes from white to red.
* Ensure no visual effects are produced when the Github / Social links are touched (mobile/table).
* Ensure the Enquire/Submit button produces the 'grow' effect, and changes from white to red when touched (mobile/table).
* Ensure screen readers read the text in the correct order:
    * Github --> Enquire/Submit --> Facebook --> Twitter --> Instagram --> Linkedin.

**Price Table**

1. Modal Design (About/Enquire Pages):
    * Ensure the price of each tier is clear, and what benefits included in the respective tier is clear. 
    * Ensure the table is displayed centrally, and that all text is clear and visible.
    * Ensure on larger viewports, the table fits comfortably on the page, and does not require unnecessary scrolling.
    * Ensure on smaller vertical viewports, the table is scrollable on the y axis.
    * Ensure the user can interact with each 'benefit':
        * Ensure that on hover (desktop), the correct tooltip is displayed, and that the tooltip displays to the right of the relevant text, and that the text is legible. 
        * Ensure that on click (desktop)/touch (mobile/tablet), the correct tooltip is displayed, and persists until either the user clicks/touches a different benefit, or clicks/touches elsewhere.
        * Ensure the user can tab (desktop) through each tooltip, in logical order, from top to bottom.
    * Ensure screen readers read the text within the table in the correct order:
        * Heading --> Price.
        * Benefit --> Benefit Description --> In what packages the benefit is included. 

2. Full-Screen Design (Enquire Page):
    * Ensure the price of each tier is clear, and what benefits included in the respective tier is clear. 
    * Ensure the table size is equally proportionate to the size of the enquiry form.
    * Ensure the width of the surrounding 'Package Tiers' fieldset adjusts dynamically when adjusting the horizontal viewport.
    * Ensure the table is viewable on smaller vertical viewports, and can scroll through the content appropriately.
    * Ensure the user can interact with each `?` icon tooltip:
        * Ensure that on hover (desktop), the correct tooltip is displayed, and that the tooltip displays to the right of the relevant text, and that the text is legible. 
        * Ensure that on click (desktop)/touch (mobile/tablet), the correct tooltip is displayed, and persists until either the user clicks/touches a different benefit, or clicks/touches elsewhere.
        * Ensure the user can tab (desktop) through each tooltip, in logical order, from top to bottom.
    * Ensure screen readers read the Package table before the Enquire table, and that the table itself is read immediately after the heading.
    * Ensure screen readers read the text within the table in the correct order:
        * Heading --> Price.
        * Benefit --> Benefit Description --> In what packages the benefit is included. 

**Enquire Form**

* Ensure each input is correctly grouped into its relevant fieldset.
* Ensure the Legend for each fieldset is clear and distinguishable.
* Ensure each input's label is clear and distinguishable, and highlights the correct field on click (desktop)/touch (mobile/tablet).
* Ensure the form's size is equally proportionate to the size of the Package Table.
* Ensure the form is viewable on smaller vertical viewports, and can scroll through the content appropriately.
* Ensure the width of the fieldsets and form inputs adjust dynamically when changing the horizontal viewport.
* Ensure tabbing through the Enquire form correctly navigates through the form:
    * Full Name --> Email Address --> Phone Number --> Type (Option 1) --> Optional Peripherals (Option 1) --> (Option 2) --> (Option 3) --> Budget Tooltip --> Budget Input --> Your Package (Option 1) --> Your Request.
    * See known bugs below for discussion on tabbing from the 'Your Request' field to the 'Submit' button.
* Ensure on any invalid input entry, the default browser validation messages are presented. 
* Ensure Full Name field accepts any value, but requires at least one character to be deemed valid.
* Ensure Email Address field does not accept input that is not in the format of an email address.
    * On entry of an invalid email address, the default email validation message appears.
* Ensure Phone Number field only accepts numbers (plus an optional + at the beginning).
    * On entry of an invalid telephone number, the title is presented to the user: `Valid numbers only, with no spaces`.
* Ensure Type selection is required for valid submission, and that both cannot be selected.
* Ensure the form can be submitted with none of the peripherals selected.
* Ensure the budget tooltip is appropriately displayed on hover/click (desktop) or touch (mobile/tablet).
* Ensure the form cannot be submitted without a valid budget value entered.
    * Values less than 1 are presented with `Value must be greater than 0`.
    * Values greater than 100,000 are presented with `Value must be less than 100000`.
* Ensure Package selection is required for valid submission, and that all three cannot be selected.
* Ensure on valid form submission that the Thank You model is presented, and that the form is cleared in full.  
* Ensure screen readers read through the Enquire form in the correct sequence:
    * Your Details (legend) --> Full Name --> Email Address --> Phone Number 
    * Your Computer (legend) --> Type --> Desktop --> Laptop 
    * Optional Peripherals --> Monitor --> Keyboard --> Mouse 
    * Budget --> Budget Tooltip --> Budget input 
    * Your Package (legend) --> Your Package --> Bronze --> Silver --> Gold
    * Your Request (legend) --> Leave a note for your Hard Driver (optional)

**Modals**

These tests applied to both the Price Table (About/Enquire) and Thank You (Enquire) modals:

* Ensure the modal is displayed centrally, with the appropriate Header / Body / Footer.
* Ensure the modal's "close" button functions as intended, and closes the modal.
* Ensure the modal can be dismissed by clicking (desktop) of touching (phone/tablet) out of the modal area.
* Ensure pressing tab navigates appropriately through the content as intended.
* Ensure pressing tab at the end of the content highlights the "close" button:
    * Ensure pressing enter subsequently closes the modal.
* Ensure pressing the escape key closes the modal.
* Ensure the content of the modal fits appropriately, and can be scrolled on the y axis if required.
* Ensure screen readers can read the content of the modal appropriately, and can read the "close" button.

**Viewport Control**

1. General:

2. Mouse and Keyboard Based Devices:

3. Touch Based Devices:

**Responsive Layout and design**

1. General:


## Browser Testing

Cross-Browser compatibility was tested via applying the methodology described above within each browser detailed below.

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
    * Set the pages "content" size to viewport-px (height of header + footer), then set all sections of the page to be in Flex format, with the appropriate layout definitions being amended on each viewport. This allowed fully dynamic image sizing, and div resizing, for the size of the page, regardless of device height/width.
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

8. **Tooltips**
    * Multiple implementations of the tooltip were tested in order to allow the user to hover on desktop, and both click/touch to allow a persisent tooltip to appear in the Price Table.
    * The current implementation contains `tabindex=0`,which allows users to tab through the benefits and display their relevant tooltip accordingly. 
    * However, this solution results on the tooltip persisting on 'click', and cannot be 'unclicked'. The user must either click/tab to another tooltip or click elsewhere on the page to remove
    the tooltip. 
    * While this does not neccessarily diminish the user experience, it is a bug that I would prefer to remove, however I am aware this requires additional knowledge of javascript. 

9. **Tabbing through the Enquire Menu**
    * When the user reaches the "Your Request" field of the Enquire Form, they need to tab twice, to bypass the "Github" icon, in order to reach the submit button. 
    * Setting `tabindex=1` to the submit button causes this item to be selected first when tabbing through the document, and results in the user having to press tab more times to reach the submit button.
    * Given the final input field is a "Free Text" box, pressing the enter button on this form generates a new line, as opposed to most other form inputs in which enter submits the form.
    * A solution to this would be to add set `tabindex=3` to all elements prior to the submit button, `tabindex=2` on the submit button, and `tabindex=1` on the rest of the footer icons.
    * This solution seems long winded, and would potentially result in unexpected results and goes against the recomendation to [not use tabindex=1+](https://developer.paciellogroup.com/blog/2014/08/using-the-tabindex-attribute/#:~:text=When%20tabindex%20is%20set%20to,it%20in%20the%20tab%20order.).
    * A solution to this could also be implemented in Javascript, however additional experience would be needed to attempt this.

**Other technical difficulties:**

1. **Github Commit Merge** 
    * On 27th October, I accidentally merged multiple git commits (df2b72005f9506c70c5d58fcb9964631462d7555/a8190a91b29cb1d4c3258e5d0f684390113bc646). While I researched how to undo the push, I was aware this would result in all of these changes being combined, and I wasn't fully comfortable 
    continuing with this as I didn't want to lose any more progress/commits. Accepted this single merge was an error, and moved on and learned from this.
