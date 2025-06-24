# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./design/desktop-preview.jpg)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Responsive design

### What I learned

This project helped me improve my skills in creating responsive layouts using Flexbox. I learned how to effectively use CSS custom properties (variables) to maintain a consistent color scheme throughout the project.

One of the interesting techniques I implemented was the image color overlay effect using mix-blend-mode:

```css
.image-container {
  position: relative;
  background-color: var(--soft-violet);
}

.image-container img {
  width: 100%;
  display: block;
  mix-blend-mode: multiply;
  opacity: 0.8;
}
```

I also practiced creating a responsive layout that changes from column to row layout based on screen size:

```css
@media (min-width: 768px) {
  .card {
    flex-direction: row;
  }

  .content {
    padding: 70px;
    text-align: left;
    flex: 1;
  }
}
```

### Continued development

In future projects, I want to focus more on:

- Implementing CSS Grid for more complex layouts
- Improving accessibility features
- Adding subtle animations to enhance user experience
- Exploring more advanced CSS techniques

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - This helped me understand various CSS properties and how to use them effectively.
- [CSS-Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is an amazing article which helped me understand Flexbox layout.

## Author

- Frontend Mentor - [@Ayokanmi-Adejola](https://www.frontendmentor.io/profile/Ayokanmi-Adejola)
