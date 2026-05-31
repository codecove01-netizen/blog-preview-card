<p align="center">
  <img
    src="https://www.frontendmentor.io/images/logo-desktop.svg"
    alt="Frontend Mentor"
    width="220"
  />
</p>
<h1 align="center">
  🌟Blog Preview Card Solution
</h1>

<p align="center">A responsive solution to the Blog Preview Card challenge on Frontend Mentor.</p>

<p align="center">
  <a href="YOUR_LIVE_SITE_URL">🌐 Live Demo</a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="YOUR_FRONTEND_MENTOR_SOLUTION_URL">💡 Frontend Mentor Solution</a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS">🎯 Challenge</a>
</p>

<h1 align="left">
  📸 Layout Overview
</h1>

<blockquote>

<h3>💻 Desktop View</h3>

<img src="./screenshot-desktop.png" alt="Desktop Preview" width="850">

</blockquote>

<br>

<blockquote>

<h3>📱 Mobile View</h3>

<img src="./screenshot-mobile.png" alt="Mobile Preview" width="300">

</blockquote>
---

## 🎯 The Challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover states for interactive elements
- The font sizes in this project are slightly smaller in the mobile layout. Find a way to reduce font size for smaller screens without using media queries.

---

## 🚀 Built With

- Semantic HTML5 Markup
- CSS Custom Properties
- Flexbox
- Mobile-First Workflow
- Responsive Design
- CSS `clamp()`

## 💡 What I Learned

This project gave me valuable practice in translating a design specification into a responsive and visually accurate webpage.

### Responsive Typography with `clamp()`

One concept I explored in depth was responsive typography using the `clamp()` function. While implementing fluid font sizes, I learned that the preferred value must reach the maximum threshold before the browser applies the maximum size.

This helped me better understand how viewport units influence responsive text scaling.

```css
.card-title {
  font-size: clamp(1.25rem, 1.5vw, 2rem);
}
```

### Key Takeaways

- Semantic HTML structure
- Flexbox alignment and spacing
- CSS custom properties
- Hover states and interactive elements
- Creating reusable and maintainable CSS

> This project also reinforced the importance of attention to detail when matching spacing, typography, and visual hierarchy to a design specification.

---

## 🚧 Biggest Challenge

One of the more interesting challenges was matching the spacing, typography, and overall visual hierarchy of the original design while keeping the layout responsive across different screen sizes.

Fine-tuning margins, shadows, font sizes, and responsive behavior helped me appreciate the importance of attention to detail in frontend development.

---

## 🤖 AI Collaboration

During this project, I used **ChatGPT** as a learning and debugging assistant to:

- Clarify CSS concepts
- Understand responsive typography
- Troubleshoot layout issues
- Review code quality and best practices

> The final implementation, styling decisions, testing, and code integration were completed and verified by me.

---

## 👩‍💻 Author

**Arati D'sa**

- GitHub - [@YOUR_USERNAME](https://github.com/YOUR_USERNAME)
- Frontend Mentor - [@YOUR_USERNAME](https://www.frontendmentor.io/profile/YOUR_USERNAME)

---

## 🙏 Acknowledgments

Thanks to **Frontend Mentor** for providing practical challenges that help developers strengthen their frontend skills through hands-on learning.
