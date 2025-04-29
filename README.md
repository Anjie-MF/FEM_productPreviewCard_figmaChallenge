# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### Screenshot

![](./images/Screenshot%202025-04-28%208.55.20%20PM.png)

### Links

- Solution URL: [GitHub](https://github.com/Anjie-MF/FEM_productPreviewCard_figmaChallenge)
- Live Site URL: [GitHub Pages]( https://anjie-mf.github.io/FEM_productPreviewCard_figmaChallenge/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Figma

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

```html
      <div class="img-container">
        <picture>
          <source media="(min-width: 768px)" srcset="images/image-product-desktop.jpg">
          <source media="(min-width: 300px)" srcset="images/image-product-desktop.jpg">
          <img src="images/image-product-mobile.jpg" alt="crystal bottle surrounded by lush leaves">
        </picture>
      </div>

      This is actually from my own old code, this responsive image solution ueses the <picture> element, ensuring an optimized user experience across different screen sizes
```
```css
    .add-to-cart {
        background-color: #1A4032;
        border-radius: 8px;
        padding: 32px 16px;
        margin: 32px;
        color: white;
        font-family: "Montserrat", sans-serif;
        font-weight: 900;
        font-size: 1rem;
        line-height: 110%;
        width: 80%;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 8px;
    }

    .add-to-cart:hover {
        background-color: #3D8168;
        font-size: 1rem;
    }

    .cart-icon {
        width: 18px;
        height: 18px;
    }
    About two years, I wasn’t sure how to incorporate a hover effect and an icon, so I left them out. This time, I decided to experiment and learn through trial and error, ultimately figuring out how to enhance the button's interactivity with both the hover effect and the cart icon.!
```

### Continued development

Improve my confidence with spacing and alignment (especially without relying heavily on guesswork).

Deepen my understanding of when to use Flexbox vs Grid — and how to combine them thoughtfully for different screen sizes.

Build stronger mobile-first habits, while ensuring desktop layouts feel equally polished.

### Useful resources

- [Responsive Test Tool](https://responsivetesttool.com/) - It is my go-to to check if it is responsive to all screen sizes. 

## Author

- Linkedin - [Anjelica May](www.linkedin.com/in/anjiemay23)
- Frontend Mentor - [Anjie-MF](https://www.frontendmentor.io/profile/Anjie-MF)
