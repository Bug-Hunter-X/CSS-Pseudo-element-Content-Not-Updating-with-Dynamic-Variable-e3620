# CSS Pseudo-element Content Not Updating with Dynamic Variable

This repository demonstrates a bug where the content of a CSS pseudo-element (::before or ::after) does not update when the variable used in the `content` property is dynamically updated via JavaScript.  This can lead to unexpected behavior in web applications where dynamic content updates are expected.

The `bug.css` file shows the problematic code, and `bugSolution.css` demonstrates the solution.

## Bug Report

The issue occurs when combining CSS variables, pseudo-elements, and JavaScript.  The pseudo-element's `content` property, referencing a CSS variable updated dynamically, fails to reflect those changes.