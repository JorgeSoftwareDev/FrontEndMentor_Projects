# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The Challenge

The challenge is to build out this recipe page and get it looking as close to the design as possible.

### Screenshot

![](/Project1_RecipePage/assets/images/screenshot.png)

### Links

- Codepen URL: [Jorge's CodePen](https://codepen.io/Jorge-Alvarado-the-selector/details/MWRoeJd)

## My process

In my website development project for a "Frontend Mentor" challenge, I focused on crafting a webpage using HTML and CSS based on a supplied design mockup. This entailed creating all necessary HTML tags and CSS classes, as well as integrating Google Fonts and Font Awesome icons to enhance aesthetics and user interface. The design aimed for responsiveness across devices, with layouts tailored for mobile (375px) and desktop (1440px) widths, ensuring accessibility in line with WCAG standards.

The typography of the site, emphasizing readability and style, featured selected fonts from Google Fonts — 'Young Serif' and 'Outfit' — used at specific weights to maintain design consistency. This project was a balanced effort to combine responsive design principles with a visually appealing and accessible online experience, focusing on user-friendly navigation and aesthetic coherence without delving into the specific color scheme details.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Google Fonts](https://fonts.google.com/)
- [Font Awesome](https://fontawesome.com/)

### What I learned

This CSS code snippet introduced me to an advanced styling technique for lists that I hadn't explored in depth before. Specifically, the ::marker pseudo-element targets the list item markers, allowing for customization beyond the default appearance. In this instance, the code changes the color of the list markers to a specific shade (hsl(332, 51%, 32%)) and sets the font weight to 600, making the markers noticeably bold. This method of directly styling the markers was a new concept for me, offering a refined level of control over the visual presentation of lists without affecting the text of the list items themselves. It underscored the importance and versatility of pseudo-elements in CSS, opening up possibilities for more intricate designs and presentations in web development.

```css
#instructions li::marker {
  color: hsl(332, 51%, 32%);
  font-weight: 600;
}
```

### Useful resources

- [W3 Schools](https://www.w3schools.com/) - This helped me when I got stuck on a CSS property. Especially the CSS marker pseudo selector.

## Author

- LinkedIn - [Jorge Alvarado's LinkedIn](https://www.linkedin.com/in/jorgesoftwardev/)
