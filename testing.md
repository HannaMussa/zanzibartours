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

 **Page** | **Screenshot** | **Changes to be made** | **Changes made** | **Updated Screenshot** 
---|---|---|---|---
 CSS style sheet | ![screenot](assets/images/documentation/testing/validator/css-v-before.png) | Font-size and padding values / format were incorrect  | Padding removed as it was not necessary and font-size value was chnaged | ![screenot](assets/images/documentation/testing/validator/css-v-after.png) 
  |  |  |  |  

 </details>

## Browser Compatibility
## Responsiveness

## Lighthouse Audit
Chrome Lighthouse evaluates the performance, accessibility, and SEO of a web page by running audits, providing detailed reports, and suggesting improvements.

<details>
<summary>Click here  to view the Lighthouse Audit </summary>
 

 </details>

## WAVE Web Accessibility Evaluation Tool 

The [WAVE](https://wave.webaim.org/) tool analyzes structure, contrast, and accessibility issues, providing visual feedback for web pages.

<details>
<summary>Click here  to view the WAVE Feedback </summary>
 

 </details>
 

## User Story Testing
## Bugs
## Unfixed Bugs
