# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

![The Preview](./tools/fem-landing-page%20desktop.png) 

### Screenshot

Desktop:
![Desktop View](./tools/fem-landing-page%20desktop.png) 

Tablet
![Tablet Views](./tools/fem-landing-page%20tablet%201.png) 
![Tablet Views](./tools/fem-landing-page%20tablet%202.png) 

Mobile:  

![Tablet Views](./tools/fem-landing-page%20mobile%201.png) 


## My process
1. Design System: I start by using the Figma design system to copy colors, button styles, font styles, and any other important design choices into the root of my project.

2. Boilerplate Code: Next, I create boilerplate code for the base styles, setting a solid foundation for the project.

3. HTML Structure: I then code the HTML from top to bottom. 

4. Section by Section: I then split the website into sections and tackle each section. Ensuring it's optimized for mobile, tablet, and desktop before moving on to the next section.

>In total this took me about **13** hours of work, between research, coding and testing. Definitely not idea, but I am going to continue to work at some challenges to see if I can't optimize my workflow as I get better. 

**Future Plans**: In the future, I want to make some tweaks to my process by coding each device layoout one after the other while still maintaining a mobile-first approach.  

### Built with

- Semantic HTML5 markup
- SCSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Supporting Figma Prototypes and Design Systems

### What I learned

-**Figma to Code**: I got better at making sure my code matches the figma designs more closely - paying extra attention to the little details.  

-**Better Workflow**: I tweaked how I set up my projects, making everything flow more smoothly and setting up success from the start. This meant organizing my files better, planning out key features in advance, and using version control (like Git) more effectively.  

-**Mobile-first Workflow**: I learned a lot about mobile-first design, focusing on getting things right for small screens before worrying about larger ones.   

-**Cool CSS Stuff**: I discovered some neat CSS properties like the clamp() function that made my typography more flexible.  

-**Responsive Images**: I also learned how to use the <picture> tag to serve different images based on device width, optimizing the user experience on various screen sizes.  


To see how you can add code snippets, see below:

```html
 <h1> Some Nifty HTML I learned </h1>
         <picture>
             <!-- Load different pictures for different device break points -->
               <!-- Desktop-->
               <source media="(min-width: 75em )" srcset="/assets/image-hero-desktop@2x.webp" width="2092" height="1876" >
               <!-- Tablet-->
             <source media="(min-width: 50.625em )" srcset="/assets/image-hero-tablet@2x.webp" width="695" height="723" >
            <img src="/assets/image-hero-mobile@2x.webp" alt="woman with coffee and laptop with labels reading Members 29k, Course hours 1,451" width="870" height="818">
          </picture>
```
 > The <picture> tag helps load different images based on the device's screen size, making the site faster and more responsive. Here’s how it works:
 >
>Desktop: If the screen is 75em (1200px) or wider, the desktop image (image-hero-desktop@2x.webp) is loaded.  
>
>Tablet: For screens that are at least 50.625em (810px) but less than 75em, the tablet image (image-hero-tablet@2x.webp) shows up instead.  
>
>Mobile (Fallback): If neither condition is met, the mobile image (image-hero-mobile@2x.webp) is loaded by default. This makes sure smaller devices don’t load huge files they don’t need.


### Continued development

I’m excited to keep improving my skills in the following areas:

**CSS Grid and Layout Mastery**: I want to dive deeper into CSS Grid to create more complex and flexible layouts that respond beautifully to different screen sizes.

**Positioning**: I’m looking to master positioning techniques to have more control over how elements are placed and layered on the page.

**Mobile and Responsive Development**: I plan to explore more about responsive design to ensure all my projects look great on any device.

**Accessibility**: I’m committed to learning more about web accessibility to make sure my projects are usable for everyone, regardless of their abilities.

### Useful resources

- [Fluid Typography](https://royalfig.github.io/fluid-typography-calculator/) - This tool helped me create responsive text sizes that adjust smoothly across different screen sizes. I really liked this pattern and will definitely use it in my future projects
- [Can I Use? ](https://caniuse.com/) - This site is fantastic for checking browser compatibility of different CSS features. It finally helped me understand how to ensure my designs work across various browsers.
- [Complete Guide to Grid ](https://css-tricks.com/snippets/css/complete-guide-grid/) - This article is an excellent resource for mastering CSS Grid. It clarified a lot of concepts for me, and I’ll definitely refer back to it as I work on grid layouts in the future.


## Author
Hi, I’m **Toni King**! I’m a designer and aspiring full-stack programmer with a passion for creating engaging and user-friendly web applications. I love diving into new technologies and honing my skills. 

When I’m not coding, you can find me watching sports, reading a book or finding a new favorite food spot. I’m always eager to learn and grow in this field, and I’m excited to see where my journey takes me!

![Personal Logo](./tools/Toni%20M%20King.jpg) 


## Acknowledgments

I want to give a big shoutout to @CodercoderBuilds on YouTube. Her videos taught me some invaluable tricks and problem-solving techniques. I’d code sections of my website, then watch her videos to see how she approached similar challenges. I learned a ton of new things that really helped improve my skills! 
