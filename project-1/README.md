# Milestone Project 1

## Portfolio / Resume Project

### 🎯 Strategy: 

I have decided that I will build a Resume / Portfolio website. The reason I have decided to do this project from the list of Project examples supplied by the course, is that I have made 3 other portfolio websites in the recent months before starting this course, but they have always been other peoples designs that have been copied through follow along videos on Youtube. I have always wanted to try and make one of my own design but never had the courage to start. 

This project will be for myself, the website will contain my own personal portfolio information which is real and not for a fictional person. Although the website will not immediately be used by myself in real life I may use it in the future as a structure to build upon and improve with the intention of possibly using it in real life circumstances. 

The goal of this website is to display my CV, a small text about myself and a live list of projects and  certifications that can be viewed by any potential employer. The projects, as well as having a live button to view the project will also have a button that will direct to the actual code that makes up the projects, which will be viewed through GitHub. There will also be a contact me page with a form for the potential employer to use to contact me through direct email message or via the use of social links which will be attached onto the footer of each page. 


### 🎯 Scope: 

The website will have the standard header and footer on each page. The header will have some form of simple logo and navigational links to each web page.  
I have decided that I want to keep the project simple, aesthetically pleasing to the eye and try not to overthink the design past my current capabilities.
I know from watching design idea videos on Youtube that the majority of social media suggestions state that simple is best. The employer will only be interested in the basic layout and structure of your design (a responsive and working website) and will more likely be targeting your projects, certifications and code examples.
The website will be fully responsive to the best of my ability and will have all fully working Links/Buttons.


### 🎯 Structure: 

The website structure will be kept simple and easy to navigate (for ease of use).

The main page will be kept simple with a small but non overpowering image of myself and below it a simple description of myself.
Below the about me section I will have an image of my real CV pdf that I created a few months ago and below that will be a working button to open and download that CV. 
 
The projects page will have a simple layout of bordered box around each project that will include a screenshot and title, also there will be two buttons within each project box that will link to both a live preview and the actual code displayed on GitHub. The certifications will also be displayed in a similar manner to the projects but without the navigational buttons. Each of the projects/certifications will be displayed side by side for the width of the page with small margin to separate each one.

The Contact page will also be kept very simple and will have a basic easy to use form which will include sections for first name, surname, email, phone number and finally a message section. There will be a submit button below the form. Haven’t fully decided if this will be a fully working form linked to a back-end yet as this would require the use of outside tutorials and help.  
 


### 🎯 Skeleton: 

This website will be written using GitPod as per our course guidance so far. As suggested in our project ideas and overview, I have decided not to use GitHub pages to display my finished project. Instead I will be using Netlify which I have become very familiar with over the past few months whilst teaching myself to code. Netlify is easy to use and has a ton of great features including connecting to any GitHub repositary, Back-end email service, easy to drag and drop files/folders and free hosting.  

I will be using an easy to use wireframe design tool called Balsamiq to design my website and will be linking images of these designs below.


### 🎯 Surface: 

As for the finished look of the project I am not fully decided on which fonts to use yet or which colors. I’m gonna use a long known procedure of try and test before I decide which I’m going to use. I do however know that I do not want to use any bright and bold colors, I want to stay within the borders of my already decided simple design, and keep the layout, colors and styles simple yet aesthetically pleasing to the eye. 
So far I’m thinking along the lines of light blues, greens and greys, with simple and bold text fonts.


### 🎯 Wireframe of proposed website.


As I have never done a wireframe frame before it took a lot of research to figure out a simple tool to use for creating my wireframe. I decided to use Balsamiq as this look easy and simple to use compared to others I had found. Once I had created the wireframe for each page of my website I then had to figure out how I could show them on this ReadMe file, I decided to use my PC’s own snipping tool to copy sections of my wireframe  and save those sections as individual images. 

Below are those images. I have not incorporated any Tablet views into my wireframe due to the view that any tablet views would only be such small changes that those changes would not made any kind of real change in comparison to the desktop views. Instead I will write a small caption or text stating what those changes would be for the tablet view.


### 🎯 For the main page or index.html page:

#### Desktop View

![Index Page Desktop View](assets/img/index-desktop.PNG)

#### Tablet View

The changes between tablet and desktop view would in my opinion be very small, the only real changes would be the size of the side margins on the outside edge of the main content sections.
Everything else would remain the same.

#### Mobile View

![Index Mobile View](assets/img/index-mobile.PNG)


### 🎯 For the Projects page:

#### Desktop View

![Project Desktop View](assets/img/project-desktop.PNG)

