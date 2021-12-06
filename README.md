# Girl On Earth.
![logo](assets/ref-images/logo.png)
## Table of Contents
1. [About](#about)
2. [Users Experience (UX)](#user-experience)
3. [Design](#design)
4. [Features](#feature)
5. [Technologies Used](#Technologies-used)
6. [Troubleshooting](#Troubleshooting)
7. [Testing](#testing)
8. [Debugging](#debugging)
9. [Deployment](#Deployment)
10. [Credits](#credits)

![Am I responsive](assets/ref-images/Am-I-responsive.png)

## 1. About

GirlOnEarth. is a website created for a female meet-up group. The purpose of the group is to gather like-minded female individuals sharing the same values and metaphors about life, empowering each other to live their life to the maximum, dream big and trive! 

I have moved to Ireland since the age of 20, ever since then I have been busy surviving, studying and working, having a family and raising kids, it has been non-stop. Until Covid hit in March last year, everything has paused, finally, I relized that I haven't been living my life (the life we all get to live for once and only once!) It was the awakening moment of my life, from then my focus was shifted onto self-love, self-improvement, mindfulness...   

So, there you go! As a single mother , a beautician, and a person that right in the middle of the awakening moment, I came up with this idea for my Milestone project 1 for the full stack web development course at [code institute](https://codeinstitute.net/). 

Main requirements
* Write custom HTML5 and CSS3 code to create a website of at least 3 pages, or (if using a single scrolling page), at least 3 separate page areas.
* Incorporate a main navigation menu and structured layout.
* Incorporate a main navigation menu and structured layout and use Git & GitHub for version control.

Live project website can be accesed [here](https://melindazhang2020.github.io/CI-MS1-GirlOnEarth/).

Repository for this project can be accesed [here](https://github.com/MelindaZhang2020/CI-MS1-GirlOnEarth.).


## 2. Users Experience (UX)


#### 2.1 Users stories

As a user and a woman with high living standards, my goal is to live a substainable life, my aim is to find a like-minded group of people, so that I can surround myself with people who can inspire, activate and uplift me.


#### 2.2 The Five Planes of UX

* ##### Strategy Plane

  **The aim** is to attract women with the same mindset to join the group to form a community filled with positive energy, inspire and uplift each other, and to serve the bigger community we live in.

  **The target audience** is female individuals that have a strong mindset, knowing what they want to achieve in life and aiming to live their life to the maxmium.

* ##### Scope Plane

  **The home page** should include an eye catching feature with an insparational metaphors to draw users attention immediately. **The passions section** should include a few of the topics around daily life that would interest our female audience. It would be ideal if there are acticles linked to this section, but for now the page can just include a basic scope. Articles can be added as the page grows. **The Acitivities** section should be divided into 3 columns, with a round shape image clearly tell the users what is happening on a regular basis. **The contact page** should include a form so that the user can get in touch with us.

* ##### Structure Plane
  
  The page is going to a single page with five sections, with a header containing a brand image, a brand name and a navigatiion bar. The home page section structured on the top of the page, followed by an about section to clarify what this page is about. The next section is divided by six topics displayed with images and quotes. The following is the activities section, it's a section with 3 columns clearly laid out. Then finally there is a contact form for the users to fill up if they are interested to join in the group. The page ends with a footer that has social links and copyright information.

* ##### Skeleton Plane
  The goal is to achieve a clean visual effect for the entire page with as little text as possible, using simple and calming images to deliver the "go with the flow" effect. The navigation system should be simple and clear, with five sections fixed on the top of the page. When the users click a navigation section, it will bring them straight to the relevant section. You can find a wireframe draw-up in the Mockups section.

* ##### Surface Plane
  Because our audience is female, our color theme will be light and girly, images should be feminine, and fonts will also be delicate. Minimise the content is the goal, to create a calming sensation throughout the page.

## 3. Design


#### 3.1 Colours

![pallette 1](assets/ref-images/ms1-color-pallette1.png)
![pallette 2](assets/ref-images/ms1-color-pallette2.png)
![pallette 3](assets/ref-images/ms1-color-pallette3.png)

The above color pallate will be the main color theme throughout the page. 

#### 3.2 Typography

"Architects Daughter", "Bungee Outline", "Teko", "Yanone Kaffeesatz", "Fredericka the Great","Audiowide","Shadows Into Light","Yanone Kaffeesatz", "Fredericka the+Great" and "Yusei Magic" are the fonts I used throughout the page. These are all from [Google Font](https://fonts.google.com/).

#### 3.3 Imagery
Througout the project, I am aiming for images that have natural color, easy on the eyes, to create a soothing sensation.
Please see in the credit section for links to images sources.

#### 3.4 Mockups

Please see the wireframes 
[here.](assets/wireframes/ms1.pdf)

## 4. Features

#### 4.1 Existing Features

The site is a one-page site divided by five sections, including *home*, *about*, *passions*, *acitivities*, and *contact*. The layout of the page is completed by its responsive navbar, footer and two dividers to ensure a balanced visual effect.
* #### Navbar
  The responsive navbar has been achieved by implementing Bootstrap 4, it collapes into a button when the screen is smaller than 990px. It contains links to all sections, and the logo of the page. The logo is also used as a homepage link.
* #### Homepage
  The homepage contains a main image, a title quote and a button. I used CSS animation to make the quote slide from left to right as soon as the page loads, then the button "start now" appears 3 seconds later. The aim here is to grab users' attention to make the site appealing.
* #### About
  The about section contains two images and the a paragraph describing what the page is all about, so the users can have a clear view of what they can get from using the page. The section's visual effect is achieved by using CSS position and overflow.
* #### Passions 
  This section contains 6 images and a title with a quote, explaining what topics the group is focusing on, to give the user a general idea about the passions that we might have in common. I used CSS grid to make this section completely responsive for all different screen sizes.
* #### Acitivities
  This section gives the user an idea about what acitivities we are going to do together to reach our goals. It contains 3 small sections with an image, time and place each event is happening. 
* #### Contact
  The contact section contains a form which gather's users informaton, including users' first and last names, email address and a text field for them to leave a message. A submit button is also included. Although at the moment, there's no backend attached to the site, but by the time I finish this course, I would be able to implement such a feature.
* #### Dividers
  There are two individual dividers to separate the page into sections. Inside each divider, there's a motivational quote.
* #### Footer
  The footer has been divided into two sections, which is social icons links and copyright. 

#### 4.2 Features Left to Implement

* As the course progress, I would love to add additional features to this page, for example, adding interesting acticles and links into each passions. I would also add a section to subscribe users onto an email list, so whenever there's an update on the page or new articles, they will be notified. All the backend features will be implemented by the time I finish this course, such as users' information etc.
* I would love to add a function that when the user hovers on the quotes in the passions section a button with "read more" shows up and when clicked, it leads them to different pages such as Tony Robbins, Dr. Joe Dispenza as I would love to share the information and knowledge I have learned and inspired me so far.

## 5. Technologies Used

#### 5.1 Languages Used

* HTML/HTML5 provides basic Structure of the website.
* CSS/CSS3 provides colors, layout and visual effect of the page.

#### 5.2 Frameworks, Libraries and Programs Used

* [Bootstrap4](https://getbootstrap.com/) - helped created a responsive navbar and some sections structures throughtout the page.
* [Gitpod](https://gitpod.io/) - README, git version control and  all code was written in Gitpod using code institute gitpod full template.
* [GitHub](https://github.com/) - hosting service to save the project in a repository.
* [Balsamiq](https://balsamiq.com/) - used to draw up the wireframes.
* [TinyPNG.com](https://tinypng.com/) - used to compress large images.
* [Google Font](https://fonts.google.com/) - used to import the following fonts Architects+Daughter, Audiowide, Bungee+Outline, Fredericka+the+Great, Shadows+Into+Light, Yanone+Kaffeesatz, Fredericka+the+Great and Yusei+Magic.
* [font awesome](https://fontawesome.com/) - used for footer icons.
* [coolors.co](https://coolors.co/) - used to color scheme.
* [Am I responsive?](https://ami.responsivedesign.is) - used to check responsivity of code and display the mock up in the documentation.
* [W3C Markup Validation Service](https://validator.w3.org/) - used to validate HTML codes.
* [W3C CSS Validation service](https://jigsaw.w3.org/css-validator/) - used to validate CSS codes.
* [RGBA and Hex Color Converter](https://cssgenerator.org/rgba-and-hex-color-generator.html) - used to convert hex color to RGBA color.
* [The Complete Web Developer in 2021: Zero to Mastery](https://www.udemy.com/course/the-complete-web-developer-zero-to-mastery/) - I started this course last year before I enrolled with Code Institute, one of the codes I used in this project was from this course.
* [freeCodeCamp](https://www.freecodecamp.org/) - used this site to learn coding last year, and I used it for reference.
* [Diffchecker](https://www.diffchecker.com/) - used to compare codes.
* [Autoprefixer](https://autoprefixer.github.io/) - used to add autoprefixer for improving browser compatibility.
* [Chrome Devtools](https://developers.google.com/web/tools/chrome-devtools) - used throughout the project to inspect on elements and writing codes.

## 6.Troubleshooting

Througout the process of this project, I have encounter a good few troubles, and that was where the real learning begins! Breaking through the following couple of examples were frustrating but fun:

* I first used Bootstrap for the navbar, the collapse button didn't work for me, I couldn't find a solution for it. So I decided to write my own codes. I googled "responsive navbar" on youtube, and found [CodingNepal](https://www.youtube.com/c/CodingNepal)'s code is easy to understand, so I learned it and used it in my project.
But when I applied it to my own codes, the collapes button didn't work for me again! I was stuck with it for a couple of days, using the inspect Devtools over and over trying to find where the problem was, and finally... I found out that it was the light background color made it nearly invisible, and also it showed up behind the cover image. I used z-index property to solve that issue.

* Trying to solve the problem of "the navbar items doesn't direct user to the correct section of the page, as it only shows half of it". I googled for solution for this problem, found it [here](https://css-tricks.com/hash-tag-links-padding/). But applying it to my own code wasn't very easy, I spent two days changing around the codes and finally got it.


## 7. Testing

* Testing tools 

    * Macbook Air used for large screen testing.
    * Huawei T1-821 tablet used for medium size screen testing.
    * Huawei P10 and Sumsumg galaxy 10 used for small screen testing.

* Chrome DevTools - used to see responsive and mobile design previews, applying and optimising CSS rules and targeting HTML elements and their behaviour.

* Asked family and friends to check the page on their computers and mobile phones.
* Tested on Google Chrome, Firefox, Internet Explorer, and Safari web browser.

* Functionality testing - 

    * tested all the navbar links, made sure it connects to relevant sections.
    * tested the collapse button after screen size reduces, to make sure when clicked, it opens up a slide menu of navigatiion options. And also that navigation links bring the user to the relevant section.
    * tested the logo link is working, so that when clicked, it refreshes the cover page.
    * tested the "start now" button is linked to the contact section, and that when clicked, it brings the user to the contact form section.
    * tested all the social links are linked to the relevant social media page.
    * tested the developer's name is linked to her github page.

* Responsiveness testing - 

    * tested on Chrome Devtools by dragging the page edge and reducing the viewport size, scrolling to each section to see any issues.
    * tested on [responsive viewer](https://chrome.google.com/webstore/detail/responsive-viewer/inmopeiepgfljkpkidclfgbgbmfcennb) by Google Chrome browser extensions.
    
* Testing User Stories 

    The following examinations were carried out to address user needs:

    * Users are looking for navigating around the page easily - there is a navigation system has been set up and easy to follow, so that the user will know how to use it straight away after opening the website. i.e. the navbar layout, position and visual aspect. The navbar is fixed to the top of the page, so even when the user scrolls to the bottom of the page, they can easily get back to any section if they would like to.
    * Users are looking for a page with a clear layout set up that is not too busy or too much going on - the entire page is clearly laid out into different sections, with the most important content at the very top, i.e. the cover section, about section, divider section with quotes, passions section, divider section with quote and lastly the contact section.
    * Users want to have a basic idea what the page is about as soon as they open up the page - the user will grasp the main concept of the page as soon as they open up the page, i.e. the quote on cover section with the animation effect grabs the users attention immediately.
    * Users would like to know more about what the page is about as they scroll further down the page - the user gets a better idea of what this page is about, by scrolling down to the next section which is the about section. A short paragraph explains further what this page is all about.
    * Users want to know what area or topics the group is going to focus on and what can they learn from it - The passions section further develops on what topic and areas the group is focusing on. That also gives the user a rough idea about what kind of people they'd expect to meet if they are interested in joining in.
    * Users would like to know if there's any activities happening within the group to get socialable, if they can make friends and go on a learning journey together - the activities section shows the user that there are events going on in the group that they can join. If that's something they would interested in, the options is there.
    * Users are expecting to see contact information if they are interested, that is easy to fill in - the contact section gives the user exactly what they need. There is a form with only three inputs of basic personal infomation where they can get connected to like-minded people and grow together instantly!
    * Users would generally expect social links within the page, so that they can connect that way if they want to - in the footer section the social media links are avaiable. 
    
#### 7.1 HTML5 validator

![HTML Validator Service](assets/ref-images/html-validator.png)
The above errors has been found through HTML validator service and they have been corrected.

#### 7.2 CSS3 validator

![CSS Validator Service](assets/ref-images/css-validator.png)
The above error was found through CSS validator service and I have managed to fix number 4.

## 8. Debugging
* The nav items only direct the user to half of the page in each relevant section due to the fixed nav bar.

  I searched around on google for this issue and found a solution [here](https://css-tricks.com/hash-tag-links-padding/), but apply it into my own code was tricky, I was playing with the code for a couple of days, finally it worked for me.
* When hover over, the social icons in the footer shows a white background that it wasn't suppose to be there. See photo below.

  ![debugging image](assets/ref-images/debugging-image-1.png)

  My mentor Allen gave me some suggestions that I should give each element a specific class instead using multipy css selector method like .social-links li a {}. I renamed the element class, and that solved the problem.

* The contact form didn't show Validation if the user leave it blank and just press the "submit" button.

  I changed the "type" attribute to "submit" and that problem was solved.

* The main page has a gap on the right hand side, when slide the mouse over, the whole page moves.
  
  It showed me that there is some parts of the page's content is bigger that its box model, to solve that problem, I applied the following code:
  > `*` { border: 1px solid red; } 

  to all elements in the body section and it gave me a clearer visual effect where exactly was the problem.

## 9. Deployment

**Deployment via GitHub Pages**

1. Select the Repository you wish to deploy.
2. Under the "Repo" name on the top left of the screen there is a menu, select the settings tab on this menu.
   ![see photo](assets/ref-images/deploy-image-1.png)
3. Scroll down to the GitHub Pages section.
4. Under Source use the None or Branch drop down menu to select the publishing source you wish to use.
    Master is recommened. 
    ![see photo](assets/ref-images/deploy-image-2.png)
    ![see photo](assets/ref-images/deploy-image-3.png)
5. Select Save and refresh the page.
6. Your published address will appear in a green highlighted container above Source.
7. Click the link to test it works.

## 10. Credits

#### 10.1 Content

* I came up with all the content myself, got the inspiration and quotes from [success.com](http://success.com) and [personalexellence.com](http://personalexellence.com).
* The reponsive navbar codes was taken from youtube channel [CodingNepal](https://www.youtube.com/c/CodingNepal)'s [responsive navbar video](https://www.youtube.com/watch?v=oLgtucwjVII) and changed some of the codes to make it my style.
* The passions section used CSS grid, the code for its reponsiveness is taken from [Zero to Mastery](https://www.udemy.com/course/the-complete-web-developer-zero-to-mastery/) course on Udemy.
* The footer social link codes was taken from Code Institute video [Rosie's Resume](https://www.youtube.com/watch?v=r9QC_imtw9A).
* Througout the project, I have watched many youtube videos to help me learn specific topics, the youtube channels that inspired me are: [Web Dev Simplified](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw), [DevEd](https://www.youtube.com/c/DevEd), and [Traversy Media](https://www.youtube.com/c/TraversyMedia).

#### 10.2 Media

* all photos was downloaded from the follow website:
    [unsplash](https://unsplash.com/)
    [pexels](https://www.pexels.com/)
    [pixabay](https://pixabay.com/)
    [icons8](https://icons8.com/)

#### 10.3 Acknowledgements

I would like to thank:

*  my mentor Allen Thomas Varghese for the useful tip, recommendations and support.
*  the tutor support team for the rapid respond each time when I submit a question.
*  everyone who help me in the Slack community for their kindness and generosity.

And if anyone have any questions regarding to this project you can reach me on melinda_hongye@yahoo.com.







