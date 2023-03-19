# Frontend Mentor - Testimonials grid section solution


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)



## Overview
-	Webpage with sections of testimonials 

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size


### Links

- Live Site URL: https://testimonialsgridsectionfm.netlify.app/

## My process
-	Remove the internal stylesheet to an external one
-	Completde html with the appropriate attributes and classes for separation when I get to the CSS page
-	I put everything into one main container and separated each testimonial into an individual div section and added the images for each profile picture.
-	Afterwards I added my google font according to the style guide provided 
-	In the CSS I added the default elements I wanted throughout the page (background color, padding, margin and font)
-	I started workout from the outside of the design, so the container style first and then I worked on setting the grid_header spacing, alignment, and position. I added the text elements for the font size, margin and font weight. After that, I used my second class for each grid header to set the individual background colors and text colors. This way it eliminated the need for excess code  by duplicating each testimonial code over and over with slight changes. The media query took some effort, but I was able to follow a grid tutorial to set up the column and row locations for each card in the container when the webpage is seen in desktop mode.  



### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

-	I learned how to use the CSS grid item in a grid container to style the items so that they will span multiple columns and/or rows. Helpful resource here: https://www.w3schools.com/css/css_grid_item.asp . This was also another chance to work with attributes that I assigned two classes which I am still practicing. This is what I feel really helped me not overcomplicate my code by repeating things for each card in my grid. Instead I had one style assigned (grid_header) and then the second class was used to change the color and backgrounds.  

Code I am proud of:
```css
/**** My individual cards ****/

.grid_header.card1 {
    background-color:hsl(263, 55%, 52%);
    color: hsl(0, 0%, 100%);
}
```


### Continued development

-	I would like to continue focusing on grids until I feel more comfortable with them, especially when changing screen sizes.   

### Useful resources
- https://www.youtube.com/watch?v=RCBdm4YTVpQ - I followed this tutorial after my first attempt, because he explained his steps really well and helped me feel confident in some of the steps I took with my code. (The media query grid arrangement was were I needed the most help)


