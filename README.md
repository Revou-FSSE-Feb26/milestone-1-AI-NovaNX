# Personal Portfolio Website

A simple **personal portfolio website** using **native HTML and CSS**
This project was created to showcase personal information, skills, and projects in a clean layout without relying on any frameworks or external libraries.

The goal of this project is to demonstrate a solid understanding of **fundamental web development concepts**, including semantic HTML structure, and clean CSS styling.

---

## Preview

![Portfolio](public/preview.png)

---

## Tech Stack

This project intentionally uses **pure web fundamentals**

| Technology        | Description                                 |
| ----------------- | ------------------------------------------- |
| HTML5             | Structure of the web pages                  |
| CSS3              | Styling, layout, and responsiveness         |
| Flexbox / Grid    | Layout management                           |
| Responsive design | Improving usability across all screen sizes |

Explanation:

- **index.html** → Main entry page of the website
- **style.css** → Main stylesheet for all styling rules
- **public/** → Folder containing images and icons used in the website
- **README.md** → Documentation of the project

---

## Getting Started

To run this project locally, follow these steps:

### 1. Clone the repository

```bash
git clone https://github.com/Revou-FSSE-Feb26/milestone-1-AI-NovaNX.git
```

---

### 2. Navigate to the project folder

```bash
cd milestone-1-AI-NovaNX
```

---

### 3. Open the project

Open `index.html` directly in your browser

For a better development experience you can also run the project using VS Code Live Server

---

## Learning Goals

This project focuses on strengthening the following skills:

- Writing clean **semantic HTML**
- Creating layouts using **CSS Flexbox and Grid**
- To apply **responsive design principles** in developing a website that delivers a consistent and intuitive user experience across various screen sizes and devices.
- Organizing project structure properly
- Understanding the **foundation of front-end development**

---

## Deployment

This project can be deployed using GitHub Pages

Example deployment URL :

```bash
https://revou-fsse-feb26.github.io/milestone-1-AI-NovaNX/
```

---

## Features 
_(Click the arrow " ▶ "  in front of each feature number or click the feature title to view a more detailed explanation.)_

<details>
	<summary><strong>1. Fixed Header with glass blur effect</strong></summary>

The portfolio website includes a fixed header that remains consistently positioned at the top of the page, ensuring that navigation is always visible and easily accessible regardless of the user’s scroll position. To enhance both usability and visual refinement, the header applies a subtle glass blur effect when page content scrolls beneath it, creating a polished frosted-glass appearance while preserving clarity and readability. This implementation supports a more intuitive user experience by keeping key navigation elements available at all times and reinforcing a clean, modern interface throughout the site.

In addition, all navigation buttons are fully functional and provide seamless access to their respective page sections or destination links, allowing users to move through the website easily and efficiently. This enhances the overall <mark>**user experience (UX)**</mark> by making navigation more intuitive, accessible, and efficient throughout the website.

[![Watch the demo video](public/preview.png)](https://www.webmobilefirst.com/en/screencasts/euyo4kje92r2zb/)

<mark>Click the image above to watch the demo video (video will open in other tab - don't forget to klik play " ▶️ " button)</mark>

</details>

<details>
    <summary><strong>2. Radial gradation in Hero background</strong></summary>

The hero section is enhanced with a radial gradient background that adds depth and visual emphasis to the opening area of the page. This design element helps draw the user’s attention to the main introductory content while creating a more dynamic and modern visual impression. By using a smooth gradient transition, the section feels more engaging and refined, supporting the overall aesthetic quality of the website without overwhelming the content.

</details>

<details>
    <summary><strong>3. Hero Title Typography Combination</strong></summary>

The hero title uses a combination of **Inter** and **Charm** to create a balanced visual identity between clarity and artistic expression. **Inter** provides a clean, modern, and highly readable foundation, while **Charm** adds a more decorative and expressive touch to the heading. This combination helps the title feel more distinctive and memorable, with **Charm** reinforcing the <mark>artistic</mark> atmosphere that aligns with the overall theme of the website.

</details>

<details>
    <summary><strong>4. Using Flex Box</strong></summary>

The layout implementation makes extensive use of **Flexbox** to create a clean, flexible, and well-aligned structure across different sections of the website. By using Flexbox, elements can be positioned more efficiently, with better control over spacing, alignment, and content distribution. This approach helps maintain a responsive and organized interface, ensuring that the layout remains visually balanced and adaptable across various screen sizes.
<br>
<p align="center">
    <img src="public/flex-desktop.png" alt="Flex when in desktop size" width="500"><br  >
    <em>About section in Desktop size</em>
</p>
<br>
<p align= "center">
    <img src="public/flex-tablet.png" alt="Flex-warp when in tablet size" width="500"><br>
    <em>About section in Tablet size</em>
</p><br>

</details>

<details>
    <summary><strong>5. Button with link and icon image</strong></summary>

The website uses buttons that combine text labels with icon images to make interactions clearer and more visually engaging. This helps users recognize the purpose of each action more quickly while keeping the interface consistent with the overall visual style of the portfolio.

We add one CSS declaration to the envelope icon so that its position can align inline with the text that follows it. The CSS line is as follows:

```bash
.btn-primary img {
  vertical-align: middle;
}
```

</details>

<details>
    <summary><strong>6. Marquee-style logo animation</strong></summary>

The website features a marquee-style logo animation that presents trusted brand identities in a continuous horizontal flow, enhancing visual engagement while reinforcing credibility and professional appeal.

This feature is designed not only to make the section more visually engaging, but also to communicate credibility, professionalism, and the value of strong design execution. By presenting these brand identities in a dynamic and polished way, the website highlights a sense of trust and reinforces the impression that my design and development results are dependable, refined, and worthy of professional recognition.

[![Watch the demo video](public/marquee.png)](https://www.webmobilefirst.com/en/screencasts/-nqrleyxz9_nyf/)
<mark>Want to see the animation? Click the image above to watch the demo video (video will open in other tab - don't forget to klik play " ▶️ " button)</mark>
</details>

<details>
    <summary><strong>7. CSS GRID layouting</strong></summary>

The Portfolio section is built using **CSS Grid** with **`auto-fit`** to create a clean, flexible, and visually balanced layout for presenting project work. This approach allows the project cards to automatically adjust based on the available screen width, making the section more responsive without requiring rigid column settings. By combining CSS Grid with `auto-fit`, the layout maintains consistent spacing, strong alignment, and an organized visual structure across different devices. This implementation demonstrates the use of modern front-end techniques to achieve both responsiveness and presentation quality, helping the portfolio appear polished, professional, and easy for recruiters to explore.

<br>
<p align="center">
    <img src="public/grid-desktop.png" alt="Grid when in desktop size" width="500"><br  >
    <em>Grid 3x2 in Desktop size</em>
</p>
<br>
<p align= "center">
    <img src="public/grid-tablet.png" alt="Grid when in tablet size" width="500"><br>
    <em>Grid 2x3 in Tablet size</em>
</p><br>

</details>

<details>
    <summary><strong>8. Responsive design</strong></summary>

The website is designed with a responsive layout strategy to ensure a consistent and user-friendly experience across multiple device sizes. For **mobile devices** with a breakpoint of **max-width: 765px**, the layout is optimized for smaller screens by improving content flow, readability, and touch accessibility. In this mobile view, the navigation menu can be accessed through a **burger menu button** available in the header, allowing users to open and use the navigation conveniently without overcrowding the screen. For **tablet to small desktop screens**, ranging from **768px up to less than 1280px**, the interface adjusts to provide better spacing, alignment, and content balance while making fuller use of the available screen width. On **desktop screens** with a breakpoint of **1280px and above**, the layout expands to deliver a more spacious and structured presentation, allowing the content to appear more polished and visually organized. This responsive implementation demonstrates careful attention to usability, adaptability, and modern front-end development practices across a wide range of devices.

**a. Breakpoin mobile phone (breakpoin max-width 765px)**
<br>
[![Watch the demo video](public/mobile.png)](https://www.webmobilefirst.com/en/screencasts/ffgu-uvpmk4h16/)
<br>

**b. Breakpoin 768px up to less than 1280px**
[![Watch the demo video](public/tablet.png)](https://www.webmobilefirst.com/en/screencasts/krojlkclzjy8jp/)
<br>

**c. Breakpoin 1280px and above**
[![Watch the demo video](public/desktop.png)](https://www.webmobilefirst.com/en/screencasts/qwi0allvs452fr/)
<br>

<mark>Click the image above to watch the demo video (video will open in other tab - don't forget to klik play " ▶️ " button)</mark>

</details>

---

## Future Improvements

Possible improvements for future development:

- Implement dark mode

- Add JavaScript for interactivity

- Add animation

- Clean code for maintainability

---

## Author

### Antonius Eko Indriarto

A front-end developer learner who is passionate about building modern web interfaces and continuously improving web development skills.
