# Sailing School

Hi, welcome to my Sailing School project!

The initial idea was to set up a website for a sailing school, focused on beginner's lessons for children. I wanted the design to be minimalistic, easy to navigate, and comprehend, which was (hopefully) achieved in this project. The website is designed for parents that wish to sign their children up for sailing lessons. Keeping in mind that the intended user might not be tech-savvy and needs a simple website that does what it says, the design for this project was achieved. The colours were picked out as an attempt to emulate the colours of the Adriatic sea and to give the user a feeling of being at sea. 

[Deployed URL](https://lstipi.github.io/sailing-school-P1/)

![FullScreen](https://i.imgur.com/ilNBWgm.png)
![FullScreen Mobile](https://i.imgur.com/pYTL6Gm.png)

## Table of contents

- [Sailing School](#sailing-school)
  * [Features](#features)
    + [Existing Features](#existing-features)
  * [Testing](#testing)
    + [Validator Testing](#validator-testing)
  * [Deployment](#deployment)
  * [Credits](#credits)
    + [Content](#content)
    + [Media](#media)
  * [Acknowledgments](#acknowledgments)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

## Features

The project requirements were to use HTML and CSS to do so, therefore the initial document was index.html linked with a style.css spreadsheet. The idea for index.html was to have a navbar above an image with 2 buttons in the center of the image. The navigation bar consists of a logo on the left and the links to where-to-find-us.html and contact-form.html, while the buttons in the centre lead to beginner's guide.html and the timetable displayed under the central image in index.html. The main colors of the project are various shades of blue, ranging from paler shades to darker shades, to achieve good visibility. 
To achieve the minimalistic style, I didn't add a lot of text, nor features, just the basic information about the sailing club accompanied by a timetable of the sailing lessons on index.html, basic instructions on how to reach the location on where-to-find-us.html, and a form where t is possible to sign up in the contact-form.html. A custom 404 page was added as well.

### Existing Features


* __Navigation Bar__ 

The navigation bar is fixed and present on all other html files, it consists of 4 items, a logo, and Home that leads back to index.html, Location that leads to where-to-find-us.html, and Sign Up that leads to contact-form. It is responsive and allows the user to navigate between the pages easily on all devices, ranging from a phone to a desktop. 

![NavBar](https://i.imgur.com/AS3X58w.png)
![NavBarMob](https://i.imgur.com/i5JerW2.png)


* __Set Sail__ 

The Set sail section consists of an background image of sailboats at sea and in the centre of the image are two buttons. The first button Sailing Lessons leads directly to the About Us further down the page, while the Beginner's guide button leads to the Beginner's guide section on the very bottom of the page. 

![SetSail](https://i.imgur.com/eE88sAY.png)
![SetSailMob](https://i.imgur.com/Dk06z6f.png)


Buttons also have a hover animation as can be seen in the screenshots below.

![Buttons](https://i.imgur.com/ENe81YS.jpg?4)
![ButtonsHover](https://i.imgur.com/DkzfHTs.png?2)


* __About Us__

The About Us section gives a brief description of when the sailing club was founded and what its goals are. 

![AboutUs](https://i.imgur.com/3PNsZVo.png)



* __Timetable__



The Timetable section contains a table of times when lessons are happening throughout the week. If the time of the lesson changes, the table will be updated and members will be notified.




![Timetable](https://i.imgur.com/IH5TBqf.png)



* __Footer__

The footer consists of icons which when clicked lead to Twitter, Instagram, and Facebook and are opened in a new tab for easy navigation. It is fully responsive as can be seen on the screenshots below.

![Footer](https://i.imgur.com/91KCawL.png)
![FooterM](https://i.imgur.com/Y0j6Ieb.png)

Icons are animated when hovered over as seen in the screenshot below. 

![Icons](https://i.imgur.com/m2PiBxQ.jpg)
![IconsEffect](https://i.imgur.com/8hiVKE5.jpg?1)


* __Beginner's Guide__

Opened when clicking on the "Beginner's Guide" button, it consists of an embedded youtube video where the basics of sailing are shown. The video is fully responsive and the user can play the video directly from the website using the play button on the video. 

![BegsGuide](https://i.imgur.com/km35LFv.png)



* __Location__

Opened when clicked on "Location" in the navigation bar, opens in a new tab that allows for easy navigation. It consists of an iframe with a location of the lessons as well as a short description of the place itself. Contains both a navigation bar and footer.

![Location](https://i.imgur.com/ViYkT5i.png)
![LocationM](https://i.imgur.com/FyqSV1F.png?1)



* __Sign Up__

Opened when clicked on "Sign Up" in a new tab, leads the user to a form where they can sign up for the lessons. It consists of name, email, and phone fields. The navigation bar and footer are also present. The "Set Sail!" button has a hover effect just like the "Sailing Lessons" and "Beginner's Guide" buttons found on the homepage.

![SignUp](https://i.imgur.com/8vhzhe2.png)
  - If the requirements for certain fields are not met, e.g. if the content put into the email field doesn't contain an @ symbol, a warning will pop up on the screen and the user won't be able to submit the form until the requirements are met. 
  ![Email](https://i.imgur.com/yZCrijZ.png)
  - After the user has met all the requirements to successfully submit the form, after clicking on the "Set Sail!" button, the Code Institute formdump website opens and confirms that the form has been submitted successfully. 
  ![FormDump](https://i.imgur.com/PfhQP8J.png)

* __404 Page__

A custom 404 page was added, it contains the header and the footer, as well as a button that leads back to the homepage. 

![404](https://i.imgur.com/ZbdTWpE.png)
![404mobile](https://i.imgur.com/Yexl3I7.png)

* __Favicon__

A favicon of a sailing boat was added to the code for styling purposes. 

![FavIcon](https://i.imgur.com/8wGzq2k.jpg)

* __Media Queries__

Media Query break points used for this website are:

  - max-width:480px for smaller devices such as mobile phones, e.g Huawei P30, iPhone

  - max-width:768px; for iPads and most tablets

  - max-width:992px for most desktop/laptop browsers


## Testing 

Tested the webpage in the following browsers: 
  - Microsoft Edge 
  - Mozilla Firefox 
  - Google Chrome 

Tested the webpage on the following devices: 
  - Huawei P30 
  - Moto G4 (Chrome emulator) 
  - Ipad (Chrome emulator)

Bugs occurred mostly because of my typos, but they were corrected as they were found. According to the Validators, the html and css code is fully functional. The submit button is positioned strangely when on mobile devices, and will be fixed in the next update. There's a possibility of more existing bugs I haven't encountered yet, so those will (hopefully) be squashed when found.

## Defects 
  - CSS smooth scrolling
    - The scrolling on all devices was rather abrupt, therefore it was fixed by adding the scroll-behavior: smooth; property in CSS. 
  - Sailing Lessons scroll goes to an odd spot
    - After fixating the navigation on the top of the page, the Sailing Lessons button lead to an odd place on the page, not the one it was supposed to anyway. It was fixed by adding the scroll-margin-top: 70px; property to CSS stylesheet for desktop and, scroll-margin-top: 70px; and 100px for smaller devices.
  - Form fields too small on mobile
    - The form fields were too small to interact with on mobile, this defect was fixed by adding padding:8px; property for the ids in question within the media query targeting small devices. The form submits button needs further styling which will be done in the next update.

    ![Defect](https://i.imgur.com/Ao8nlu6.png)

    ![DefectFix](https://i.imgur.com/mbHAOJM.png)

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html) 

  - where-to-find-us.html, contact-form and 404.html
![HTMLValidator](https://i.imgur.com/dVCQGex.jpg)

  - index.html didn't return any errors, but 1 warning came back. 
![HTMLVal1](https://i.imgur.com/aXtRn9N.jpg)

- CSS
  - No errors were found when passing through the official [Jigsaw validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

  - results for style.css came back as follows:

  ![Jigsaw](https://i.imgur.com/RnFphkW.jpg)

  - all.min.css (FontAwesome stylesheet)

  ![JigsawII](https://i.imgur.com/rXzeKNT.jpg)

- Lighthouse 
  - index.html results are as follows: 

  ![image](https://i.imgur.com/nY2StGA.jpg)

  - where-to-find-us.html results are as follows: 

  ![location](https://i.imgur.com/KDm0Bqu.jpg) 

  - contact-form.html results are as follows:

  ![contact-form](https://i.imgur.com/DvxyJTk.jpg)
  
  - the custom 404.html results are as follows : 

  ![404](https://i.imgur.com/l41Uypb.jpg)

## Manual Testing

Tested most of the features myself on either emulators or phones, and most of the things work as intended, besides the form defect mentioned above.

### Homepage

- [x] All navigation points go where they should
- [x] All footer links open new tabs because they are not on the website
- [x] No console errors
- [x] Looks nice on tablets 
- [x] Looks nice on desktops
- [x] Looks nice on phones

### Location
- [x] All navigation points go where they should
- [x] All footer links open new tabs because they are not on the website
- [x] No console errors
- [x] iframe is fully responsive
- [x] Looks nice on tablets 
- [x] Looks nice on desktops
- [x] Looks nice on phones

### Form
- [x] All navigation points go where they should
- [x] All footer links open new tabs because they are not on the website
- [x] No console errors
- [x] Looks nice on tablets 
- [x] Looks nice on desktops
- [x] Won't submit the form if requirements are not met
- [x] After successful submission of the form it leads to CI's formdump website

### 404
- [x] All navigation points go where they should
- [x] All footer links open new tabs because they are not on the website
- [x] No console errors
- [x] Looks nice on tablets 
- [x] Looks nice on desktops
- [x] Looks nice on phones



## Deployment

The site was deployed using GitPages, the link is: https://lstipi.github.io/sailing-school-P1/

1. Go to the GitHub Pages https://github.com/lstipi/sailing-school-P1/settings/pages
![image](https://i.imgur.com/Jm2G8SN.jpg)

2.  Selected the main branch and clicked Save
![image](https://user-images.githubusercontent.com/87386883/133104567-f3ad0cbe-f7bf-434f-9203-1957bcda758d.png)

3. You should see the success message and that the site is deployed
![image](https://user-images.githubusercontent.com/87386883/133105121-38bf7b2b-b0f4-496a-a141-b88cbe78bae9.png)


## Credits 


### Content 

- The fonts used are from [Google Fonts](https://fonts.google.com/specimen/Urbanist#pairings)
- Reviewed most of the essential code from [W3Schools](https://www.w3schools.com/)
- Used Stackoverflow forums to double-check code and see what other people did with theirs for inspiration  [Stackoverflow](https://stackoverflow.com/)
- Used Mozilla Dev for checking essential code and just general help [MozzilaDev](https://developer.mozilla.org/en-US/)
- Used this website to help me calculate the units to centre elements [HowToCenterInCss](http://howtocenterincss.com/#contentType=text&horizontal=left&vertical=top)
- Checked for media queries sizes [MediaQs](https://stackoverflow.com/questions/19592968/bootstrap-3-breakpoints-and-media-queries?rq=1)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- The favicon was taken from [Favicon](https://favicon.io/)
- Flex grid from [Flex Grid](https://codepen.io/taniarascia/pen/rOLEGe/)
- This tutorial helped me make the embedded video responsive [Embed a YouTube Video in HTML and Make it Responsive (CSS included)
](https://www.youtube.com/watch?v=9YffrCViTVk)
- Table of content for ReadMe generated from [GitHub Wiki TOC generator](https://ecotrust-canada.github.io/markdown-toc/)
- Fixed odd buttons issue with the help of this [Article](https://stackoverflow.com/questions/11501025/div-anchors-scrolling-too-far)
- Fixed abrupt scrolling with the help of this [Article](https://www.w3schools.com/cssref/pr_scroll-behavior.asp)

### Media

- The main image used on the homepage is from [Pexels](https://www.pexels.com/photo/blue-boats-daylight-island-358326/)

## Acknowledgments 

- A huge thank you to my mentor Malia Havlicek for helping me with this project. 


