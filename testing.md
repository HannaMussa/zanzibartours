## Code Validation

To ensure code quality and identify major issues, each page is validated.

The tables below detail the validation process, including the specific errors detected, corresponding screenshots from the validator, the necessary corrections, and the implemented code amendments.

### HTML

<details>
<summary>Click here to view Index.html responsiveness testing results </summary>

HTML was validated using [The W3C Markup Validation Service](https://validator.w3.org/).

| **Page** | **Screenshot**                                                                    | **Changes to be made**                                                                                                                                                                       | **Changes made**                                                                                                                                                                                                                                                         | **Final result**                                                                 |
| -------- | --------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------- |
| Home     | ![screenshot](assets/images/documentation/testing/validator/index-v-before.png)   | Stray div                                                                                                                                                                                    | Removed stray div                                                                                                                                                                                                                                                        | ![screenshot](assets/images/documentation/testing/validator/index-v-after.png)   |
| Book Now | ![screenshot](assets/images/documentation/testing/validator/booking-v-before.png) | The input type was set incorrectly. <br><br> The required attribute was duplicated, <br><br> The form method and action were written incorrectly. The form element was not closed correctly. | Changed the input type to 'text' to ensure the placeholder attribute functions correctly. <br><br> Removed the duplicate 'required' attribute. <br><br> Updated the form's method to 'GET' and set its action to 'confirmation.html'. Closed the form element correctly. | ![screenshot](assets/images/documentation/testing/validator/booking-v-after.png) |

**Note:** The Packages page is not listed above because it passed the HTML validation without errors.

 </details>

### CSS

<details>
<summary>Click here to view the CSS Validation </summary>

CSS is validated using [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator/).

| **Page**       | **Screenshot**                                                                | **Changes to be made**                                     | **Changes made**                                               | **Updated Screenshot**                                                       |
| -------------- | ----------------------------------------------------------------------------- | ---------------------------------------------------------- | -------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| CSS Stylesheet | ![screenshot](assets/images/documentation/testing/validator/css-v-before.png) | Font-size and padding values were not correctly formatted. | Removed unnecessary padding and corrected the font-size value. | ![screenshot](assets/images/documentation/testing/validator/css-v-after.png) |

 </details>

## Browser Compatibility

The most commonly used browsers are Google Chrome, Microsoft Edge, Mozilla Firefox, Opera, and Brave. Thus, the website has been tested on these browsers—results are as follows.

<details>
<summary>Click here to view the Browser Compatibility </summary>

| Browser         | Home (Top)                                                                          | Home (Bottom)                                                                       | Packages Page                                                                         | Booking Page                                                                         |
| --------------- | ----------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| Google Chrome   | ![screenshot](assets/images/documentation/testing/browser-compat/index-chrome1.png) | ![screenshot](assets/images/documentation/testing/browser-compat/index-chrome2.png) | ![screenshot](assets/images/documentation/testing/browser-compat/packages-chrome.png) | ![screenshot](assets/images/documentation/testing/browser-compat/booking-chrome.png) |
| Microsoft Edge  | ![screenshot](assets/images/documentation/testing/browser-compat/index-edge1.png)   | ![screenshot](assets/images/documentation/testing/browser-compat/index-edge2.png)   | ![screenshot](assets/images/documentation/testing/browser-compat/packages-edge.png)   | ![screenshot](assets/images/documentation/testing/browser-compat/booking-edge.png)   |
| Mozilla Firefox | ![screenshot](assets/images/documentation/testing/browser-compat/index-fox1.png)    | ![screenshot](assets/images/documentation/testing/browser-compat/index-fox2.png)    | ![screenshot](assets/images/documentation/testing/browser-compat/packages-fox.png)    | ![screenshot](assets/images/documentation/testing/browser-compat/booking-fox.png)    |
| Opera           | ![screenshot](assets/images/documentation/testing/browser-compat/index-opera1.png)  | ![screenshot](assets/images/documentation/testing/browser-compat/index-opera2.png)  | ![screenshot](assets/images/documentation/testing/browser-compat/packages-opera.png)  | ![screenshot](assets/images/documentation/testing/browser-compat/booking-opera.png)  |
| Brave           | ![screenshot](assets/images/documentation/testing/browser-compat/index-brave1.png)  | ![screenshot](assets/images/documentation/testing/browser-compat/index-brave2.png)  | ![screenshot](assets/images/documentation/testing/browser-compat/packages-brave.png)  | ![screenshot](assets/images/documentation/testing/browser-compat/booking-brave.png)  |

**Note:** The website was responsive and displayed consistently across all tested browsers.

</details>

## Responsiveness

The website maintains a fully responsive layout across all devices, ensuring a seamless user experience on mobile, tablet, laptop, and XL screen.

<details>
<summary>Click here to view the Index.html responsiveness</summary>

| Device             | Mobile                                                                                  | Tablet                                                                                  | Laptop                                                                                  | XL Devices                                                                          |
| ------------------ | --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Index-Carousel     | ![screenshot](assets/images/documentation/testing/responsive/index/i-mobile-car.png)    | ![screenshot](assets/images/documentation/testing/responsive/index/i-tablet-car.png)    | ![screenshot](assets/images/documentation/testing/responsive/index/i-laptop-car.png)    | ![screenshot](assets/images/documentation/testing/responsive/index/i-xl-car.png)    |
| Index-About        | ![screenshot](assets/images/documentation/testing/responsive/index/i-mobile-about.png)  | ![screenshot](assets/images/documentation/testing/responsive/index/i-tablet-about.png)  | ![screenshot](assets/images/documentation/testing/responsive/index/i-laptop-about.png)  | ![screenshot](assets/images/documentation/testing/responsive/index/i-xl-about.png)  |
| Index-Testimonials | ![screenshot](assets/images/documentation/testing/responsive/index/i-mobile-test.png)   | ![screenshot](assets/images/documentation/testing/responsive/index/i-tablet-test.png)   | ![screenshot](assets/images/documentation/testing/responsive/index/i-laptop-test.png)   | ![screenshot](assets/images/documentation/testing/responsive/index/i-xl-test.png)   |
| Index-Footer       | ![screenshot](assets/images/documentation/testing/responsive/index/i-mobile-footer.png) | ![screenshot](assets/images/documentation/testing/responsive/index/i-tablet-footer.png) | ![screenshot](assets/images/documentation/testing/responsive/index/i-laptop-footer.png) | ![screenshot](assets/images/documentation/testing/responsive/index/i-xl-footer.png) |

</details>

<details>
<summary>Click here to view the Packages.html responsiveness</summary>

| Device        | Mobile                                                                                   | Tablet                                                                                   | Laptop                                                                                   | XL Devices                                                                           |
| ------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| Packages-Card | ![screenshot](assets/images/documentation/testing/responsive/packages/p-mobile-card.png) | ![screenshot](assets/images/documentation/testing/responsive/packages/p-tablet-card.png) | ![screenshot](assets/images/documentation/testing/responsive/packages/p-laptop-card.png) | ![screenshot](assets/images/documentation/testing/responsive/packages/p-xl-card.png) |

</details>

<details>
<summary>Click here to view the Booking.html responsiveness</summary>

| Device       | Mobile                                                                                  | Tablet                                                                                  | Laptop                                                                                  | XL Devices                                                                          |
| ------------ | --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Booking Form | ![screenshot](assets/images/documentation/testing/responsive/booking/b-mobile-form.png) | ![screenshot](assets/images/documentation/testing/responsive/booking/b-tablet-form.png) | ![screenshot](assets/images/documentation/testing/responsive/booking/b-laptop-form.png) | ![screenshot](assets/images/documentation/testing/responsive/booking/b-xl-form.png) |

</details>

## Lighthouse Audit

Chrome Lighthouse audits web pages for performance, accessibility, and SEO, generating reports and improvement suggestions.

<details>
<summary>Click here to view the Lighthouse Audit </summary>

| Page     | Size    | Screenshot Before                                                               | Lighthouse Suggestions                                                  |     | Screenshot After                                                               |
| -------- | ------- | ------------------------------------------------------------------------------- | ----------------------------------------------------------------------- | --- | ------------------------------------------------------------------------------ |
| Home     | Mobile  | ![](assets/images/documentation/testing/lighthouse/index-mobile-before.png)     | ![](assets/images/documentation/testing/lighthouse/index-detail.png)    |     | ![](assets/images/documentation/testing/lighthouse/index-mobile-after.png)     |
| Home     | Desktop | ![](assets/images/documentation/testing/lighthouse/index-desktop-before.png)    | Similar to above                                                        |     | ![](assets/images/documentation/testing/lighthouse/index-desktop-after.png)    |
| Packages | Mobile  | ![](assets/images/documentation/testing/lighthouse/packages-mobile-before.png)  | ![](assets/images/documentation/testing/lighthouse/packages-detail.png) |     | ![](assets/images/documentation/testing/lighthouse/packages-mobile-after.png)  |
| Packages | Desktop | ![](assets/images/documentation/testing/lighthouse/packages-desktop-before.png) | Similar to above                                                        |     | ![](assets/images/documentation/testing/lighthouse/packages-desktop-after.png) |
| Booking  | Mobile  | ![](assets/images/documentation/testing/lighthouse/booking-mobile-before.png)   | ![](assets/images/documentation/testing/lighthouse/booking-detail.png)  |     | ![](assets/images/documentation/testing/lighthouse/booking-mobile-after.png)   |
| Booking  | Desktop | ![](assets/images/documentation/testing/lighthouse/booking-desktop-before.png)  | Similar to above                                                        |     | ![](assets/images/documentation/testing/lighthouse/booking-desktop-after.png)  |

**Note:** All pages underwent image compression and resizing for improved performance.

 </details>

## WAVE Web Accessibility Evaluation Tool

The [WAVE](https://wave.webaim.org/) tool analyzes structure, contrast, and accessibility issues, providing visual feedback for web pages.

<details>
<summary>Click here to view the WAVE Feedback </summary>

| Before                                                                  | After                                                                  | Notes                                                                                                                                                                                                          |
| ----------------------------------------------------------------------- | ---------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![screenshot](assets/images/documentation/testing/wave/wave-before.png) | ![screenshot](assets/images/documentation/testing/wave/wave-after.png) | The carousel headings had a contrast issue due to the background color. To resolve this, I applied background-color: rgba(0, 0, 0, 0.014) for better contrast. This update is reflected in the CSS stylesheet. |

**Note:** Since all other pages passed without issues, no additional screenshots are necessary.

 </details>

## User Story Testing

<details>
<summary>Click here to view the User story testing Feedback </summary>

| **User Story**                                                                                                                                                                                                                    | **Screenshot**                                                                              | **Result**                                                                                                                                                                                                                                 |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| As a new user, I would like to understand the purpose of this site for ease of convenience.                                                                                                                                       | ![screenshot](assets/images/documentation/testing/user-stories/about.png)                   | The About Us section provides a clear overview of Zanzibar Tours, highlighting its goal of delivering unforgettable holiday experiences.                                                                                                   |
| As a new user, I would like to easily navigate the site, as this would be user-friendly and convenient.                                                                                                                           | ![screenshot](assets/images/documentation/testing/user-stories/navigation.png)              | The website's fixed navigation menu ensures seamless access to key sections, including Home, About, Packages, Contact, and Book Now. Internal links provide smooth scrolling for quick access, enhancing user convenience.                 |
| As a new user, I would like to contact the owner and view their opening hours so I can contact them and discuss any questions. <br> <br> As a new user, I would like to find social media pages for contact purposes.             | ![screenshot](assets/images/documentation/testing/user-stories/footer.png)                  | The footer offers key contact details, social media links, and opening hours, ensuring easy access for inquiries and communication.                                                                                                        |
| As a new user, I would like to book a tour for convenience.                                                                                                                                                                       | ![screenshot](assets/images/documentation/testing/user-stories/booking.png)                 | The website ensures a seamless booking experience with a prominently placed 'Book Now' button leading to a user-friendly form.                                                                                                             |
| As a new user, I would like to view visuals of Zanzibar Tours to know what I will be expecting.                                                                                                                                   | ![screenshot](assets/images/documentation/testing/user-stories/carousel.png)                | The carousel showcases high-quality assets/images of Zanzibar Tours, providing users with a visual preview of destinations and experiences, helping them know what to expect before booking.                                               |
| As a new user, I would like to get detailed information on available tours with scenic visuals to know what I will be expecting.                                                                                                  | ![screenshot](assets/images/documentation/testing/user-stories/packages.png)                | The packages.html page offers detailed tour descriptions with scenic visuals, providing users with clear expectations. Each package includes a title, description, and pricing details.                                                    |
| As a new user, I would like to read testimonials from previous visitors to get an idea of the credibility of the company.                                                                                                         | ![screenshot](assets/images/documentation/testing/user-stories/test.png)                    | The website features a testimonials section where previous visitors share their experiences.                                                                                                                                               |
| As a new user, I would like to view the site on any device, as this would be a good user experience and convenient.                                                                                                               |                                                                                             | The website is designed to be fully responsive, ensuring a seamless experience across all devices. It adapts to different screen sizes, providing easy navigation and accessibility whether viewed on a desktop, tablet, or mobile device. |
| Since responsiveness was tested across multiple devices, no single screenshot is provided. For details, refer to the [TESTING.md](TESTING.md) file.                                                                               |
| As an existing user, I would like to stay updated and get notified about new features, events, and announcements to see if I would like to attend any tours.                                                                      | ![screenshot](assets/images/documentation/testing/user-stories/footer.png)                  | The website's newsletter keeps users informed about new tours, events, and announcements, ensuring they stay updated on the latest offerings.                                                                                              |
| As an existing user, I would like to see any tours available with their costs so that I can calculate the feasibility before booking.                                                                                             | ![screenshot](assets/images/documentation/testing/user-stories/packages.png)                | The packages.html page displays all available tours along with their costs, allowing users to assess feasibility before booking.                                                                                                           |
| As an admin user, I should be able to respond to user inquiries to build a good reputation and ensure reliability.                                                                                                                | ![screenshot](assets/images/documentation/testing/user-stories/booking.png)                 | The website enables admin users to respond to inquiries through a contact section, booking form, and provided contact details, ensuring timely communication, reliability, and a strong reputation.                                        |
| As an admin user, I want to add, edit, or remove tour listings so that the website always displays up-to-date offerings to provide a good user experience.                                                                        | ![screenshot](assets/images/documentation/testing/user-stories/packages-code.png)           | The code provided enables administrators to add, edit, and remove tour listings, ensuring that the website remains up to date and provides users with accurate information.                                                                |
| As an admin user, I should be able to oversee site performance, detect issues, and debug any problems for a good user experience. <br> <br> As an admin user, I should have correct indentation for easy readability and editing. | ![screenshot](assets/images/documentation/testing/user-stories/admin-indentation-debug.png) | he code follows proper indentation for readability, making it easier to detect and debug issues.                                                                                                                                           |

</details>

## Bugs

<details>
<summary>Click here to view the Bugs </summary>

| Bug                                                                                                | Solution Implemented                                                                          | Outcome Screenshot                                                                    |
| -------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| **Navbar difficult to access** – Users had to scroll to the top to navigate between pages.         | Added `fixed-top` to `<nav>` for a persistent navbar.                                         | ![Navbar Issue](assets/images/documentation/testing/bugs/navbar.png)                  |
| **Carousel text lacked contrast** – The text was hard to read against the background.              | Applied `background-color: rgba(0, 0, 0, 0.014)` to the header for better contrast.           | ![Carousel Issue](assets/images/documentation/testing/bugs/carousel.png)              |
| **Testimonial card not responsive** – Layout broke on different screen sizes.                      | Used media queries: Min-width 992px → height 25rem, Min-width 1200px → height 23rem.          | ![Testimonial Responsiveness](assets/images/documentation/testing/bugs/test-resp.png) |
| **Package card not responsive** – Content overflowed or misaligned on various devices.             | Standardized image sizes and ensured `<p>` elements had a similar word count for consistency. | ![Package Responsiveness](assets/images/documentation/testing/bugs/packages-resp.png) |
| **Booking form selector pre-selected by default** – Users could not start with an empty selection. | Added `selected disabled` to the "Select a tour" `<option>` to prevent auto-selection.        | ![Booking Form Issue](assets/images/documentation/testing/bugs/booking.png)           |

</details>

## Unfixed Bugs

- At this time, no known unresolved bugs have been identified
