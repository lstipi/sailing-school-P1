# Sailing School

Hi, welcome to my Sailing School project!

The initial idea was to set up a web site for a sailing school, focused on begginer's lessions for children. I wanted the design to be minimalistic, easy to navigate and comprehend, which was (hopefully) achieved in this project. The webiste is designed for parents that wish to sign their children up for sailing lessons. Keeping in mind that the intended user might not be tech savvy and needs a simple website that does what it says, the design for this project was achieved. The colours were picked out as an attempt to emulate the colours of the Adriatic see and to give the user a feeling of being at see. 

[Deployed URL](https://lstipi.github.io/sailing-school-P1/)

![Central image](https://i.imgur.com/uZ7OKci.jpg)


## Features

The project requirements were to use HTML and CSS to do so, therefore the initial document was index.html linked with a style.css spreadsheet. The idea for index.html was to have a nav bar above an image with 2 buttons in the center of the image. The navigation bar consists of a logo on the left and the links to where-to-find-us.html and contact-form.html, while the buttons in the centre lead to begginer's guide.html and the timetable displayed under the central image in index.html. The main colors of the project are various shades of blue and white, to achieve good visibility. 
To achieve the minimalistic style, I didn't add a lot of text, nor features, just the basic information about the sailing club accompanied by a timetable of the sailing lessons on index.html, basic instructions on how to reach the location on where-to-find-us.html, and a form where t is possible to sign up in the contact-form.html. 

### Existing Features


* __Navigation Bar__ 

The navigation bar is present on all other html files (with exception to begginer's-guide.html), it consists of 4 items, a logo that leads back to index.html, and a Home, Location and Contact Us clickable links that lead back to index.html, as well as where-to-find-us.html and contact-form.html. It is responsive and allows the user to navigate between the pages easily on all devices, ranging from a phone to a desktop. 

![NavBar](https://i.imgur.com/1AIUerY.jpg)


* __Set Sail__ 

The Set sail section consists of an background image of sailboats on the sea and in the centre of the image are two buttons. The first button Sailing Lessons leads directly to the timetable further down the page, while the Begginer's guide opens begginers-guide.html in a new tab. The begginers-guide.html consists of an embbeded youtube video where the basics of sailing are described. 

![SetSail](https://i.imgur.com/SaUdCHW.jpg)


* __About Us__

The About Us section gives a brief description of when the sailing club was founded and what it's goals are. 

![AboutUs](https://i.imgur.com/ehVIzvH.jpg)



* __Timetable__

The Timetable section contains a table of times when lessons are happening throughout the week. If the time of the lesson changes, the table will be updated and members will be notified.

![Timetable](https://i.imgur.com/kvchy3W.jpg)



* __Footer__

The footer conists of icons which when clicked lead to Twitter, Instagram and Facebook and are opened in a new tab for easy navigation. 

![Footer](https://i.imgur.com/LNnxIC0.jpg)



* __Beginner's Guide__

Opened when clicking on the "Beginner's Guide" link, the begginers-guide.html consists of an embbeded youtube video where the basics of sailing are shown. 

![BeginnersGuide](https://i.imgur.com/DsCEYS5.jpg)



* __Location__

Opened when clicked on "Location" in the navigation bar, opens in a new tab that allows for easy navigation. It consists of an iframe with a location of the lessons as well as a short description of the place itself. Contains both navigation bar and footer.

![Location](https://i.imgur.com/TCGCt3P.jpg)



* __Sign Up__

Opened when clicked on "Sign Up" in a new tab, leads the user to a form where they can sign up for the lessons. It consists of name, email and phone fields. Navigation bar and footer are also present. 

![SignUp](https://i.imgur.com/UL7yvDV.jpg)

## Testing 

Tested the webpage in Microsoft Edge, Mozzila Firefox and Google Chrome and everything works as intended. 

Bugs occured mostly because of my typos, but they were corrected as they were found. According to the Validators, the html and css code is fully functional. There's a possibility of existing bugs I haven't encountered yet, so those will (hopefully) be squashed when found.

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html) (a few warnings were, not sure if that counts)
- CSS
  - No errors were found when passing through the official [Jigsaw validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

## Deployment

The site was deployed using GitPages, the link is :

1. Go to the GitHub Pages https://github.com/lstipi/sailing-school-P1/settings/pages
![image](https://user-images.githubusercontent.com/87386883/133104257-d6750715-56c1-4264-abc6-85d112a69527.png)

2.  Selected the main branch and clicked Save
![image](https://user-images.githubusercontent.com/87386883/133104567-f3ad0cbe-f7bf-434f-9203-1957bcda758d.png)

3. You should see the success message and that the site is deployed
![image](https://user-images.githubusercontent.com/87386883/133105121-38bf7b2b-b0f4-496a-a141-b88cbe78bae9.png)


## Credits 


### Content 

- The fonts used are from [Google Fonts](https://fonts.google.com/specimen/Urbanist#pairings)
- Reviewed most of the essential code from [W3Schools](https://www.w3schools.com/)
- Text after iframe and positioning on beginners-guide.html from [Post](https://stackoverflow.com/questions/35877796/text-after-iframe)
- Used Stackoverflow forums to double check code and see what other people did with theirs for inspiration  [Stackoverflow](https://stackoverflow.com/)
- Used Mozilla Dev for checking essential code and jsut general help [MozzilaDev](https://developer.mozilla.org/en-US/)
- Used this website to help me calculate the units to centre elements [HowToCenterInCss](http://howtocenterincss.com/#contentType=text&horizontal=left&vertical=top)
- Checked for media queries sizes [MediaQs](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- Relied heavly on lessons in the course and the Love Running project

### Media

- The main image used on the homepage is from [Pexels]([https://www.pexels.com/photo/blue-boats-daylight-island-358326/)




