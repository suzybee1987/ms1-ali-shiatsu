readme

# Alison Melville's Shiatsu Shin Tai

![](assets/images/readme-imgs/amiresponsive.png)

## About

**Alison Melville's Shiatsu** needs a B2C website that showcases a massage business specialising in Shin Tai near Manchester. I designed the site to educate the user about the benefits of Shiatsu Shin Tai and allow them to contact her to book a consultation. 
I created the site to look professional and in keeping with the theme of similar Shiatsu websites and using the colour schemes to bring a relaxing impression as would be expected with a massage site.
The goal of the website will be to interact with existing and potential clients and be a source of information to educate them, build confidence and encourage them to contact the business owner.
The site must contain all information required to complete these goals and site visitors will most likely be comparing with other similar services in the local area so must stand out and show everything the user would want to see.

Link to [live site](https://suzybee1987.github.io/ms1-ali-shiatsu/index.html)

## **Contents**

- [**UX (User Experience)**](#ux-user-experience)
  - [**User Stories**](#user-stories)
  - [**Project Goals**](#project-goals)
  - [**User Goals**](#user-goals)
  - [**Site Owner Goals**](#site-owner-goals)
- [**Design Choices**](#design-choices)
  - [**Fonts**](#fonts)
  - [**Colours**](#colours)
  - [**Imagery**](#imagery)
  - [**Wireframes**](#wireframes)
- [**Technologies**](#technologies)
  - [**Languages**](#languages)
  - [**Libraries**](#libraries)
  - [**Tools**](#tools)
- [**Features**](#features)
  - [**Features Implemented**](#features-implemented)
  - [**Future Features**](#future-features)
  - [**Responsive Design**](#responsive-design)
- [**Version Control**](#version-control)
- [**Testing**](#testing)
  - [**Functionality Testing**](#functionality-testing)
  - [**User Story Testing**](#user-story-testing)
  - [**Performance Testing**](#performance-testing)
  - [**Responsive**](#responsive)
  - [**W3C Validator**](#w3c-validator)
- [**Bugs**](#bugs)
- [**Deployment**](#deployment)
  - [**Running Locally**](#running-locally)
- [**Credits**](#credits)
  - [**Code**](#code)
  - [**Content**](#content)
  - [**Images**](#images)
  - [**Inspiration**](#inspiration)
  - [**Acknowledgements**](#acknowledgements)
  

## **UX (User Experience)**


### **User Stories**
- As a user visiting the site for the first time:
  - I want to be able to see social media links so that I can keep up to date through Facebook, Instagram and Twitter.
  - I want to click the navigation links to be taken to the correct section and also back to home for a better user experience.
  - I want the page to be in a predictable layout so that I can navigate it easily.  
  - I want to see a map of the location so that I can determine how close it is to my location and navigate there easily.  

- As a user returning to the site:
  - I want to be able to access the site easily on my chosen device
  - I want to easily be able to navigate to different parts of the site
  - I want to be able to contact the business owner as I wish through social media or contact form

- As a user who has never had a Shiatsu Shin Tai Massage before:
   - I want to use the site to learn more about Shiatsu Shin Tai and how to contact the business owner so that I can ask questions.
   - I want to see a demonstration of what to expect when receiving a Shiatsu Shin Tai massage.
   - I want some information about the price and time required per session
   - I want some information about the business owner's qualifications.
   
   
### **Project Goals**
- The primary goal of this site is to showcase Ali's Shiatsu Shin Tai massage business to attract new clients and provide a means of communication while linking to social media pages. 


### **User Goals**
- The user will be able to find out more about Shiatsu Shin Tai and be able to contact Ali for more information.


### **Site Owner Goals** 
- As a site owner I want the user to learn about Shiatsu Shin Tai massage and the business owner.
- As a site owner I want the user to be able to communicate with the business owner on social media and through contact form.
- As a site owner I want to show the user that the business owner is a registered practitioner of her work.
- As a site owner I want to create a website with a great user experience so that visitors will come again. 

[Back to contents](#contents)

## **Design Choices**


### **Fonts**

I have chosen [Architect's Daughter](https://fonts.google.com/specimen/Architects+Daughter) for the headers as it is easy to read and has sufficient contrast to the main body font. It is a cursive font so has a more easy-going, relaxed look inkeeping with the feel of the site. 
![Example here](assets/images/readme-imgs/architects-daughter.PNG)

and [Montserrat](https://fonts.google.com/specimen/Montserrat) for the rest of the text on the site (eg. paragraphs and lists) as it is easy to read with wider spacing than other fonts.

![Example here](assets/images/readme-imgs/montserrat.PNG)


### **Colours**

As the site purpose is about relaxation and massage the colour scheme used is adapted to suit with what the user would expect of this kind of site. It features complementary blue, green and purple colours that also stand out to make the content easy to read. The colours chosen are:

![Coolors Palette](assets/images/ms1-coolors.png.png)


Format: [Coolors Palette](https://coolors.co/5b76a0-299491-45b0ae-827aa2-f5f9fd)

These colours compliment each other well and are not too striking, in keeping with what the user expects. 

### **Imagery**

Images can be found in [assets](assets/images) and feature Shin Tai massages being performed, a profile of the business owner and continue with the relaxing theme of the site.
Some of the images have been sourced from [Unsplash](https://unsplash.com/) and are free to use if credited and others were provided by the business owner. 
  
### Video

-index.html
  - The [Massage Demonstration Video](https://youtu.be/aLYgPbQXyGw) is performed by Saul Goodman who came up with the Shin Tai blend of massage. 

### **Wireframes**

The wireframes were created using [Balsamiq](https://balsamiq.com/) and can be found in pdf form in [wireframes](assets/wireframes)

- [Home](assets/images/wireframes/index.png)
- [Contact Page](assets/images/wireframes/contact.png)
- [Mobile View - Home](assets/images/wireframes/mobileindex.png)
- [Mobile View - Contact Page](assets/images/wireframes/contact.png)
- [Tablet View - Home](assets/images/wireframes/tablet-index.png)
- [Tablet View - Contact Page](assets/images/wireframes/tablet-contact.png)


[Back to contents](#contents)

## **Technologies**

### **Languages**

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)
  - Used as the main markup language for the website content.
- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)
  - Used to style the individual webpages.
- [jQuery](https://developer.mozilla.org/en-US/docs/Glossary/jQuery) and [Popper.js](https://popper.js.org/)
  - Used with Bootstrap Scrollspy to track location on the page and Bootstrap Collapse for Accordion sections on mobile and tablet view. Also used with the contact form to launch the modal after required fields on form were completed. 

### **Libraries**
​
- [Bootstrap](https://getbootstrap.com/)
  - Used to design a mobile-first responsive website layout along with custom components (navigation bar toggle button, accordion, cards, scrollspy, footer).

  
### **Tools**

- [Git](https://git-scm.com/)
  - Git was used for version control (commit to Git and push to GitHub).
- [GitHub](https://github.com/)
  - Used to store, host and deploy the project files and source code after being pushed from Git. I also used it for the Project Kanban board.
- [Gitpod](https://www.gitpod.io/)
  - An online IDE linked to the GitHub repository used to write my code.
- [Font-Awesome](https://fontawesome.com/icons?d=gallery)
  - Used to make headings stand out.
- [Google fonts](https://fonts.google.com/)
  - Used to compare and choose fonts. 
- [Coolors](https://coolors.co/)
  - Used to research and choose the colour scheme by comparing and contrasting similar colours in the generator.
- [Favicons](https://favicon.io/)
  - Used to generate a favicon for the website title.
- [Lighthouse](https://developers.google.com/web/tools/lighthouse)
  - Used to audit the site for quality and ensure responsiveness.
- [amiresponsive](http://ami.responsivedesign.is/)
  - An online tool to check how responsive the site is on different devices.

[Back to contents](#contents)

## **Features**

### **Features Implemented**

Features relevant to both pages:
- **Header**
    - Contains the navigation links and is fixed to the top of the page for easy use on all devices (this was done using Bootstrap sticky-top class).
    - All links are underlined when hovered over and for the icons this is done using the border-bottom attribute to provide spacing and prevent overlapping the icon.
    - The headings are underlined as the user visits different areas of the page (using Bootstrap scroll-spy) to help the user work out where they are in the page.
    - The home button is on the left of the header and sections of the page listed on the right where a user would expect them to be.
    - Navigation links are underlined when the user hovers over them to give feedback that they have hovered over the right spot.
    - On mobile and tablet view the Navigation links collapse in to a toggle button for easier user experience. Some JavaScript was used here to ensure the menu closes after a link is pressed to avoid the user having to close the menu. 
    - The colour scheme is designed to be easy to read with the contrast and the ratio tested on Google Dev Tools.

- **Hero sections**
    - The image takes up the full width of the browser to leave a high impact lasting impression with the user and this is replicated on both pages to bring a sense of familiarity when browsing.
    - The hero images were obtained when searching for massage related images to instantly give the user the confirmation that this is the site they were searching for.
  
- **Footer** 
    - Designed to sit at the bottom of the page after all of the content 
    - Contains social media links and a link to Shiatsu Society website so that the user can verify the business owners professional status. 

  
#### *index.html*
  
- **About sections**
   - About Shiatsu and About Shin Tai sections contain some information which allows users to understand more about the subject, origin and health benefits.
  - About Me section gives the user some history about how the business owner discovered Shin Tai and confidence in her registered status along with a portrait of her for them to relate to.
   - On mobile and tablet view the About Shin Tai and About Me sections have been condensed using Bootstrap Accordian component to prevent the user from having to scroll through large volumes of text. The information is split in to subheadings to allow the user to target the information they require. 

- **Pricing and Services section**
   - Provides a video showing the massage being performed by the developer of Shin Tai to allow the user to understand what to expect.

- **Testimonials**
    - Bootstrap cards used here to contain the testimonial quotes - featured on browser are three cards but to save space on mobile and tablet this has been reduced to one. 

#### *contact.html*

- **Contact form**
    - For the user to contact the business owner, the fields: Name, Phone and Email and required and show error messages if not filled before clicking submit. Comments (textarea) is not required. 

- **Modal**
    - This component from Bootstrap's library is used to give feedback that the form has been submitted as without it the form would reset on submission. This required some use of JavaScript to show it only after all required fields have been filled. 

- **Buttons** 
   - On the form the buttons are as a user would expect there is a submit and reset button on the form with the Reset button having more muted colours and Submit button the obvious choice for the user to select upon submission. The modal Close button uses the same colour scheme making it easy for the user to understand what is expected after the message is displayed. 

#### *404.html*

 - **Button**
    - On the 404.html page the button redirects the user back to index.html to prevent them having to press the browser back button. 

### **Future Features**
- I would like to implement an appointment booking system and for the user to receive feedback of appointment booked via email and sms.
- I would also like to add an option for the user to add a testimonial to the business online and link to Trust Pilot
- I would like to implement a swipeable carousel for the Testimonials on mobile/tablet view 

### **Responsive Design**

- Bootstrap columns were used to make the site responsive on all devices.

[Back to contents](#contents)

## **Version Control**

**Version control** was managed within **GitHub** and **Gitpod** and regular commits pushed to **GitHub**.

### Gitpod Workspaces
1. Starting from GitHub clone the [Code Institute template](https://github.com/Code-Institute-Org/gitpod-full-template) by clicking Use This Template and copying to my repository under the name ms1-ali-shiatsu. The workspace is then launched by clicking GitPod - this action only needs to be performed once and then workspace reopened from GitPod.
2. Start the Gitpod Workspace which opens an **online IDE editor** window.

### Update GitHub by committing from GitPod
3. After each change made I would save the code, perform *git add .*, *git commit -m "commit message here"* and *git push* to push my changes to the GitHub repository. 
4. Meaningful commit messages were used to allow to roll back any changes made throughout the journey.

After beginning this process I acknowledged that using git branches would be a more efficient way to do this to avoid any bugs in the future. 

[Back to contents](#contents)

## **Testing**

### **Functionality Testing**

Browsers tested: Google Chrome, Mozilla Firefox, Microsoft EDGE and Safari.

The devices used in this testing include Acer Swift 3, iPad Mini 2, Huawei P30 lite v.Android 10, Samsung S8 v.Android 10, Samsung S10 v.Android 10 iPhone X, iPhone 7.

- Navigation bar
  1. When the Spa icon is clicked it takes the user to the homepage (index.html) from all pages
  2. Click each link in turn and you are taken to the desired section of the site
  3. Reduce the screen size to 992px and toggler (hamburger) menu appears
  4. Menu links clicked in turn and successfully navigate to each section
  5. When a link on hamburger menu is clicked the menu automatically closes
  6. Stays fixed to the top of the browser on all devices
  7. Tested on all browsers and mobiles. 

- Scrollspy
  1. Scroll down the page
  2. See the underlined nav links just before each new section is reached.
  3. Tested on all browsers and mobiles. 

- Footer 
  1. Scroll to the bottom of the page
  2. Sticks to the bottom of the page no matter how much content is present - this was tested by deleting all the other content from the body and it stayed on the bottom.
  3. Click the social media links and they open the relevant pages in a new tab. 
  4. Tested on all browsers and mobiles. 
 
- Accordion Menus
  1. Click each heading in turn
  2. Only one card is open at once as designed
  3. As another is opened the last card is closed
  4. This was tested on all browsers for sizes 992px and below. 

- Youtube Video
  1. Scroll to Pricing section
  2. Video does not autoplay
  3. Click play and it plays successfully in the window and can click to open in full screen
  4. Tested on all browsers and mobile. 

- Google Maps iframe
  1. Scroll to Find Me section
  2. Google Maps iframe visible
  3. Zoom function works correctly,
  4. Hover over and full screen option is available
  5. Tested on all browsers and mobile. 

- Contact form 
  1. Open "Contact" page
  2. Try to submit form without required fields and an error message appears.
  3. Try to submit with invalid email address, error message appears.
  4. Try to submit with less than 11 numbers in the phone number field and error appears. 
  5. Try to submit the form with all required fields filled correctly and success message appears. 
  6. Tested on all browsers and mobile

- Modal
  1. Successfully submit form
  2. Modal shows only when all required fields correctly filled
  3. Close button works as required.

### **User Story Testing**

Testing was completed to make sure the user goals were completed

- As a user visiting the site for the first time:
  - [x]I want to be able to see social media links so that I can keep up to date through Facebook, Instagram and Twitter.
    -Social media links open in new tabs
  - [x]I want to click the navigation links to be taken to the correct section and also back to home for a better user experience.
    -Navigation links work correctly to direct to the right part of the site.
  - [x]I want the page to be in a predictable layout so that I can navigate it easily.  
    -The layout is colour coordinated to make it easy to see where each section starts and ends.
  - [x]I want to see a map of the location so that I can determine how close it is to my location and navigate there easily.  
    -Google Map with the local area featured in Find Me section. 

- As a user returning to the site:
  - [x]I want to be able to access the site easily on my chosen device
    -Site is responsive on all devices tested and Google Dev Tools
  - [x]I want to easily be able to navigate to different parts of the site
    -Fixed navigation at top of page and scroll spy allows for easy navigation
  - [x]I want to be able to contact the business owner as I wish through social media or contact form
    -Contact form available and social media links to keep in touch with business owner.

- As a user who has never had a Shiatsu Shin Tai Massage before:
   - [x]I want to use the site to learn more about Shiatsu Shin Tai and how to contact the business owner so that I can ask questions.
    -Information provided about Shiatsu and Shin Tai to help the user learn more and contact form included.
   - [x]I want to see a demonstration of what to expect when receiving a Shiatsu Shin Tai massage.
    -YouTube video included and description of what to expect for users who can't view the video.
   - [x]I want some information about the price and time required per session
    -Pricing information available on request due to individual needs. Time of session provided in pricing section
   - [x]I want some information about the business owner's qualifications.
    -About Me section communicates to the user the qualification held through Shiatsu Society and link to their website where the business owner can be verified. 


### **Performance Testing**
- Testing completed at [WebPageTest](https://www.webpagetest.org/), location London, browser Chrome. The site suggested to improve security and cache which is outside the scope of this course so far. 
  -[index.html](https://www.webpagetest.org/result/210502_AiDc9H_54970e9720a3e3a7effb48b06e5a3eeb/)
    -[Security Score](assets/images/readme-images/webpagetest-index)
  -[contact.html](https://www.webpagetest.org/result/210502_AiDcYW_b5066f465ced9a2a821f8e4138e48c1b/)
    -[Security Score](assets/images/readme-images/webpagetest-contact)
  

### **Responsive**
The site is responsive on all browsers and mobile through bootstrap framework and media queries and was tested using [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/). 
The live site address was given to family and friends as well as the business owner to confirm the links work as expected and is responsive on all devices. 


### **W3C Validator**

W3C tests completed for html and css pages

- Scrollspy
  1. Scroll down the page
  2. See the underlined nav links just before each new section is reached.
  3. Tested on all browsers and mobiles. 

- Footer 
  1. Scroll to the bottom of the page
  2. Sticks to the bottom of the page no matter how much content is present - this was tested by deleting all the other content from the body and it stayed on the bottom.
  3. Click the social media links and they open the relevant pages in a new tab. 
  4. Tested on all browsers and mobiles. 
 
- Accordion Menus
  1. Click each heading in turn
  2. Only one card is open at once as designed
  3. As another is opened the last card is closed
  4. This was tested on all browsers for sizes 992px and below. 

- Youtube Video
  1. Scroll to Pricing section
  2. Video does not autoplay
  3. Click play and it plays successfully in the window and can click to open in full screen
  4. Tested on all browsers and mobile. 

- Google Maps iframe
  1. Scroll to Find Me section
  2. Google Maps iframe visible
  3. Zoom function works correctly,
  4. Hover over and full screen option is available
  5. Tested on all browsers and mobile. 

- Contact form 
  1. Open "Contact" page
  2. Try to submit form without required fields and an error message appears.
  3. Try to submit with invalid email address, error message appears.
  4. Try to submit with less than 11 numbers in the phone number field and error appears. 
  5. Try to submit the form with all required fields filled correctly and success message appears. 
  6. Tested on all browsers and mobile

- Modal
  1. Successfully submit form
  2. Modal shows only when all required fields correctly filled
  3. Close button works as required.

### **User Story Testing**

Testing was completed to make sure the user goals were completed

- As a user visiting the site for the first time:
  - [x]I want to be able to see social media links so that I can keep up to date through Facebook, Instagram and Twitter.
    -Social media links open in new tabs
  - [x]I want to click the navigation links to be taken to the correct section and also back to home for a better user experience.
    -Navigation links work correctly to direct to the right part of the site.
  - [x]I want the page to be in a predictable layout so that I can navigate it easily.  
    -The layout is colour coordinated to make it easy to see where each section starts and ends.
  - [x]I want to see a map of the location so that I can determine how close it is to my location and navigate there easily.  
    -Google Map with the local area featured in Find Me section. 

- As a user returning to the site:
  - [x]I want to be able to access the site easily on my chosen device
    -Site is responsive on all devices tested and Google Dev Tools
  - [x]I want to easily be able to navigate to different parts of the site
    -Fixed navigation at top of page and scroll spy allows for easy navigation
  - [x]I want to be able to contact the business owner as I wish through social media or contact form
    -Contact form available and social media links to keep in touch with business owner.

- As a user who has never had a Shiatsu Shin Tai Massage before:
   - [x]I want to use the site to learn more about Shiatsu Shin Tai and how to contact the business owner so that I can ask questions.
    -Information provided about Shiatsu and Shin Tai to help the user learn more and contact form included.
   - [x]I want to see a demonstration of what to expect when receiving a Shiatsu Shin Tai massage.
    -YouTube video included and description of what to expect for users who can't view the video.
   - [x]I want some information about the price and time required per session
    -Pricing information available on request due to individual needs. Time of session provided in pricing section
   - [x]I want some information about the business owner's qualifications.
    -About Me section communicates to the user the qualification held through Shiatsu Society and link to their website where the business owner can be verified. 

### **Performance Testing**
- Testing completed at [WebPageTest](https://www.webpagetest.org/), location London, browser Chrome. The site suggested to improve security and cache which is outside the scope of this course so far. 
  -[index.html](https://www.webpagetest.org/result/210502_AiDc9H_54970e9720a3e3a7effb48b06e5a3eeb/)
    -[Security Score](assets/images/readme-images/webpagetest-index)
  -[contact.html](https://www.webpagetest.org/result/210502_AiDcYW_b5066f465ced9a2a821f8e4138e48c1b/)
    -[Security Score](assets/images/readme-images/webpagetest-contact)
  
### **Responsive**
The site is responsive on all browsers and mobile through bootstrap framework and media queries and was tested using [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/). 
The live site address was given to family and friends as well as the business owner to confirm the links work as expected and is responsive on all devices. 

### **W3C Validator tests completed for html and css pages**

![index.html](assets/images/readme-imgs/html-validator)
![contact.html](assets/images/readme-imgs/html-validator-contact)
![css](assets/images/readme-imgs/css-validator)

[Back to contents](#contents)

## **Bugs**

- iframe bug
  - During testing the w3c validator flagged the usage of <p> within the iframe which would be displayed if the youtube video would not load. This was learned on the course and there doesn't seem to be an alternative from my research. 

[Back to contents](#contents)

## **Deployment**

The project was developed using [GitPod](https://gitpod.io/) and pushed to [GitHub](https://github.com/) as follows:

To deploy the page to **GitHub Pages** these steps were taken:
1. Log in to **GitHub**.
2. Select **suzybee1987/ms1-ali-shiatsu**.
3. Click Settings and scroll down to **Pages**.
4. Under **Source** select **None** and then **Master Branch**.
5. The site automatically refreshes and the website deployed providing the link: https://suzybee1987.github.io/ms1-ali-shiatsu/index.html

### How to contribute to the site
1. Navigate to [GitHub](https://github.com/) and log in
2. Locate my [repo](https://github.com/suzybee1987/ms1-ali-shiatsu)
3. On the right side of the screen click Fork
4. This creates a copy in your own repository to make changes in [GitPod](https://gitpod.io/)
5. Once finished with changes add, commit and push to your own [GitHub](https://github.com/)
6. Click Pull Requests and select "New Pull Request" button.

### How to run the project locally

To clone this project from GitHub follow the instructions taken from [GitHub Docs](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository):
1. Navigate to the [GitHub Repository](https://github.com/suzybee1987/ms1-ali-shiatsu)
2. Above the files click the green Download Code link.
3. To clone using HTTPS click the clipboard symbol under "Clone with HTTPS". To clone using SSH key click Use SSH then click the clipboard symbol. To clone using GitHub CLI select Use GitHub CLI and click the clipboard symbol. 
4. Open Git Bash
5. Change the working directory to the location you want the cloned directory to be.
6. Type 'git clone' and paste the url copied from step 3. 
7. Press 'enter' to create your clone.

[Back to contents](#contents)

## **Credits**

### **Code**
- CodeInstitute Full Stack Developer Course
- LinkedIn Learning course by [James Williamson](https://www.linkedin.com/learning/html-essential-training-2017/)
- LinkedIn Learning course by [Christina Truong](https://www.linkedin.com/learning/css-essential-training-3/)

### **Content**
- The information provided regarding Shiatsu was provided by the business owner, Alison Melville. 
- README.md help came from: 
  -[Code Institute](https://github.com/Code-Institute-Solutions/SampleREADME)
  -CI Student [Simon Vardy](https://github.com/simonjvardy/Aviation-Consultancy/blob/master/README.md)
  -My Mentor - Maranatha Ilesanme sent me [Liga Baikova's README.md](https://github.com/LigaMoon/Boredom-guide/blob/master/README.md) to use as a rough template.
  
### **Layout**

-[Background layout](https://css-tricks.com/perfect-full-page-background-image/) from css-tricks.com
-[Layout fix](https://css-tricks.com/fixed-headers-on-page-links-and-overlapping-content-oh-my/) when contact form overlapped footer
-[Lazy Loading](https://developer.mozilla.org/en-US/docs/Web/Performance/Lazy_loading) added to iframes after reading Lighthouse report which showed these slow down the site loading time. Solution found [here](https://css-tricks.com/the-complete-guide-to-lazy-loading-images/)
-[Modal on submission](https://github.com/natalie-kate/haunted) issue was coming up because the button type="button" was required to make the modal work but this button type doesn't produce error if required fields not completed. Checked on slack and found a solution from post on #peer-code-review where @Nat_kate managed to fix this issue.

### **Images**
Images were run through [tinypng.com](https://tinypng.com/) to reduce the size after running Lighthouse report. This helps load the site faster and provides better user experience.
- #index.html
  - The [Hero image](assets/images/conscious-design-J16LdoIsRJM-unsplash.jpg) on index.html was sourced from [Unsplash](https://unsplash.com/). Photo by <a href="https://unsplash.com/@conscious_design?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Conscious Design</a> on <a href="https://unsplash.com/s/photos/massage-therapy?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  - The images of [Alison Performing Shin Tai Massage](assets/images/Ali-massage2.jpg) and [Alison's profile photo](assets/images/ali-photo2.jpg) were taken by her husband, Iain Melville.

- #contact.html
The hero image on contact.html was sourced from [Unsplash](https://unsplash.com/). Photo by <a href="https://unsplash.com/@lgence?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Laurent Gence</a> on <a href="https://unsplash.com/@dfu05229/likes?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
### **Inspiration**

- Scrollspy navigation inspiration from Peer Code Review project posted by [Claire Lemonair](https://github.com/lemocla/MS1-Catsitting)

### **Acknowledgements**

- I received inspiration for this project from X

[Back to contents](#contents)