#### Tablet View

![Project Tablet Text](assets/img/project-tablet.PNG)

#### Mobile View

![Project Mobile View](assets/img/project-mobile.PNG)


### 🎯 For the Contact page:

#### Desktop View

![Contact Desktop View](assets/img/contact-desktop.PNG)

#### Tablet View

![Contact Tablet View](assets/img/contact-tablet.PNG)

#### Mobile View

![Contact Mobile View](assets/img/contact-mobile.PNG)


## Adding the Content

### Steps in Order that I took from start to finish in order to complete my project website:

#### Index Page:

Will be using Bootstrap CSS for the Index page, Contact page and header/footer on all pages.

1. Created my basic index.html, project.html and contact.html files.
2. Started to layout the basic structure of my index.html page including header, footer, main content section, title and other meta tags including Bootstrap.
3. Created my main content structure for my index.html page with <div>’s.
4. Using the basic layout structure for the index.html, I then copied this and pasted onto both the project.html and contact.html in order to give all pages the same basic structure.
5. Then I practised add, commit and push to push content made so far onto Github, this is where I encountered my first issue, this was because I had taken a small break and GitPod had timed out. When I refreshed GidPod, the git push command was not working. Took a while to figure out what I had to do, but I did so many things I’m not sure which of these fixed the issue. My best guess is that I re-typed the command ‘git init’ into the terminal and needed to do this each time the session times out. This seemed to work for future time outs.
6. Started to create my header/navbar layout and this went well.
7. Added my links to the navbar page links and then encountered my second error. The links failed to work, took me about 10mins to realised I had put the <a> tags within the <i> tags instead of vice versa, this immediately fixed the issue.
8. Added FontAwesome meta tags and then added some icons to my navbar menu.
9. Added my name as a logo of header, using a span on surname with intention of making my surname a different color to first name.
10. Then I spent some time researching and adding Bootstrap CSS to my header, this took a while due to having to do a lot of research into bootstrap commands, as well as getting the positioning correct which took a few tries. The research was from https://getbootstrap.com/docs .
11. Spent some time adding color onto my header, decided to use the standard bootrap default colors for now.
12. Created the footer, added the social media icons (from FontAwesome)and links.
13. Added Bootstrap CSS to footer.
14. Updated the project and contact page with the header and footer that I created on the index.html page, plus meta tags that I had added.
15. Tested each page and social media links to make sure they were all working, realised I had forgotten to add ‘target=”blank” on the footer links so went and added those.
16. Started to add my About Me content, this was made up of a real image of me that I own and also the text about me was copied and pasted from my own real CV with a small amount of additional text added.
17. Added Bootstrap CSS to my image as it showed up huge. Then decided to add CSS to put a border around the image to make it stand out a little bit.
18. Added Bootstrap CSS to my text.
19. Added my CV image to CV section. Added Bootstrap CSS as yet again the image showed up huge, this was a little harder to get right until I realised I had forgotten to add sizing to the container.
The CV is my real image of my CV.pdf.
20. Added a download CV button. Added Bootstrap CSS to button. Added a working link to the button that enables you to download my Real CV.pdf.
21. Tested my main index.html page and checked that I was happy with the way it all looked.
22. Made some minor padding adjustments to the overall look of the index.html page.


#### Project Page:

Will be using standard CSS with separate stylesheet for the main content of this page only, header and footer will incorporate same Bootstrap CSS as other pages.

1. Checked to make sure all html was up to date with what had been written on index page, mainly with regards to header and footer.
2. Added CSS file to project for the main content section of this page, as well as adding stylesheet in head section.
3. Tested menu and links for this page and content page as well.
4. Added the basic layout and structure for my main content on this page.
5. Added some real images of screenshots or real projects and certificates from my actual portfolio website.
6. Added the individual project images onto the html main section with titles and buttons.
7. Added working links to the buttons which was copied from my real CV Portfolio.
8. Added CSS but this took a while as I had some trouble with positioning of the project elements, had to look on www.w3schools.com for some positioning research.
9. Copied the project section into the certificate section of my html page but removed the button/links.
10. Edited the certificate images and titles until it was all changed from projects to certificates and correct.
11. Tested the page layout and all buttons and links worked correctly.
12. Small amount of CSS for adjustment.


#### Contact Page:

1. Used www.w3schools.com to look up bootstrap forms and found one that I ended up copying the basic code structure and bootstrap from.
2. Edited code to my own liking for the form.
3. Changed only a small amount of Bootstrap CSS. The bootstrap CSS already added was fully responsive so didn’t need to edit/add much. 

