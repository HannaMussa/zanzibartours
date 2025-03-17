## Code Validation

To ensure code quality and identify major issues, each page undergoes validation.

The tables below detail the validation process, including the specific errors detected, corresponding screenshots from the validator, the necessary corrections, and the implemented code amendments.

### HTML

<details>
<summary>Click to view Index.html responsiveness testing results </summary>

HTML was validated using [The W3C Markup Validation Service](https://validator.w3.org/).

| **Page** | **Screenshot**                                                                    | **Changes to be made**                                                                                                                                                                       | **Changes made**                                                                                                                                                                                                                                                         | **Final result**                                                                 |
| -------- | --------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------- |
| Home     | ![screenshot](assets/images/documentation/testing/validator/index-v-before.png)   | Stray div                                                                                                                                                                                    | Removed stray div                                                                                                                                                                                                                                                        | ![screenshot](assets/images/documentation/testing/validator/index-v-after.png)   |
| Book Now | ![screenshot](assets/images/documentation/testing/validator/booking-v-before.png) | The input type was set incorrectly. <br><br> The required attribute was duplicated, <br><br> The form method and action were written incorrectly. The form element was not closed correctly. | Changed the input type to 'text' to ensure the placeholder attribute functions correctly. <br><br> Removed the duplicate 'required' attribute. <br><br> Updated the form's method to 'GET' and set its action to 'confirmation.html'. Closed the form element correctly. | ![screenshot](assets/images/documentation/testing/validator/booking-v-after.png) |

**Note:** The Packages page is not listed above because it passed the HTML validation without errors.

 </details>

### CSS

<details>
<summary>Click here  to view the CSS Validation </summary>

CSS is validated using [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator/).

| **Page**        | **Screenshot**                                                                | **Changes to be made**                                  | **Changes made**                                                         | **Updated Screenshot**                                                       |
| --------------- | ----------------------------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------------------------ | ---------------------------------------------------------------------------- |
| CSS style sheet | ![screenshot](assets/images/documentation/testing/validator/css-v-before.png) | Font-size and padding values were incorrectly formatted | Padding removed as it was not necessary, and font-size value was changed | ![screenshot](assets/images/documentation/testing/validator/css-v-after.png) |
|                 |

 </details>

## Browser Compatibility

## Responsiveness

The website maintains a fully responsive layout across all devices, ensuring smooth user experience on mobile, tablet, laptop, and XL screens

<details>
<summary>Click here  to view the Index.html responsiveness</summary>

| Device             | Mobile                                                                                  | Tablet                                                                                  | Laptop                                                                                  | XL Devices                                                                          |
| ------------------ | --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Index-Carousel     | ![screenshot](assets/images/documentation/testing/responsive/index/i-mobile-car.png)    | ![screenshot](assets/images/documentation/testing/responsive/index/i-tablet-car.png)    | ![screenshot](assets/images/documentation/testing/responsive/index/i-laptop-car.png)    | ![screenshot](assets/images/documentation/testing/responsive/index/i-xl-car.png)    |
| Index-About        | ![screenshot](assets/images/documentation/testing/responsive/index/i-mobile-about.png)  | ![screenshot](assets/images/documentation/testing/responsive/index/i-tablet-about.png)  | ![screenshot](assets/images/documentation/testing/responsive/index/i-laptop-about.png)  | ![screenshot](assets/images/documentation/testing/responsive/index/i-xl-about.png)  |
| Index-Testimonials | ![screenshot](assets/images/documentation/testing/responsive/index/i-mobile-test.png)   | ![screenshot](assets/images/documentation/testing/responsive/index/i-tablet-test.png)   | ![screenshot](assets/images/documentation/testing/responsive/index/i-laptop-test.png)   | ![screenshot](assets/images/documentation/testing/responsive/index/i-xl-test.png)   |
| Index-Footer       | ![screenshot](assets/images/documentation/testing/responsive/index/i-mobile-footer.png) | ![screenshot](assets/images/documentation/testing/responsive/index/i-tablet-footer.png) | ![screenshot](assets/images/documentation/testing/responsive/index/i-laptop-footer.png) | ![screenshot](assets/images/documentation/testing/responsive/index/i-xl-footer.png) |

</details>

<details>
<summary>Click here  to view the Packages.html responsiveness</summary>

| Device        | Mobile                                                                                   | Tablet                                                                                   | Laptop                                                                                   | XL Devices                                                                           |
| ------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| Packages-Card | ![screenshot](assets/images/documentation/testing/responsive/packages/p-mobile-card.png) | ![screenshot](assets/images/documentation/testing/responsive/packages/p-tablet-card.png) | ![screenshot](assets/images/documentation/testing/responsive/packages/p-laptop-card.png) | ![screenshot](assets/images/documentation/testing/responsive/packages/p-xl-card.png) |

</details>

<details>
<summary>Click here  to view the Booking.html responsiveness</summary>

| Device       | Mobile                                                                                  | Tablet                                                                                  | Laptop                                                                                  | XL Devices                                                                          |
| ------------ | --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Booking Form | ![screenshot](assets/images/documentation/testing/responsive/booking/b-mobile-form.png) | ![screenshot](assets/images/documentation/testing/responsive/booking/b-tablet-form.png) | ![screenshot](assets/images/documentation/testing/responsive/booking/b-laptop-form.png) | ![screenshot](assets/images/documentation/testing/responsive/booking/b-xl-form.png) |

</details>

## Lighthouse Audit

Chrome Lighthouse evaluates the performance, accessibility, and SEO of a web page by running audits, providing detailed reports, and suggesting improvements.

<details>
<summary>Click here  to view the Lighthouse Audit </summary>

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
<summary>Click here  to view the WAVE Feedback </summary>

| Before                                                                  | After                                                                  | Notes                                                                                                                                                                                                 |
| ----------------------------------------------------------------------- | ---------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![screenshot](assets/images/documentation/testing/wave/wave-before.png) | ![screenshot](assets/images/documentation/testing/wave/wave-after.png) | The headings on the carousel had a contrast issue due to background color, therefore I added `background-color: rgba(0, 0, 0, 0.014)` to overcome this issue. This can be viewed on the styles sheet. |

**Note:** All other pages passed the WAVE test without issues, so no additional screenshots are provided.

 </details>

## User Story Testing

<details>
<summary>Click here  to view the User story testing Feedback </summary>

| **User Story**                                                                                                                                                                                                                    | **Screenshot**                                                                              | **Result**                                                                                                                                                                                                                                                                                                             |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| As a new user, I would like to understand the purpose of this site for ease of convenience.                                                                                                                                       | ![screenshot](assets/images/documentation/testing/user-stories/about.png)                   | The About Us section provides a clear overview of Zanzibar Tours, highlighting its goal of delivering unforgettable holiday experiences.                                                                                                                                                                               |
| As a new user, I would like to easily navigate the site, as this would be user-friendly and convenient.                                                                                                                           | ![screenshot](assets/images/documentation/testing/user-stories/navigation.png)              | The website's fixed navigation menu ensures seamless access to key sections, including Home, About, Packages, Contact, and Book Now. Internal links provide smooth scrolling for quick access, enhancing user convenience.                                                                                             |
| As a new user, I would like to contact the owner and view their opening hours so I can contact them and discuss any questions. <br> <br> As a new user, I would like to find social media pages for contact purposes.             | ![screenshot](assets/images/documentation/testing/user-stories/footer.png)                  | The footer offers key contact details, social media links, and opening hours, ensuring easy access for inquiries and communication.                                                                                                                                                                                    |
| As a new user, I would like to book a tour for convenience.                                                                                                                                                                       | ![screenshot](assets/images/documentation/testing/user-stories/booking.png)                 | TThe website ensures a seamless booking experience with a prominently placed 'Book Now' button leading to a user-friendly form.                                                                                                                                                                                        |
| As a new user, I would like to view visuals of Zanzibar Tours to know what I will be expecting.                                                                                                                                   | ![screenshot](assets/images/documentation/testing/user-stories/carousel.png)                | The carousel showcases high-quality images of Zanzibar Tours, providing users with a visual preview of destinations and experiences, helping them know what to expect before booking.                                                                                                                                  |
| As a new user, I would like to get detailed information on available tours with scenic visuals to know what I will be expecting.                                                                                                  | ![screenshot](assets/images/documentation/testing/user-stories/packages.png)                | The packages.html page provides detailed tour information with scenic visuals, helping new users understand what to expect. Each package includes a title, description, pricing.                                                                                                                                       |
| As a new user, I would like to read testimonials from previous visitors to get an idea of the credibility of the company.                                                                                                         | ![screenshot](assets/images/documentation/testing/user-stories/test.png)                    | The website features a testimonials section where previous visitors share their experiences.                                                                                                                                                                                                                           |
| As a new user, I would like to view the site on any device, as this would be a good user experience and convenient.                                                                                                               |                                                                                             | The website is designed to be fully responsive, ensuring a seamless experience across all devices. It adapts to different screen sizes, providing easy navigation and accessibility whether viewed on a desktop, tablet, or mobile device. For detailed responsiveness tests, visit the [TESTING.md](TESTING.md) file. |
| As an existing user, I would like to stay updated and get notified about new features, events, and announcements to see if I would like to attend any tours.                                                                      | ![screenshot](assets/images/documentation/testing/user-stories/footer.png)                  | The website's newsletter keeps users informed about new tours, events, and announcements, ensuring they stay updated on the latest offerings.                                                                                                                                                                          |
| As an existing user, I would like to see any tours available with their costs so that I can calculate the feasibility before booking.                                                                                             | ![screenshot](assets/images/documentation/testing/user-stories/packages.png)                | The packages.html page displays all available tours along with their costs, allowing users to assess feasibility before booking.                                                                                                                                                                                       |
| As an admin user, I should be able to respond to user inquiries to build a good reputation and ensure reliability.                                                                                                                | ![screenshot](assets/images/documentation/testing/user-stories/booking.png)                 | The website enables admin users to respond to inquiries through a contact section, booking form, and provided contact details, ensuring timely communication, reliability, and a strong reputation.                                                                                                                    |
| As an admin user, I want to add, edit, or remove tour listings so that the website always displays up-to-date offerings to provide a good user experience.                                                                        | ![screenshot](assets/images/documentation/testing/user-stories/packages-code.png)           | The code provided enables administrators to add, edit, and remove tour listings, ensuring that the website remains up to date and provides users with accurate information.                                                                                                                                            |
| As an admin user, I should be able to oversee site performance, detect issues, and debug any problems for a good user experience. <br> <br> As an admin user, I should have correct indentation for easy readability and editing. | ![screenshot](assets/images/documentation/testing/user-stories/admin-indentation-debug.png) | The code maintains proper indentation, ensuring readability and also allows to detect any issues for debugging. </details>                                                                                                                                                                                             |

## Bugs

## Unfixed Bugs

- At this time, no known unresolved bugs have been identified
