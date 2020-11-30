# seanrox_portfolio
My Portfolio site 

Trouble Shooting
couldn't expand colapse toggle menu burger in nav - found solution = https://www.youtube.com/watch?v=-0TmFPOEFPw
Fixed-navbar hides portion of container, found solution how to lower it-https://stackoverflow.com/questions/14735274/bootstrap-css-hides-portion-of-container-below-navbar-navbar-fixed-top
style navbar - https://www.youtube.com/watch?v=3Yc7TVZo3h0


tutorials:

https://css-tricks.com/snippets/css/text-rotation/




<h1 align="center">Sean Rox Portfolio Site- First milestone project</h1>
<h1 align="center"><img src="/assets/images/readme/mywebsite.jpg"/></h1>

 <a href="https://seanyrox.github.io/seanrox_portfolio/"></a>  Live Website

  <a href="https://github.com/seanyrox/seanrox_portfolio">GitHub Repository
 
 ## About
This is my Portfolio website that gives insight of who I am from a professional point of view. 
The goal of the website is to generate potential work or employment in the field of programming/design.
It is a single page vertically scrolling page.
It showcases my skills in different screen resolutions as its responsive. 
 


## Table of Contents

[User Experience (UX)](#UX)

[Features](#features)

[Technologies Used](#technologies)

[Testing](#testing)

[Deployment](#deployment)

[Known Bugs](#bugs)

[Credits](#credits)



<a name="UX"></a>
## User Experience (UX)

### User Stories
- #### As a potential employer looking to hire someone fulltime/partime.
    1. I want to learn about who the candidate is without being overloaded.
    1. I want to get to the core information quick without having to click on to many links.
    1. As an employer I want to follow the candidate on his different social medias channels to get a deeper insight. 
    1. I want to be able to download his CV so that I can print it out. 
    1. As an Employer I want to contact the candidate to see if he is free for an interview. 
- #### As a potential collaborator who needs someone with programming skills or design consultation. 
    1. I want to get a sense of feel about the candidates personality to see if compatible to work with. 
    1. I want to look at his work and see if his work/style is applicable to my needs.
- #### As a visitor who is looking to get ideas or inspiration from this site. 
    1. I want to be able to follow the candidates social media channels to see updated work. 
    1. I want to access the site on any device to get inspired.
   



### Design choices 


- #### Fontface

    - I choose Roboto for the headings as it is a timeless font that's legible in various sizes. 

      

    - I choose Source Sans Pro as my paragraph/content font as its a little bit softer and less austere and rigid. 
      Gives more of an personal touch to the reader.


- #### Colour Palette
    -  The website was muted interms of colours intentionaly to emphasize the work/brand section. 
       I wanted to create less visual distraction/cluster and focus on the work I've done.
       three main colours/tones were used during this process:
       #242120- used for text colour, hover for links and footer.
       #fff used for some text. 
       #c54040 was used for the progressbars and social media links when hovered over.


- #### mockups: 
     - I used balsamic to mock up the below wireframes. the wireframes have changed since original sketch and 
     with the input of my mentor. 

    <img src="/assets/images/readme/finalwireframes.png"/>
     

   






 <a name="features"></a>
## Features

### Features

#### Shared features across site:


-   **Google Fonts** - I used Roboto and Source Sans Pro to compliment the minimal website. Below is the code added to the top of my css file

            @import url('https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
            @import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:ital,wght@0,300;0,400;0,600;1,400&display=swap'); 


-    **Navigation header** - allows user to easily navigate across the same page.
    - The Navigation bar is fixed to the top using bootstraps .fixed-top for ease of access.  
    - The brand logo link is positioned on the left  and brings vistors back to the top of the page.
    - THe remainder of the links are on the right hand side of the navigation bar, once clicked they smoothly vertically scroll to respective sections. 
    - Once you hover over the brand logo link an underline appears, when you hover over the 3 links (about, brand and email(shown as a fontawesome email icon) to the right which are displayed in a dark grey colour, they turn white with a black background.
    - For mobile devices the right handside links collapse to a hamburger button(that turns into a dropdown menu when selected) that I customised from Bootstrap. 
-   **Responsiveness**
    - the single page resized to various screen resolutions using bootstrap responsive columns and media queries. 
-    **Accessibility**
    - All Pages have an alt tag description in case the image doesn't display and is picked up byscreen readers.
    - different elements have labels with the class .sr-only
    - heading elements are in a sequentially decending order. 
    - All links are styled the same way with and inverted effect whenever hovered over. 
-   **Footer**
    - The footer is located at the bottom of the page and it contains 3 sections starting from the left- "About", middle- "Download printable cv" and right- "social media icons".
    - The left- "About" is a reminder what services I provide to increase the lead conversion to sale. 
    - The middle section allows the prospect employer to download a printable format cv. 
    - The Right hand side section provides socialmedia (Instagram, Facebook and Linkedin) links of me inform of icons. 
    - Fontawesome icons were used for the social media links as they are universally know and give an extra impact visually.  

### Specific to Pages
-    **Home(top section**
    - The top section has a 90vh display in a white background which contain two focal points; a brief description of me(left hand side) and on the right an circular image of me pops in 2 seconds after the page loads, 1 second later a speechbubble fades in above my picture with text saying "hello". These animations were generated by <a href="https://www.animista.net">animista an css animation generator.
-   **About**
    - This section "about" me has a light-grey background tone to cleary differentiate it with previous section. 
    - The About section contains 4 categories split into 3 horizontal colums occupying one row called "Me", "Skills", "Services" and the 4th category "Employment" which is directly beneath that occupy full column/width of screen.
    - The "Me" section gives the user and indepth description of who I am as a person to promote relationship building. 
    - The "Skills" section uses a bootstrap progressbar which I customised through css. These progressbars indicate my skill level in various computer languages and softwares. 
    - The "Services" section showcase what I offer interms of services for the prospective employer/client. 
    - The "Employment" section shows a customised horizontal bootstrap timeline showing my employment history, this timeline is responsive and goes vertical with smaller screens. 
-   **Brands**
    - Brands is split into two sections, first one shows a selection of iconography/brands and second section shows off work I've done for clients with a brief desciption. 
    - This iconography section has no background colour but it does float over a fixed covered background image of white bricks. This gives a sense of hip urban work enviroment. 
    - the second section below which has a white background displays work in a checkered fashion. its split into 4 rows with two column in each row on a large screen. on the first row you have writing to the left describing the job and the column on the right displays it. The following row beneath starts with shwoing the work and then describing the job, in reversed order. 
-   **Contact Form**
    - Is for anyone who wants to contact me in regards to employment, collaborator or any queries related to programming or design.
    - the Lead needs to fill in their full name, email and post a comment. 

### Features left to implement
 
- buttons that people can share or comment my work. 
- A blog/vlog section where I can share my life experices. 
- A "Thank you for submitting" text once a visitor submits the contact form. 
- Testimonial section 

<a name="technologies"></a>
## Technologies Used


- [Balsamiq wireframes](https://balsamiq.com/): Used to create wireframes

### Languages:

- [HTML5](https://en.wikipedia.org/wiki/HTML5): Markup language used to create structure of site
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets): Cascading styles used to style HTML. 
- [JavaScript](https://www.javascript.com/): Used in this instance for interactivity.  

### Development enviroment:
- [GitPod](https://www.gitpod.io/) - I used GitPod to write code, it has predictive text which speeds up the process of coding. Through the terminal in gitpod I commit/pushed my work to Github repository.  

### Hosting service:
- [Github](https://github.com/) - GitHub is used as a remote storage of files pushed from gitpod. I used Github to deploy my live website. 


### Version control system:
- [Git](https://git-scm.com/) - To track changes in my website and for version control. 




### Frameworks, Libraries and Programs Used

- [Bootstrap v4.5.3](https://getbootstrap.com/) - I placed the bootstrap cdn before my own stylesheet inorder to override with custom css. this framework was used for responsive gridsystem and I used components such as ( navigationbar, progress bars, timeline, typography and  form )
- [jquery](https://jquery.com/) - Used in some of the clickable elements such as collapsable 'hamburger' nav bar and collapse element.
- [popper.js](https://popper.js.org/) - Used in some of the clickable elements such as collapsable 'hamburger' navbar and collapse element.
- [Smooth Scroller](https://github.com/cferdinandi/smooth-scroll) - Adds a smooth scroll effect to links and buttons. 
- [Font Awesome](https://fontawesome.com/) - Font Awesome is a library with icons that I used to visually strengthen the headers in website. 
- [Google Fonts](https://fonts.google.com/) - Google Fonts was used to import 'Roboto' and 'Source Sans Pro' fonts in the main.css stylesheet.
- [Photoshop](https://www.adobe.com/ie/products/photoshop.html?gclid=CjwKCAjwwYP2BRBGEiwAkoBpAuYIg7JHUAFtnRQB28LDaU5gvFxhLX_56PYV2xbl6bTKvYSjK5yoLhoCkjQQAvD_BwE&sdid=88X75SKS&mv=search&ef_id=CjwKCAjwwYP2BRBGEiwAkoBpAuYIg7JHUAFtnRQB28LDaU5gvFxhLX_56PYV2xbl6bTKvYSjK5yoLhoCkjQQAvD_BwE:G:s&s_kwcid=AL!3085!3!340674288378!e!!g!!photoshop) - I used photoshop to resize, desaturat and save images as jpeg or png's.



<a name="#testing"></a>
## Testing




