# Hey Apoorva! Let's Build a Responsive Header with a Full-Screen Modal Navigation 🚀

Hi Apoorva,  
Welcome to your new assignment! 😊 In this task, you'll create a responsive website header that adapts to different screen sizes. On larger screens, you'll have a traditional navigation bar, but on smaller screens, a hamburger icon will appear. When you click the hamburger, a full-screen modal with your navigation links will open up, and you'll include a close button in the top right corner to dismiss it.

## What You'll Learn

- **Responsive Design:** Use media queries to adjust your layout for different screen sizes. 📱💻
- **Modal Windows:** Create and style a full-screen modal overlay. 🖥️
- **JavaScript Interactivity:** Implement click events to open and close the modal. ✨
- **Semantic HTML & CSS:** Write well-structured code that's both accessible and maintainable. ✅

## Assignment Requirements

1. **HTML Structure:**
   - Build a `<header>` that includes a logo and navigation links.
   - Add a hamburger icon that will be visible on small screens.
   - Create a modal element that covers the entire screen and contains:
     - Navigation links.
     - A close button positioned at the top right corner.

2. **CSS Styling:**
   - Use media queries (for example, `@media (max-width: 768px)`) to hide the standard navigation on smaller screens and display the hamburger icon.
   - Style the modal so that it overlays the entire viewport. Use properties like `position: fixed`, `top: 0`, `left: 0`, `width: 100%`, and `height: 100%`.
   - Position the close button at the top right of the modal with styles such as:

```css
.close {
  position: absolute;
  top: 1rem;
  right: 1rem;
  font-size: 2rem;
  cursor: pointer;
}
```

3. **JavaScript Functionality:**
   - Add an event listener to the hamburger icon that displays the modal when clicked.
   - Add an event listener to the close button to hide the modal when clicked.
   - Optionally, allow users to close the modal by clicking outside the modal content.

## Some Friendly Hints 💡

- **HTML Tips:**  
  Use semantic tags like `<header>` and `<nav>` to make your code clear and accessible.

- **CSS Media Queries:**  
  Here's a simple example to hide the navigation and show the hamburger on smaller screens:

```css
@media (max-width: 768px) {
  .nav { display: none; }
  .hamburger { display: block; }
}
```

- **Modal Styling:**  
  To make your modal cover the whole screen, consider:

```css
.modal {
  display: none;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.9);
  justify-content: center;
  align-items: center;
}
```

- **JavaScript Event Handling:**  
  Use `document.getElementById` and `addEventListener` to control the open/close functionality:

```javascript
hamburger.addEventListener('click', () => {
  modal.style.display = 'flex';
});

closeBtn.addEventListener('click', () => {
  modal.style.display = 'none';
});
```

- **Extra Tip:**  
  Make sure to comment your code. This is a great habit for keeping your work organized and for future reference. 👍

## Submission Guidelines

- Submit all your files (HTML, CSS, and JavaScript) in one ZIP archive or via a Git repository link.
- Include a `README.md` that explains your design choices and any challenges you faced.
- Make sure your code is neat, well-commented, and functional.

---

Enjoy coding this fun project, Apoorva! If you have any questions or need a hand, feel free to reach out. Happy coding! 🎉
