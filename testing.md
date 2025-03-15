## Code Validation

To ensure code quality and identify major issues, each page undergoes validation. HTML was validated using [The W3C Markup Validation Service](https://validator.w3.org/) and CSS is validated using [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator/).

he tables below detail the validation process, including the specific errors detected, corresponding screenshots from the validator, the necessary corrections, and the implemented code amendments.

### HTML

<details>
<summary>Click here  to view the HTML Validation </summary>
 
 
 **Page** | **Screenshot** | **Changes to be made** | **Changes made** | **Final result** 
---|---|---|---|---
 Home | ![screenot](assets/images/documentation/testing/validator/index-v-before.png) | Stray div | Removed stray div | ![screenot](assets/images/documentation/testing/validator/index-v-after.png) 
 Book Now | ![screenot](assets/images/documentation/testing/validator/booking-v-before.png) | The input type was set incorrectly.  <br><br> The required attribute was duplicated, <br><br> The form method and action were written incorrectly. The form element was not closed correctly. | Changed the input type to 'text' to ensure the placeholder attribute functions correctly. <br><br> Removed the duplicate 'required' attribute. <br><br> Updated the form's method to 'GET' and set its action to 'confirmation.html'. Closed the form element correctly. | ![screenot](assets/images/documentation/testing/validator/booking-v-after.png)

- The packages page is not included in the table above as it passed the HTML validation test.

 </details>

<details>
<summary>Click here  to view the CSS Validation </summary>

| **Page**        | **Screenshot**                                                              | **Changes to be made**                               | **Changes made**                                                        | **Updated Screenshot**                                                     |
| --------------- | --------------------------------------------------------------------------- | ---------------------------------------------------- | ----------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| CSS style sheet | ![screenot](assets/images/documentation/testing/validator/css-v-before.png) | Font-size and padding values / format were incorrect | Padding removed as it was not necessary and font-size value was chnaged | ![screenot](assets/images/documentation/testing/validator/css-v-after.png) |
|                 |                                                                             |                                                      |

 </details>

## Browser Compatibility

## Responsiveness

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

| Page     | Size    | Screenshot Before                                                               | Lighthouse Suggestions                                                  | Changes Made                                           | Screenshot After                                                               |
| -------- | ------- | ------------------------------------------------------------------------------- | ----------------------------------------------------------------------- | ------------------------------------------------------ | ------------------------------------------------------------------------------ |
| Home     | Mobile  | ![](assets/images/documentation/testing/lighthouse/index-mobile-before.png)     | ![](assets/images/documentation/testing/lighthouse/index-detail.png)    | Resized & compressed images for faster loading         | ![](assets/images/documentation/testing/lighthouse/index-mobile-after.png)     |
| Home     | Desktop | ![](assets/images/documentation/testing/lighthouse/index-desktop-before.png)    | Similar to above                                                        | Resized & compressed images for faster loading         | ![](assets/images/documentation/testing/lighthouse/index-desktop-after.png)    |
| Packages | Mobile  | ![](assets/images/documentation/testing/lighthouse/packages-mobile-before.png)  | ![](assets/images/documentation/testing/lighthouse/packages-detail.png) | Resized & compressed images for faster loading         | ![](assets/images/documentation/testing/lighthouse/packages-mobile-after.png)  |
| Packages | Desktop | ![](assets/images/documentation/testing/lighthouse/packages-desktop-before.png) | Similar to above                                                        | Resized & compressed images for faster loading         | ![](assets/images/documentation/testing/lighthouse/packages-desktop-after.png) |
| Booking  | Mobile  | ![](assets/images/documentation/testing/lighthouse/booking-mobile-before.png)   | ![](assets/images/documentation/testing/lighthouse/booking-detail.png)  | Removed background image for contrast & faster loading | ![](assets/images/documentation/testing/lighthouse/booking-mobile-after.png)   |
| Booking  | Desktop | ![](assets/images/documentation/testing/lighthouse/booking-desktop-before.png)  | Similar to above                                                        | Removed background image for contrast & faster loading | ![](assets/images/documentation/testing/lighthouse/booking-desktop-after.png)  |

 </details>

## WAVE Web Accessibility Evaluation Tool

The [WAVE](https://wave.webaim.org/) tool analyzes structure, contrast, and accessibility issues, providing visual feedback for web pages.

<details>
<summary>Click here  to view the WAVE Feedback </summary>

 </details>

## User Story Testing

## Bugs

## Unfixed Bugs
