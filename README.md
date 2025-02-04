# Uncommon HTML Bug: Unexpected Initial Visibility

This repository demonstrates a subtle bug related to the initial display style of a div element in HTML.  The intention is for the div to be hidden initially, but due to a missing or incorrect style declaration, it appears visible.

## Bug Description
The `bug.html` file contains a div with an id of "myDiv".  A Javascript function is used to toggle its visibility. However, upon initial page load, the div is unexpectedly visible. This is an uncommon issue that might be missed due to assumptions about default display styles.

## Solution
The `bugSolution.html` file corrects this by explicitly setting the initial `display` style of the div to `none` in CSS.  This ensures the div is initially hidden as intended.

## How to Reproduce
1. Clone the repository.
2. Open `bug.html` in a web browser. Observe that the text inside the div is immediately visible.
3. Open `bugSolution.html` in a web browser. Observe that the text is initially hidden, and only appears after clicking the button.
