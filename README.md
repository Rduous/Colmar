# Colmar Academy

The capstone project for *CodeCademy Ready*.

## Description
>You are tasked with designing and creating the landing page for a new school. You will help them by making informed design decisions about color and typography using the skills you learned last week. You will then implement your design[...] For this project you will implement the site specified by the wireframes and make all remaining design decisions to complete the site.

## Design notes
### Color palette
I let the images of this site drive the color palette. Four "types" of colors seem to predominate: web-y blues, yellow ochres, warm greys, and warm browns.  I focused on the first three families.  I went with a dark, high-impact navy blue for header, footer, and important features like buttons, with a poppier blue for hover actions.  I used a mustard/ochre for select features like logo and main header. I kept the backgrounds simple with alternating grey and light tones.

I intended the colors to be impactful (but not distracting) and just the slightest bit informal.

### Fonts
Given the technical, urban brand of Colmar Academy, I chose to use a sans seriff font.  I wanted to use "Web safe" fonts to maximize the chances viewers will see the correct font.  Arial was my ultimate choice for non-header text; it's clean and readable.  I used Arial Black for the headers to increase their impact.

I considered using Courier for the headers -- it added visual interest to the page and would have been a cheeky nod to the tech content of most of the courses -- but ultimately found it decreased the readability of headers with lighter colors.

### Changes
- **Omitted 185px space at top of mobile layout.** I made a deliberate choice to exclude this page element because I felt it detracted from the flow of the site.
- **Used ratios instead of pixels in some cases.** CSS seems to behave better with the `flex` property than with widths.
