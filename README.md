# CSS --- Scrollbar

A **scrollbar** is a user interface element that allows users to scroll the content of an element when the content overflows its visible area.

## Customizing Scrollbar with CSS (Webkit Browsers)

You can style scrollbars using pseudo-elements (only works in WebKit-based browsers like Chrome and Safari):

```css
/* Scrollbar Track */
::-webkit-scrollbar {
  width: 10px;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: #888;
  border-radius: 5px;
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: #555;
}
