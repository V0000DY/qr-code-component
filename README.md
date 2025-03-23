# Frontend Mentor - QR Code Component Solution

This is my solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help improve coding skills by building realistic projects.

---

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

---

## Overview

### Screenshot

![Design preview for the QR code component coding challenge](./preview.jpg)

This screenshot showcases the final result of my project. I used Google Chrom to take the screenshot and optimized the image for better display.

### Links

- Solution: [View solution here](https://your-solution-url.com)
- Live site: [Visit live site here](https://your-live-site-url.com)

---

## My process

### Built with

- **Semantic HTML5 markup**
- **CSS custom properties**
- **Flexbox** for layout management
- **Mobile-first workflow**

---

### What I learned

While working on this project, I improved my skills in the following areas:

1. **Semantic HTML structure**:
   I learned the importance of using semantic tags like `<main>`, `<section>`, and `<footer>` to improve website structure and accessibility.

2. **CSS custom properties**:
   I learned how to use CSS variables effectively to simplify color and style management.

```text
:root {
  --primary-color: hsl(218, 44%, 22%);
  --secondary-color: hsl(220, 15%, 55%);
  --background-color: hsl(212, 45%, 89%);
  --container-color: hsl(0, 0%, 100%);
  --shadow-color: rgba(0, 0, 0, 0.1);
  --link-color: hsl(228, 45%, 44%);
  --font-family: "Outfit", sans-serif;
  --font-size: 15px;
  --header-font-size: 22px;
  --paragraph-font-size: var(--font-size);
}

body {
  background-color: var(--background-color);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 98vh;
  font-family: var(--font-family);
  font-size: var(--font-size);
}
```

3. **Flexbox**:
   Flexbox became my go-to tool for positioning elements on the page. I learned how to create responsive layouts with minimal code.

```text
.centered {
  flex: 1;
  display: flex;
  justify-content: center;
  align-items: center;
}
```

4. **Mobile-first workflow**:
   For the first time, I applied a mobile-first approach, starting with a layout for mobile devices and then adapting it for larger screens.

---

### Continued development

In future projects, I plan to:

Deepen my knowledge of CSS Grid to create more complex layouts.

Explore web accessibility (a11y) to make my projects more user-friendly for everyone.

Further develop my responsive design skills to ensure my websites look great on all devices.

---

### Useful resources

Here are some resources that helped me during this project:

MDN Web Docs — A great source of information on HTML and CSS.

Flexbox Froggy — An interactive game that helped me understand Flexbox better.

Frontend Mentor Slack Community — A community where I found helpful tips and advice.

Author
Vitaly Rubtsov

Frontend Mentor: @V0000DY

---

### Acknowledgments

I’m grateful to the Frontend Mentor community for providing engaging challenges and inspiration. Special thanks to MDN Web Docs for their detailed explanations of HTML and CSS.
