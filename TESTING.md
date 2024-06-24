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


+ The website was checked by devtools implemented in Firefox and Chrome browsers.

    - Main Page:

    ![Main Page](documentation/responsiveness_main_page.gif)

    - Gallery Page:

    ![Gallery Page](documentation/responsiveness_gallery_page.gif)

    - Contact Page:

    ![Contact Page](documentation/responsiveness_contact_page.gif)

    - Response Page:

    ![Response Page](documentation/responsiveness_response_page.gif)

+ The website was checked with [Responsive Website Design Tester](https://responsivedesignchecker.com/).

    - Desktop Screens:

    ![Desktop 1024x600](documentation/desktop_1024_600.gif)
    ![Desktop 1024x800](documentation/desktop_1024_800.gif)
    ![Desktop 1366x768](documentation/desktop_1366_768.gif)
    ![Desktop 1440x900](documentation/desktop_1440_900.gif)
    ![Desktop 1600x900](documentation/desktop_1600_900.gif)
    ![Desktop 1680x1050](documentation/desktop_1680_1050.gif)
    ![Desktop 1920x1080](documentation/desktop_1920_1080.gif)
    ![Desktop 1920x1200](documentation/desktop_1920_1200.gif)

    - Tablet Screens:

    ![Tablet 600x960](documentation/tablet_600_960.gif)
    ![Tablet 768x1024](documentation/tablet_768_1024.gif)
    ![Tablet 800x1280](documentation/tablet_800_1280.gif)
    ![Tablet 1024x768](documentation/tablet_1024_768.gif)
    ![Tablet 1366x1024](documentation/tablet_1366_1024.gif)
    ![Tablet Kindle 768x1024](documentation/tablet_kindle_768_1024.gif)

    - Mobile Screens:

    ![Mobile 320x480](documentation/mobile_320_480.gif)
    ![Mobile 320x568](documentation/mobile_320_568.gif)
    ![Mobile 360x640](documentation/mobile_360_640.gif)
    ![Mobile 375x667](documentation/mobile_375_667.gif)
    ![Mobile 384x640](documentation/mobile_384_640.gif)
    ![Mobile 411x731](documentation/mobile_411_731.gif)
    ![Mobile 414x736](documentation/mobile_414_736.gif)

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