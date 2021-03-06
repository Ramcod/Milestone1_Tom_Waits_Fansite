# The Tom Waits Fansite

## Milestone 1 Project by Richard Martin

### The site has been designed as a place where Tom Waits fans can enjoy the latest news and watch, or listen to, recordings. It is designed for those who are familiar with his work or those who have never come across him before.

## User Experience (UX)

### - First Time Visitor Goals

- The aim of the site is for users who have not encountered Tom Waits, to get a clearly mapped out experience that would enable them to easily navigate between pages and to be able to intuitively visit the review sections and to watch video recordings.

-  With a great user experience I would hope that people would then fill out the subscribe form which would enable them to keep updated on the news feed. If they didn't it may be that they don't like Tom Waits, rather than my website!

- I decided to use this great black and white image to see the man behind the voice.

- Home page hero image

 ![Tom Waits hero image](assets/images/hero.jpg)

### - Returning and Frequent Visitor Goals

- I would like returning visitors and frequent users to be able to input ideas on the comments section of the subscribe page. It may take the eventual form of a forum and would give users the opportunity of sharing their own news of any forthcoming events or releases.

- I would like to share the opportuntiy for contributors to create a newsletter to be shared with subscribers on a quarterly basis.

### -Design

- I have used Bootstrap v4.6 to support the design of the navbar and social media links. Each page is responsive and I have chosen slightly different themes for each page but stayed with the same colour schemes on each. I have chosen a font that I feel represents some of Tom Waits' work. The navbar and footer with social media buttons are consistent throughout each sheet.

- For the 'Home page' I used a jumbotron to give an insight into the artists' work and a suitable hero image. I also chose to have two columns hosting news updates, and the other with his quotes. As the news stream will be updated constantly, I have incorporated a scroll for the overflow.

- For the 'Tom's Discs' page I used Bootstrap cards which allowed me to insert pictures of the albums and a mini review of each. I decided on a row for each card to appreciate the artwork of the album, and which would stll look good on mobile. After the reviews there is a button that once selected, will take you to a wikipedia page on that album.

- For the 'Tom Live' page I wanted to give some full width previews of old footage which was embedded from YouTube and gives the site user a great example of Tom's finest live work.

- The 'Subscribe' page gives users the opportunity to sign up for a newsletter. The subscribe button will refresh the page and so is for demonstration purposes to show the button works at the moment.

#### - Colour Scheme

- I have used bg-dark navbar-dark (Bootstrap 4.6) for the navbar, a colour of 'Gray' for the footer which contains FontAwesome social media buttons. I chose 'Goldenrod' for outlining paragraph text.
 
#### - Typography

-  Black fonts are throughout and the font family is : 'Azerat Mono', monospace; which have been taken from Google fonts. I felt that they suited the type of artist that Tom Waits is and reflects some of the work that he has previously completed.

#### - Imagery

- There are a number of very striking shots available for Tom Waits but not all of them were of a suitable size or resolution. Choosing the B & W shot of him for the hero image on the Home Page, represented what I wanted the site to be about and reflected his music quite well. All of the images used are stored in the repo- /workspace/Milestone1_Tom_Waits_Fansite/assets

### - Wireframes

-Wireframe for the subscribe page

 ![Moto 4](documentation/project_assets/wireframe_subscribe_page.png)


-Wireframe for the Homepage on iPad

 ![Homepage on iPad](documentation/project_assets/homepage_wireframe_for_ipad.png)


-Subscribe Wireframe- 

Wireframe for the tom_live page on mobile

 ![tom_live mobile](documentation/project_assets/wireframe_tom_live.png)

## Features

- Interactive elements where you can view album covers close up and click to watch YouTube videos of old recordings.

- Responsive. I have had issues with that element of the site but now using Bootstrap v4.6 has resolved the issues.

- The site features easy navigation links at the top of each page which enable users to find each page easily.

- You can click on the 'view tracklisting' button on toms_discs.html which will take you to a seperate wikipedia page with full details of each album.

- There are social media buttons on each page that take you to Tom Waits social media accounts. They all open to a blank page.

- The subscribe form has a subscribe button that will refresh the form once selected. 

## Technologies Used

I have used;

- Github
- Gitpod
- Bootstrap v4.6
- CodePen to trial different looks and functionality


### Languages Used

- HTML5 https://en.wikipedia.org/wiki/HTML
- CSS3 https://en.wikipedia.org/wiki/CSS

### Frameworks, Libraries and Programs Used

-Google Fonts | https://fonts.google.com/ which enabled me to import the chosen fonts for the project.

-Font Awesome | https://fontawesome.com/ which allowed me to import the social media icons for links in the footer.

-Git Hub | https://github.com/ This is the site that is used for storing projects that are commited and pushed from Git Pod.

-Git Pod | The program that the README.md file is being written in as well as all of the HTML5 and CSS3 files. 

