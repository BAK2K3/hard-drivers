# Hard Drivers - Testing Documentation

The Main README documentation can be found under [README.md](README.md)

[View website on GitHub Pages](https://bak2k3.GitHub.io/hard-drivers/Home.html)

# Table of contents

>1. [User Story Testing](#user-story-testing)
>2. [Feature Testing](#feature-testing)
>3. [Browser Testing](#browser-testing)
>4. [Automated Testing](#automated-testing)
>5. [Significant Bugs](#significant-bugs)
>6. [Other Technical Difficulties](#other-technical-difficulties)

# User Story Testing

## As a visitor to the website, I want to know what your company does.

**On arrival to the _"Home"_ page, the user is presented with the name of the company, the three main selling points of company, a _"call to action"_, and strong, relevant, and colourful imagery.**
* The colour scheme adopted in the Logo/Header is consistent with the content of the site, the images, and the footer's text, icons, and style. 
* Three sub-headings are visible on the _"Home"_ page which are extremely succinct, yet clearly convey the ethos and purpose of the business. 
* Each subheading has a relevant icon to give users an emotional response to each subheading's content. 
* The _"call to action"_  text on the _"Home"_ page also addresses the user, and clearly gives instructions as to how to engage with company and website on a "no-risk" basis, and what they will achieve from doing so,
further emphasising the ethos and company intention. 
* The concept and interface is simple, easy to use and navigate, and is responsive on all devices and viewports. Viewing this page on a mobile device stacks the content in order of most importance from top to bottom.

## As a potential customer, I want to know what services you provide.

**If a user requires further information with regards to the services provided by the business, they have access to the _"About"_ page, which is the next contextually relevant link within the Navbar.**
* This page offers further insight into the 3 selling points of the website/company. 
* While maintaining the websites minimalistic design, each section offers a succinct amount of detail about each selling point, in the same informational order as displayed in the Home page.
* Each section contains a relevant image, which once again dynamically resizes depending on viewport, however these images are not available on small horizontal viewports, emphasising the content rather than imagery.

## As an interested customer, I want to know how much the service costs.

**All pages on the site refer to the pricing structure of the business.** 
* The _"Home"_ page makes general reference to cost.
* The _"About"_ page elaborates on this pricing structure and presents users with the "Service Package" link which opens up a modal for the user, which displays the Package Table in full.
* The _"Enquire"_ page provides both the Package Table, and a tooltip on the Budget section of the form to explain the additional packages/peripherals are excluded from the cost of the customer's budget. 
    * On the _"Enquire"_ page, on large viewports, the user is presented with the package table next to the Enquire Form. 
    * On smaller viewports, this package table is hidden, and users are presented with a link to view package details (in the same style as that on the _"About"_ page) via a modal. 
* The colour design and structural layout of the Package Table is representative to that of the rest of the site to maintain consistency.  

## As a convinced customer, I want to be able to easily make an enquiry.
    
**The Enquire page allows a user to engage with the website through filling in a simple form.** 

* The _"Enquire"_ page is ultimately the most important page on the site. It is accessible within the Navbar, and within the footer of both the _"Home"_ page and _"About"_ page.
* In the footer of the _"Enquire"_ page, the _"Enquire"_ link is replaced with a _"Submit"_ link. 
* The formatting and style are the same as the _"Enquire"_ link (as seen in the _"Home"_ page and _"About"_ Page) to ensure consistency. 
* Form submission is validated prior to submission, and users are alerted to any incomplete fields if necessary. 
* On valid completion of the form, the user is presented with a thank you modal, informing them of the next steps, and the form is reset.

# Feature Testing

_Testing the Features was completed manually, with each feature being tested as described below._ 

## Navigation bar (Navbar)

Unless specifically stated, all functionality for the Navbar was tested on every page.

* Visit all links within the navbar in every possible order to ensure they are functional and route correctly:
    * Home -> About // Home -> Enquire 
    * About -> Home // About -> Enquire
    * Enquire -> Home // Enquire -> About
* Click the main 'logo' on each page, to ensure it diverts the user back to the _"Home"_ page.
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

## Footer

Unless specifically stated, all functionality for the Footer was tested on every page.

* On each page, ensure the GitHub / Social links open to the correct webpage, and are opened externally.   
* On the _"Home"_ and _"About"_ pages, ensure the _"Enquire"_ button correctly routes the user to the _"Enquire"_ page.
* On the _"Enquire"_ page, ensure the _"Enquire"_ button states _"Submit"_ - Functionality testing discussed on the 'Enquire Form' section. 
* Ensure on page load the Enquire/Submit button maintains its persistent 'glow' effect.  
* Ensure the Footer appearance is consistent across all pages, and maintains the same height. 
* Ensure Footer elements (GitHub - Enquire/Submit - Socials) maintain their position through navigation of the site.
* On large horizontal viewports, ensure the Footer's background image zooms in/out accordingly when increasing/decreasing horizontal viewport. 
* On all viewports, ensure the Footer's radial gradient maintains its appearance over the background image, and remains in a static position (regardless of background image's zoom effect).
* On all viewports, ensure the Enquire/Submit button's 'glow' effect does not overflow onto the Viewport Control/content of the page. 
* When adjusting the horizontal viewport, ensure the Footer elements reposition themselves dynamically to maintain equal distance, and central position within their containers.
* When adjusting the horizontal viewport, ensure the Footer elements' font sizes adjust themselves appropriately.
* On small horizontal viewports, ensure the Social links stack themselves (2x2), and maintain their functionality. 
* Ensure no visual effects are produced when the GitHub / Social Links are hovered over with the mouse (desktop).
* Ensure tabbing (desktop) navigates the user through the visual flow of footer:
    * GitHub --> Enquire/Submit --> Facebook --> Twitter --> Instagram --> Linkedin.
* Ensure hovering (desktop) over the Submit/Enquire button produces the 'grow' effect, and changes from white to red.
* Ensure no visual effects are produced when the GitHub / Social links are touched (mobile/table).
* Ensure the Enquire/Submit button produces the 'grow' effect, and changes from white to red when touched (mobile/table).
* Ensure screen readers read the text in the correct order:
    * GitHub --> Enquire/Submit --> Facebook --> Twitter --> Instagram --> Linkedin.

## Package Table

1. Modal Design (_"About"_/_"Enquire"_ Pages):
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

2. Full-Screen Design (_"Enquire"_ Page):
    * Ensure the price of each tier is clear, and what benefits included in the respective tier is clear. 
    * Ensure the table size is equally proportionate to the size of the Enquire Form.
    * Ensure the width of the surrounding 'Package Tiers' fieldset adjusts dynamically when adjusting the horizontal viewport.
    * Ensure the table is viewable on smaller vertical viewports, and can scroll through the content appropriately.
    * Ensure the user can interact with each `?` icon tooltip:
        * Ensure that on hover (desktop), the correct tooltip is displayed, and that the tooltip displays to the right of the relevant text, and that the text is legible. 
        * Ensure that on click (desktop)/touch (mobile/tablet), the correct tooltip is displayed, and persists until either the user clicks/touches a different benefit, or clicks/touches elsewhere.
        * Ensure the user can tab (desktop) through each tooltip, in logical order, from top to bottom.
    * Ensure screen readers read the Package table before the Enquire Table, and that the table itself is read immediately after the heading.
    * Ensure screen readers read the text within the table in the correct order:
        * Heading --> Price.
        * Benefit --> Benefit Description --> In what packages the benefit is included. 

## Enquire Form

* Ensure each input is correctly grouped into its relevant fieldset.
* Ensure the Legend for each fieldset is clear and distinguishable.
* Ensure each input's label is clear and distinguishable, and highlights the correct field on click (desktop)/touch (mobile/tablet).
* Ensure the form's size is equally proportionate to the size of the Package Table.
* Ensure the form is viewable on smaller vertical viewports, and can scroll through the content appropriately.
* Ensure the width of the fieldsets and form inputs adjust dynamically when changing the horizontal viewport.
* Ensure tabbing through the Enquire Form correctly navigates through the form:
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
* Ensure screen readers read through the Enquire Form in the correct sequence:
    * Your Details (legend) --> Full Name --> Email Address --> Phone Number 
    * Your Computer (legend) --> Type --> Desktop --> Laptop 
    * Optional Peripherals --> Monitor --> Keyboard --> Mouse 
    * Budget --> Budget Tooltip --> Budget input 
    * Your Package (legend) --> Your Package --> Bronze --> Silver --> Gold
    * Your Request (legend) --> Leave a note for your Hard Driver (optional)

## Modals

These tests applied to both the Price Table (_"About"_/_"Enquire"_ Pages) and Thank You (_"Enquire"_ Page) modals:

* Ensure the modal is displayed centrally, with the appropriate Header / Body / Footer.
* Ensure the modal's "close" button functions as intended, and closes the modal.
* Ensure the modal can be dismissed by clicking (desktop) of touching (phone/tablet) out of the modal area.
* Ensure pressing tab navigates appropriately through the content as intended.
* Ensure pressing tab at the end of the content highlights the "close" button:
    * Ensure pressing enter subsequently closes the modal.
* Ensure pressing the escape key closes the modal.
* Ensure the content of the modal fits appropriately, and can be scrolled on the y axis if required.
* Ensure screen readers can read the content of the modal appropriately, and can read the "close" button.

## Viewport Control and Responsive Layout / Design

The testing for these sections were combined. While the implementation of these functions are different, and serve different purposes, the testing process for each section coincided with each other and therefore
have been discussed together.

* Ensure that on all pages, the header and footer remains static, and the content in-between (i.e the Viewport Control) is dynamic.
    * On all pages where content overflowed the Viewport Control, ensure the Viewport Control is scrollable on the y-axis.
    * On all pages where the content fits within the Viewport Control, ensure the positioning of the content remains proportionate, and scales equally and proportionately.
* Ensure that on mobile devices (or on small horizontal viewports), the Navbar collapses, providing a taller vertical Viewport Control. 
* Ensure that on all pages, the distance between the "Logo" and the individual page heading is equal, and the dropdown menu fits perfectly between the two. 
* Ensure that on the _"Home"_ and _"About"_ pages, the text size is adjusted by the specified amount on specified viewports:
    * Ensure that on all viewports, all text is visible and legible. 

**Home Page**:
* On all viewports, ensure the Feature Statements appears on its own row.
* On large viewports, ensure the 'call to action' statement and Hero Image are split into equal columns, with both items being aligned and justified centrally.
* On medium to small viewports, ensure the 'call to action' statement and Hero Image are stacked vertically.
* On all viewports, ensure the Hero Image resizes according to its container, does not overflow, and does not expand the size of the container. 
* On extra small vertical viewports, ensure the Hero Image is ultimately removed from view.

**About Page**:
* On all viewports, ensure that each section has its own horizontal row.
* On all viewports, ensure each section/row resizes proportionately (as can be seen from the respective size of the image on each row.)
* On medium to large viewports, ensure each section contains an image, which is fit horizontally to its container (allowing invisible overflow from the top and bottom of the image).
* on medium to large viewports, ensure the section images resize according to their respective container.
* Ensure that on small viewports, the images are removed from their respective section.
* Ensure that on small viewports, each section is proportionately spaced according to the size of the vertical viewport. 
* Ensure that on small viewports, if the section containers no longer have any space between them, that the Viewport Control is scrollable, and that all content is visible.   

**Enquire Page**:
* On large viewports, ensure the Package and Enquire sections are visible, and are container within equal column widths.
* On large viewports, ensure the Package and Enquire sections resize dynamically when the horizontal viewport is adjusted.  
* On medium to small viewports, ensure the Package section is removed from view, and the Enquire section fills the Viewport Control.
* On medium to small viewports, ensure the Enquire Form's fieldsets and input sections resize dynamically when the horizontal viewport is adjusted.
* On large viewports, ensure the `"Click here for further details!"` section within "your package" fieldset is hidden from view.
* On medium to small viewports, ensure the `"Click here for further details!"` section within "your package" fieldset added to view.
* On small viewports, ensure the positioning of the Enquire Form's labels are repositioned accordingly to a "stacked" view for better user viewing and control.  

# Browser Testing

Cross-Browser compatibility was tested via applying the methodology described above within each browser detailed below.

## Chrome/Firefox/Edge

All functionality worked as intended.

## Safari

As I do not have access to a device which is compatable with Safari, the above instructions were carried out by a friend using Mac OS and iOS. The only unintended effect produced was that described in the "bugs" selection below, regarding input zooming.

## Internet Explorer

 While the majority of functionality worked as intended for Internet Explorer 11, the following issues were identified:

 1. Flexbox:
    * Internet Explorer is [not entirely compatible](https://caniuse.com/flexbox) with Flexbox.
    * As such, when testing the responsive design of some pages, significant functionality breaking bugs were identified. 
    * These were present on the [Home page](https://res.cloudinary.com/bak2k3/image/upload/v1605367671/flex_index_ue1yfb.jpg) and on the [About page](https://res.cloudinary.com/bak2k3/image/upload/v1605367671/flex_about_m2u8xz.jpg).
    * One attempted fix for this was to define Flex fully as: `flex: 1 0 0;` for the relevant sections. 
    * This appears to have fixed some functionality, for instance when the page is full screen the website can be navigated without issue.
    * However, when adjusting the viewport of the aforementioned pages, the bugs re-appear and do not correct themselves when the viewport is reverted back to its original state.

2. Auto Margin and Text Center:
    * Multiple fixes were explored to resolve [auto-margin](https://stackoverflow.com/questions/31903734/ie11-flexbox-max-width-and-marginauto) issues and other [text alignment](https://stackoverflow.com/questions/49668656/css-text-align-center-not-working-on-ie11) issues.

Ultimately, however, I found myself removing core functionality of the website in order to adhere to the limitations of an out of date browser. While some functionality was restored for IE11 compatibility,
it was decided to focus on the capabilities of browsers which are current, up to date, and are capable of newer technology as opposed to removing functionality and limiting the capabilities of the website.

# Automated Testing

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

3. **[Google Lighthouse](https://developers.google.com/web/tools/lighthouse)** - Accessibility, Performance, Progressive Web Apps, and Best Practices Audit:

**Home**  
![Home Lighthouse Score](https://res.cloudinary.com/bak2k3/image/upload/v1605370521/Index-Lighthouse_fxhiv5.jpg)

**About**  
![About Lighthouse Score](https://res.cloudinary.com/bak2k3/image/upload/v1605370521/About-Lighthouse_nfogiq.jpg)

**Enquire**  
![Enquire Lighthouse Score](https://res.cloudinary.com/bak2k3/image/upload/v1605370521/Enquire-Ligthouse_seuuo4.jpg)

On further inspection, the main cause for the drop in Accessibility score for the _"Enquire"_ page was due to the implementation of `minimum-scale=1, maximum-scale=1` in the head of Enquire.html.

# Significant Bugs

1. **Making image fully responsive and aesthetically fluid for different viewports**
    * When first implementing the concept for the Viewport Control and the subsequent responsive images, I started with the Hero Image on the _"Home"_ page. 
    * I first attempted absolute positioning of image in bottom right, but the image would sometimes overlap content and overflow from its container.
    * I then attempted finite height definition in px, however this was a similar outcome to the above, whereby it required consideration of "Min-height" as well as "Min-width" for viewports.
    * I subsequently attempted to add both the hero image and the "call to action" text to a Bootstrap row, with respective columns, and to set the hero-image height in Viewport Height (vh). 
    However, this required the explicit definition of `<div>` height and width, and image % size, which became cumbersome, with strict and finite instructions, which resulted in a less fluid and responsive layout.
    * The solution to this was to set the page's 'Viewport Control' size to 100% height (minus the height of header + footer), then set all sections of the page to be in Flex format, with the appropriate layout definitions being amended on each viewport. 
     This allowed fully dynamic image sizing, and div resizing, for the size of the page, regardless of device height/width.
    * This concept subsequently became the 'Viewport Control' concept, and was then implemented into the _"About"_ and _"Enquire"_ pages. 

2. **Clicking the modal button on the Enquire page attempted to submit the form, highlighting incomplete fields on mobile, and triggering "this field needs completing".**
    * When initially implementing the Modal interface, a button was used to allow the user to bring up the Price Table modal. This issue was resolved by adding `onclick="return false;"` in the button field. 
    * When adding the link to the Price Table model in the _"About"_ page, it was decided that a 'Button' was visually obtrusive, and therefore a custom `<a>` class was implemented instead. 
    * This custom `<a>` class also replaced the button for the Price Table modal in the _"Enquire"_ page. This also allowed the Enquire/Submit button to maintain its unique design, without bleeding this feature onto other concepts. 

3. **When the content of the 'benefits' section of the table overflowed, the corresponding 'tick' boxes generated additional padding on the bottom of the cell, which conflicted with the 50% border concept implemented**
    * The issue came from `vertical-align: center;`, as this uses padding to align cell contents. Due to the nature of the ::after 50% border, this caused the border to sit on top of the padding, as opposed to the bottom of the cell as intended.
    * The solution was to set the `td` and `th` tags with `position: relative;`, and set the pseudo element to `position: absolute;`, then remove any padding from the pseudo element, and move that padding to the table element. 

Screenshot of the bug:  
![Border Padding Bug](https://res.cloudinary.com/bak2k3/image/upload/v1605371763/cell_border_c6jzdi.jpg)

Screenshot of the solution:  
![Border Padding Solution](https://res.cloudinary.com/bak2k3/image/upload/v1605371838/cell_border_solution_gaulce.jpg)

4. **Tooltips were being displayed on top of the text in mobile view, despite having "data-placement: right".**
    * This was resolved by using `data-placement: left`, even though it was not clear why.

5. **Issue with file locations from CSS when pushing to GitHub pages**
    * When the site was published to GitHub pages, the links to internal pages were not working, and the images were not being pulled from the assets folder.
    * The error was caused by the internal links being prefaced with `/`. Once removed, the links worked appropriately.
    * The links to images in the CSS file were defined as: `/assets/images/...`. Therefore, when using Gitpod, the links would work appropriately. 
    * Given how the page is hosted on GitHub, the assets were being searched for in: `GitHub.io/assets/images/...` as opposed to `GitHub.io/hard-drivers/assets/images/..`
    * This was resolved by using a relative file path, and removing the `assets/` subdirectory from the location reference, as such: `./images/...`.

6. **Users informed me that on some mobile devices the Navbar disappears (Safari) after clicking on a form input or pressing Submit**
    * On some mobile devices using Safari, clicking on an input form would "zoom in" on the input field. Alternatively, submitting an incomplete form would also "zoom in" on the incomplete input form.
    * This obfuscated the implementation of Viewport Control (fixed header with embedded scrollable div), requiring users to zoom out to use the page correctly.
    * While this did not necessarily break the layout of the page, it would require the user to zoom out in order to use the site correctly, creating a poor user experience.
    * This was fixed by adding: `minimum-scale=1, maximum-scale=1` to the meta tag of the _"Enquire"_ page.
    * As discussed in the Lighthouse section, this significantly reduced the Accessibility score for the page, however based on the layout and structure of the page, I am satisfied this was a suitable solution.

7. **Tooltips** (Existing Bug)
    * Multiple implementations of the tooltip were tested in order to allow the user to hover on desktop, and both click/touch to allow a persistent tooltip to appear in the Price Table.
    * The current implementation contains `tabindex=0`,which allows users to tab through the benefits and display their relevant tooltip accordingly. 
    * However, this solution results on the tooltip persisting on 'click', and cannot be 'unclicked'. The user must either click/tab to another tooltip or click elsewhere on the page to remove
    the tooltip. 
    * While this does not necessarily diminish the user experience, it is a bug that I would prefer to remove, however I am aware this requires additional knowledge of javascript. 

8. **Tabbing through the Enquire Menu** (Existing Bug)
    * When the user reaches the "Your Request" field of the Enquire Form, they need to tab twice, to bypass the "GitHub" icon, in order to reach the submit button. 
    * Setting `tabindex=1` to the submit button causes this item to be selected first when tabbing through the document, and results in the user having to press tab more times to reach the submit button.
    * Given the final input field is a "Free Text" box, pressing the enter button on this form generates a new line, as opposed to most other form inputs in which enter submits the form.
    * A solution to this would be to add set `tabindex=3` to all elements prior to the submit button, `tabindex=2` on the submit button, and `tabindex=1` on the rest of the footer icons.
    * This solution seems long winded, and would potentially result in unexpected results and goes against the recommendation to [not use 'tabindex=1+'](https://developer.paciellogroup.com/blog/2014/08/using-the-tabindex-attribute/#:~:text=When%20tabindex%20is%20set%20to,it%20in%20the%20tab%20order.).
    * A solution to this could also be implemented in javascript, however additional experience would be needed to attempt this.

# Other Technical Difficulties

1. **GitHub Commit Merge** 
    * On 27th October, I accidentally merged multiple git commits (df2b72005f9506c70c5d58fcb9964631462d7555/a8190a91b29cb1d4c3258e5d0f684390113bc646). While I researched how to undo the push, I was aware this would result in all of these changes being combined, and I wasn't fully comfortable 
    continuing with this as I didn't want to lose any more progress/commits. Accepted this single merge was an error, and moved on and learned from this.

---

[Click here](https://GitHub.com/BAK2K3/hard-drivers/blob/master/README.md) to return to the main README.md.
