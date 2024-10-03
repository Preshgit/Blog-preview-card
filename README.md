# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges helps me improve my coding skills by building realistic projects!

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)
- [Final Words](#final-words)

## Overview

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![alt text](image.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

During this project, I deepened my understanding of using **Flexbox** for layout structuring. Flexbox allowed me to easily center elements within the webpage by leveraging properties like justify-content and align-items. This made aligning content more efficient compared to older techniques like using margins or positioning. With Flexbox, I could quickly align my elements horizontally and vertically, creating a more responsive and visually balanced design.

Additionally, I gained experience working with **IDs and Class selectors** in CSS. I learned how to target specific elements using their unique ID attributes, like _#title_ and _#paragraph_, to apply distinct styles for text formatting and spacing. This was useful in the case where I needed to apply styles to one particular element, while class selectors were effective for reusable styles across multiple elements, even though i didnt use class selectors in this particular project, but i am happy that i now understand these.

These concepts helped streamline my approach to both layout and styling, making the overall design process more intuitive and structured.

I also learned to write **Markdown syntax** and understood the difference between **WYSIWYG** (What You See Is What You Get) and Markdown’s more manual, code-based approach to formatting. This project marks my first experience creating a **README** file, which has been both educational and rewarding!

```html
<div>
  <h1 id="title">Improve your front-end skills by building projects</h1>
  <p id="paragraph">
    Scan the QR code to visit Frontend Mentor and take your coding skills to the
    next level
  </p>
</div>
```

```css
body {
  width: 100vw;
  height: 100vh;
  background-color: #d5e1ef;
  display: flex;
  justify-content: center;
  align-items: center;
}

#title {
  font-family: outfit;
  font-size: 22px;
  color: #1f314f;
  margin-top: 24px;
}

#paragraph {
  font-family: outfit;
  font-size: 15px;
  color: #68778d;
  margin-top: 16px;
  margin-bottom: 24px;
}
```

### Continued development

Code will be reviewed to make sure it it absolutely responsive across multiple devices.

### Useful resources

- [Flexbox](https://www.youtube.com/watch?v=K74l26pE4YA) - This short youtube video helped me to understand how to use Flexbox.
- [markdownguide](https://www.markdownguide.org/) - This article was incredibly helpful in teaching me how to write Markdown syntax. I quickly applied what I learned to create this README file. And yes, this is the very first README file I've ever written! :)

## Author

- Frontend Mentor - [@Preshgit](https://www.frontendmentor.io/profile/Preshgit)
- X - [@presh_ot](https://x.com/presh_OT)

## Acknowledgments

A huge thank you to my front-end senior colleague - [@kinghorey](https://github.com/KingHorey), whose guidance and support were instrumental in helping me navigate the intricacies of Flexbox and CSS. Thank You Ore!

## Final Words

Hi Reader 👋, I hope you enjoyed the read!
