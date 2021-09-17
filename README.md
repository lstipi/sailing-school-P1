# Sailing School

Hi, welcome to my Sailing School project!

The initial idea was to set up a web site for a sailing school, focused on begginer's lessions for children. I wanted the design to be minimalistic, easy to navigate and comprehend, which was (hopefully) achieved in this project. The webiste is designed for parents that wish to sign their children up for sailing lessons. Keeping in mind that the intended user might not be tech savvy and needs a simple website that does what it says, the design for this project was achieved. The colours were picked out as an attempt to emulate the colours of the Adriatic see and to give the user a feeling of being at see. 

[Deployed URL](https://lstipi.github.io/sailing-school-P1/)

![Central image](https://i.imgur.com/cZDY0Ux.jpg)

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

The project requirements were to use HTML and CSS to do so, therefore the initial document was index.html linked with a style.css spreadsheet. The idea for index.html was to have a nav bar above an image with 2 buttons in the center of the image. The navigation bar consists of a logo on the left and the links to where-to-find-us.html and contact-form.html, while the buttons in the centre lead to begginer's guide.html and the timetable displayed under the central image in index.html. The main colors of the project are various shades of blue, ranging from paler shades to darker shades, to achieve good visibility. 
To achieve the minimalistic style, I didn't add a lot of text, nor features, just the basic information about the sailing club accompanied by a timetable of the sailing lessons on index.html, basic instructions on how to reach the location on where-to-find-us.html, and a form where t is possible to sign up in the contact-form.html. A custom 404 page was added as well.

### Existing Features


* __Navigation Bar__ 

The navigation bar is fixed and present on all other html files, it consists of 4 items, a logo and Home that lead back to index.html, Location that leads to where-to-find-us.html, and Sign Up that leads to contact-form. It is responsive and allows the user to navigate between the pages easily on all devices, ranging from a phone to a desktop. 

![NavBar](https://i.imgur.com/QhlO55e.jpg)


* __Set Sail__ 

The Set sail section consists of an background image of sailboats on the sea and in the centre of the image are two buttons. The first button Sailing Lessons leads directly to the About Us further down the page, while the Begginer's guide button leads to the Beginner's guide section on the very bottom of the page. 

![SetSail](https://i.imgur.com/SaUdCHW.jpg)

Buttons also have a hover animation as can be seen in the screenshots below.

![Buttons](https://i.imgur.com/ENe81YS.jpg?4)
![ButtonsHover](https://i.imgur.com/DkzfHTs.png?2)


* __About Us__

The About Us section gives a brief description of when the sailing club was founded and what it's goals are. 

![AboutUs](https://i.imgur.com/rKjviNs.jpg)



* __Timetable__



The Timetable section contains a table of times when lessons are happening throughout the week. If the time of the lesson changes, the table will be updated and members will be notified.




![Timetable](https://i.imgur.com/cYXo0JQ.jpg)



* __Footer__

The footer conists of icons which when clicked lead to Twitter, Instagram and Facebook and are opened in a new tab for easy navigation. 

![Footer](https://i.imgur.com/sNgLFqf.jpg)

Icons are animated when hovered over as seen in the screenshot below. 

![Icons](https://i.imgur.com/m2PiBxQ.jpg)
![IconsEffect](https://i.imgur.com/8hiVKE5.jpg?1)


* __Beginner's Guide__

Opened when clicking on the "Beginner's Guide" button, it consists of an embbeded youtube video where the basics of sailing are shown. 

![BegsGuide](https://i.imgur.com/pwGPjzY.jpg)



* __Location__

Opened when clicked on "Location" in the navigation bar, opens in a new tab that allows for easy navigation. It consists of an iframe with a location of the lessons as well as a short description of the place itself. Contains both navigation bar and footer.

![Location](https://i.imgur.com/dssP49D.jpg)



* __Sign Up__

Opened when clicked on "Sign Up" in a new tab, leads the user to a form where they can sign up for the lessons. It consists of name, email and phone fields. Navigation bar and footer are also present. 

![SignUp](https://i.imgur.com/M0AqkUq.jpg)

* __404 Page__

A custom 404 page was added, it contains the header and the footer, as well as a button that leads back to the homepage. 

![404](https://i.imgur.com/jtZk6JI.jpg)

* __Favicon__

A favicon of a sailing boat was added to the code for styling purposes. 

![FavIcon](https://i.imgur.com/8wGzq2k.jpg)

## Testing 

Tested the webpage in Microsoft Edge, Mozilla Firefox and Google Chrome and everything works as intended. 

Bugs occured mostly because of my typos, but they were corrected as they were found. According to the Validators, the html and css code is fully functional. There's a possibility of existing bugs I haven't encountered yet, so those will (hopefully) be squashed when found.

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html) 

  - where-to-find-us.html, contact-form and 404.html
![HTMLValidator](https://i.imgur.com/dVCQGex.jpg)

  - index.html didn't return any errors, but 1 warning came back. 
![HTMLVal1](https://i.imgur.com/aXtRn9N.jpg)

- CSS
  - No errors were found when passing through the official [Jigsaw validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

  ![Jigsaw](https://i.imgur.com/RnFphkW.jpg)

 - Lighthouse 
  - index.html results are as follows: 
  ![image](https://i.imgur.com/nY2StGA.jpg)

  - where-to-find-us.html results are as follows: 
  ![location](https://i.imgur.com/KDm0Bqu.jpg) 

  - contact-form.html results are as follows:
  ![contact-form](https://i.imgur.com/DvxyJTk.jpg)

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
- Used Stackoverflow forums to double check code and see what other people did with theirs for inspiration  [Stackoverflow](https://stackoverflow.com/)
- Used Mozilla Dev for checking essential code and just general help [MozzilaDev](https://developer.mozilla.org/en-US/)
- Used this website to help me calculate the units to centre elements [HowToCenterInCss](http://howtocenterincss.com/#contentType=text&horizontal=left&vertical=top)
- Checked for media queries sizes [MediaQs](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- The favicon was taken from [Favicon](https://favicon.io/)
- Flex grid from [Flex Grid](https://codepen.io/taniarascia/pen/rOLEGe/)
- This tutorial helped me make the embedded video responsive [Embed a YouTube Video in HTML and Make it Responsive (CSS included)
](https://www.youtube.com/watch?v=9YffrCViTVk)
- Table of content for ReadMe generated from [GitHub Wiki TOC generator](https://ecotrust-canada.github.io/markdown-toc/)

### Media

- The main image used on the homepage is from [Pexels](https://www.pexels.com/photo/blue-boats-daylight-island-358326/)

## Acknowledgments 

- A huge thank you to my mentor Malia Havlicek for helping me with this project. 


