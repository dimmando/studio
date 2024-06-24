# TESTING


## Compatibility

In order to confirm the correct functionality, responsiveness, and appearance:

+ The website was tested on the following browsers: Chrome, Firefox, Edge.

    - Chrome:

    ![Chrome](documentation/chrome.png)

    - FireFox:

    ![FireFox](documentation/firefox.png)

    - Edge:

    ![Brave](documentation/edge.png)

## Responsiveness


+ The website was checked by Responsive Viewer - a trial version of Chrome browser extension:

    ![Responsive Viever](documentation/responsive-viewer.png)

    - Main Page:

    ![Main Page](documentation/responsiveness_main_page.png)

    - Gallery Page:

    ![Gallery Page](documentation/responsiveness_gallery_page.png)

    - Booking Page:

    ![Booking Page](documentation/responsiveness_booking_page.png)

    - Response Page:

    ![Response Page](documentation/responsiveness_response_page.png)

+ The functionality of the links in the website was checked as well by different users.

---
## Validator testing
+ ### HTML
  #### Home Page
    - No errors or warnings were found when passing through the official W3C validator.


    ![Home Page HTML Validator](documentation/w3_validator_home_page.png)
    
  #### Our Studio/Gallery Page
    - Only 1 warning was found when passing through the official W3C validator.

    ![Gallery Page HTML Validator](documentation/w3_validator_gallery_page.png)

  #### Booking Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Booking Page HTML Validator](documentation/w3_validator_contact_page.png)

  #### Response Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Response Page HTML Validator](documentation/w3_validator_response_page.png)
    
+ ### CSS
  No errors or warnings were found when passing through the official W3C (Jigsaw) validator

  ![CSS Validator errors](documentation/w3_validator_css_errors.png)
  

+ ## LightHouse report

    - Using lighthouse in devtools I confirmed that the website is performing well, accessible and colors and fonts chosen are readable.
    
  ### Home page

  ![Home Page Lighthouse](documentation/lighthouse_home_page.png)

  ### Gallery page

  ![Our Studio Lighthouse](documentation/lighthouse_gallery_page.png)

  ### Contact page

  ![Booking Lighthouse](documentation/lighthouse_contact_page.png)

  ### Response page

  ![Response Page Lighthouse](documentation/lighthouse_response_page.png)

---
​
## Bugs
+ ### Solved bugs
    1. Pictures at Our Studio page/kind of gallery didn't want to align at the center of the page.
    
        *Solutions:* Alignment was done by using flex instruction.

+ ### Unsolved bugs
    - None.
+ ### Mistakes
    - Mistake was made in alignment Google Map insertion on Home Page using HTML code that didn't allow to scale all page on small screen like 375px correctly. It have been solved by styling alignment in CSS file instead HTML.
    
---