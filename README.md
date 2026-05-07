# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### Screenshot

![My HTML code](<Screenshot (468).png>)[](./screenshot.jpg)
![Windows Developer's view](<Screenshot (467).png>)

### Links

- Solution URL: [Add solution URL here]
- Live Site URL: [Add live site URL here]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This project provided an excellent opportunity to solidify foundational HTML and CSS skills, particularly focusing on layout mechanics. One of the primary challenges in this component is perfectly centering a card on the screen while maintaining responsiveness across different device sizes. 

Using Flexbox made centering the main container straightforward:

```css
body {
    font-family: 'Outfit', sans-serif;
    display: flex; 
    flex-direction: column; 
    align-items: center;
    justify-content: center;
    height: 100vh;
    width: 80%;
    padding: 1rem;
    margin: 0 auto;
    background-color: var(--slate-300);
}
```

I also focused on writing clean, semantic HTML and managing spacing efficiently using CSS custom properties to keep the styling organized.

### Continued development

As I continue building my full-stack software development skills, I plan to take on more complex layout challenges to deepen my understanding of CSS Grid and responsive design principles. Establishing a strong command of the front-end structure is a primary goal as I prepare to tackle heavier JavaScript frameworks and backend integrations in upcoming intensive study tracks. 

### Useful resources

- [MDN Web Docs: Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) - An indispensable guide for understanding how to properly align and distribute space among items in a container.
- [freeCodeCamp Curriculum](https://www.freecodecamp.org/) - The foundational HTML and CSS lessons were highly relevant to structuring this document correctly.

### AI Collaboration

How I used them:

Debugging: I used AI to understand why I wasn't getting my intended layout result. Specifically, it helped me identify why my body element had unexpected extra space—I had removed justify-content: center, which caused the layout to revert to its default flex-start behavior. I also used AI in writing my Readme file;).

Refactoring: I also used the AI to help reorganize my CSS code to ensure it properly followed a mobile-first workflow.

What worked well: The AI was incredibly helpful for explaining the "why" behind default CSS Flexbox behaviors, turning a frustrating layout bug into a solid learning moment.

## Author

- Name - Obioma Tobechukwu Joel
- Frontend Mentor - [@inspayaa](https://www.frontendmentor.io/profile/inspayaa)
- Linkedin - [@Tobechukwu Joel Obioma](https://www.linkedin.com/in/tobechukwu-joel-obioma-3b3b60183/)