-Balsamiq | https://balsamiq.com/ This site enables you to create Wireframes at the point of inception and you can share projects based on different price plans. This therefore allows collaborative working in the design process.

-Bootstrap v4.6 | This library has helped me to make my site responsive and understand the importance of mobile first design. I have used this througout the design process.

## Testing

- At the start of the project I encountered a lot of issues with GitPod and GitHub. I was unable to Git Push and I had also made some mistakes in the terminal when putting in commands. I found that by revisiting the training modules that I was able to get a better understanding of some of the bugs that sometimes occured and how to best use the command line.

- To test each HTML5 file I used https://validator.w3.org/ which provided me with where errors occured and helped me to pinpoint correcting them.

- index.html validation screenshot

 ![html validation](documentation/project_assets/tom_waits_index.html_validator.png)

 - toms_discs.html validation screenshot

 ![toms_discs](documentation/project_assets/toms_discs_html_checker.png)

 - toms_live.html validation screenshot

 ![toms_discs](documentation/project_assets/tom_live_html_validator.png)

 - subscribe.html validation screenshot

 ![subscribe](documentation/project_assets/tom_waits_subscribe.html_validator.png)

- To test the CSS3 file I used the W3C CSS validation service

 ![css](documentation/project_assets/css_validator.png)



-After initial testing of the site there were 2 main issues in the responsiveness and the contrast on a lot of the body text. The body text was corrected by removing the opacity on all sections. To fix the responsiveness I used Bootstrap v4.6 to construct classes that would collapse or grow between smaller and larger devices.

### Testing From User Experience (UX) Section

-User feedback from colleagues has been positive since the responsiveness issues have been sorted but there were some comments on the follwoing which I have since corrected;

- Some of the spacing of paragraphs was a little close to the edge of the page and so the padding was looked at and corrected in each case.

- The color scheme was too dull for one user who had colour vision issues and so a brighter scheme was chosen to compensate.


### Further Testing

- I have asked colleagues to visit the site on both laptop and mobile to ensure that each feature works and that the site is viewable for each device. They have reported no bugs and that all of the expected functionality is there.

### Known Bugs

- There have been issues with getting the HTML files to load the CSS and I have checked the file path names on numerous attempts. All files have been validated through the W3C Validation Service.

- There are issues with the responsive of the design which still requires further work as of 25/10/2021. As of 4th November all files are now responsive owing to utilising the repsonsive Bootstrap classes.

## Deployment

- The site has been tested to check for a suitable user experience and here is evidence of how the site works on the following browsers.

- The home page and how it looks on Google Chrome


![Google Chrome](documentation/project_assets/home_page_in_google_chrome.png)



- The home page and how it looks on Microsoft Edge

![Microsoft Edge](documentation/project_assets/home_page_microsoft_edge.png)


- The home page and how it looks on Firefox


![Microsoft Edge](documentation/project_assets/home_page_firefox.png)

### GitHub Pages

- Here you can find the project repo. https://github.com/Ramcod/Milestone1_Tom_Waits_Fansite 

### Forking the GitHub Repository

- "A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.

Most commonly, forks are used to either propose changes to someone else's project or to use someone else's project as a starting point for your own idea. You can fork a repository to create a copy of the repository and make changes without affecting the upstream repository. 

- You can propose changes to someone else's project.
For example, you can use forks to propose changes related to fixing a bug. Rather than logging an issue for a bug you've found, you can:
  
  * Fork the repository.
  * Make the fix.
  * Submit a pull request to the project owner."


### Making a Local Clone

- To make a clone on your PC, in case of any issues online, you can follow this set of instructions that guides you visually through the process.

    * ### Local Deployment

If you would like to make a clone of this repository, you can type the following command in your IDE terminal:

- `git clone https://github.com/Ramcod/Milestone1_Tom_Waits_Fansite.git`

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/Ramcod/Milestone1_Tom_Waits_Fansite)

### Content

- All content was created by Richard Martin

- Subscribe form was influenced by and adapted from https://www.w3schools.com/howto/howto_css_responsive_form.asp

### Media

- All images were taken from various locations across Google Chrome. I have saved copies locally and also saved them to the repo in /workspace/Milestone1_Tom_Waits_Fansite/assets/images.

### Acknowledgements

- There have been a number of useful resources that are available and they have included the following;

- https://www.w3.org/ which has a huge amount of resources that give a reminder of a piece of code, or to help you with something brand new.

- https://htmlcheatsheet.com/ really helps as a bright visual revision tool and you can even try things out in there.

- https://getbootstrap.com/docs/4.6/getting-started/introduction/ which has really been useful in getting the site to be more responsive whilst still allowing me to put in my own creative elements to the site.

- The video tuition of Code Institute

- There are various sources of content online and with some text books I have been reading and I plan to change my approach slightly for milestone 2, which will enable me to experiment more and consolidate my knowledge.
