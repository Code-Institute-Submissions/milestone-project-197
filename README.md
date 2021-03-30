# Personal Portfolio Website

This website is a personal portfolio website to highlight my own skills, experience with programming to target potential employers, collaborators and partners. My Formal CV will be available for download from the site. 

Included in this overview will be insights into my own personal journey as a developer. Sections on Work Experience, Project Experience and semi-formal descriptive text with complimenting images will be the primary content across this small site. 

There will be three pages; 
- home.html
- projects.html
- contact.hmtl

# Wireframes;
### Home (v1)
![Homev1 Wireframe](images/readme_imgs/wireframe-homev1.png)

I decided it would be helpful to have a section below my work experience, highlighting any academic and professional achievements that I have attained.

### Home (v2)
![Homev2 Wireframe](images/readme_imgs/wireframe-homev2.png)

### Projects
![Projects Wireframe](images/readme_imgs/wireframe-projects.png)

### Contact
![Contact Wireframe](images/readme_imgs/wireframe-contact.png)

## UX 
For UX Design, I'm going with a mimic of VsCode's [Dark Theme](https://code.visualstudio.com/docs/getstarted/themes). 
I also used these value references in my testing; https://docs.microsoft.com/en-us/visualstudio/extensibility/ux-guidelines/color-value-reference-for-visual-studio?view=vs-2019

My decision here comes from the last few years this has been my primary editor, and I've come to really like the color-scheme it uses.
I feel this scheme combined with a resumé/portfolio style website would be complimentary. 

- Main Background; 
`background-color: rgb(64, 64, 64);`

- Headings;
`color: #017fc6;`
- Text/paragraphs background;
`background-color: rgba(112, 112, 112, 0.2);`

- Regular Text
White

## Features
- Responsive Navigation menu
- Show Text Over An Image On Click (Js) for Work Experience section of home page
- Button menu to control content shown by Language for Projects page
- Form Input section for Contact Page
- External Linking for Social Media and Contact img links (Font-awesome)
- Hover affect (hover.css) for images on Work Experience sections and Projects sections
- Clickable footer links 
- Progress bar/striped 
- [Collapsible content](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_js_collapsible)

### Existing Features
For my employment experience section, an on-click action(Working)
![Before](images/readme_imgs/on-click-before.png)
![After](images/readme_imgs/on-click-after.png)

### Features Left to Implement
- Employment Experience - On Hover 
The functionality I wanted for this section was an on-hover icon to indicate the element can be clicked(Not Working), and an on-click action(Working). I had some trouble getting the hover the work - and opted to have the content over the functionality present. Using a paragraph block above the images, I can highlight to the end user that the images can be clicked. 
![exp](images/readme_imgs/on-hover.png)

- Project Implementation
By the end of this course, I would like to embed as much of my previous projects as possible into this website, rather than just touching on them with text and screenshots. 

- I would like to fix the spacing and resolution of some of the inserted images

## Technologies Used
- [HTML](https://www.w3schools.com/html/)
    - The project uses **HTML**.
- [CSS](https://www.w3schools.com/)
    - The project uses **CSS**.
- [Javascript](https://www.javascript.com/)
    - The project uses **Javascript**.
- [Bootstrap](https://getbootstrap.com/)
    - The project uses **Bootstap** to simplify the content structure and provide pre-built functionalities such as navigational templates and grid-classes.

## Testing
### Navigation
- Centering of navigation

### onClickTextOverImg
- I needed to use an external source (CodePen) to test this functionality and get it right; 
https://codepen.io/evane123/pen/vYgKmMM

Implementing it directly into the website proved very difficult. I found myself getting a bit confused with linking the class name between the script tag, html and css. 
Once I got testing it in codepen and with help from a udemy course (Creditted) I was able to get the desired functionality.

### CSS Validation Error;
![CSS Validation Error](images/readme_imgs/validationErr.png)

### Color scheme + hex values; 
[Hexcol](https://hexcol.com/)

### Placement of text inside work-experience logo's 
As per the image below, the text inside of the logo divs doesn't really look as nice as I would have initially intended. 
![text](images/readme_imgs/languages.png)
### Alignment of about me section
I wasn't able to get my profile image and about me text to automatically align side by side when the screen size exceeded 992px 
![Alignment](images/readme_imgs/aboutme-alignment.png)

### Image/text centering/responsiveness
Struggled a little bit with the testing of responsiveness with bootstrap. Unsure if it's due to CSS, or the bootstrap versions I was installing - however it was a bit tough getting going with the content on the page 

## Deployment
- Github pages
I've opted to use [Github Pages](https://evane123.github.io/home) 

The reason for this decision is due to ease of use. With my code already on Github, using Pages will save essential time avoiding the set up of multiple services and server space. 

In the future, I would like to host my website(s) myself. This would be experience, and to offer a more professional feel to the site. 

https://evane123.github.io/

## Credits
- [Aaron Sinnott](https://ie.linkedin.com/in/aaronsinnott)
As my mentor for this project, Aaron was detrimental in reinforcing my key understandings of what is required, and more importantly how to properly approach and manage a project from an academic standpoint. 

Through the last year I have been spending time going through some udemy courses that helped forming of idea's and speccing out what is possible. I used this to my advantage in the Work Experience Section, implementing a small script to handle showing of text that is hidden behind an image when you click on the image. 

### Content

As this is a personal portfolio website, the vast majority of the content is written personally by myself. An outline of the key pieces of information can be found here; 

home.html
- About Me Section
- Work Experience Section
    - Learn4Fun information
    - Teamwork information
    - Voxpro information
    - McDonalds information
    - Eddie Rockets information
- Achievements section 

projects.html
- My experience section (overall statement)
- Html/CSS
- Javascript
- Vue.js
- GoLang
- JAVA

In this Projects section, my intention initially was to try and embed working examples of these projects. After spending some time, I realized that my local environment is not suitable for this. 
In the future, I intend to clean up my environment so that each project can be hosted individually on Github, and referenced when needed. Below is a graphic of my current environmentlanguage breakdown;
![MyStuff Repo](images/readme_imgs/mystuff.png)

![Languages](images/readme_imgs/languages.png)

### Media
### images folder
- Company Logo's; Corresponding company websites. 
- readme_imgs; Created by me
- Project screenshots; Created by me


### readme_imgs folder
- Github Private Repo screenshots acquired while logged into my github.com account. 

### Acknowledgements
- My inspiration for this project came from wanting to have an online presence where I can start, and build on. 