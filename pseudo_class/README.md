This is day 3 of consistently learning towards my fullstack development journey today my focus is on pseudo class in css. Pseudo-class is a keyword added to a selector to specify a special state of the selected element. my focus has been on link the pseudo class element of a link are:
1️⃣ a:link — Unvisited Link
This pseudo-class targets links that have not yet been clicked.
a:link {
  color: blue;
}
📌 Used to define the default color of new links.
2️⃣ a:visited — Visited Link
This applies after the user has clicked the link at least once.
a:visited {
  color: purple;
}
📌 Helps users identify links they’ve already visited.
3️⃣ a:hover — Hover State
This activates when the user moves their mouse over the link.

a:hover {
  color: green;
}
📌 Improves usability by giving visual feedback.
4️⃣ a:focus — Keyboard Focus
This applies when a link is selected using the keyboard (e.g., Tab key).
a:focus {
  outline: 2px solid orange;
}
📌 Important for accessibility, especially for keyboard users.
5️⃣ a:active — Active (Clicked) State
This activates while the link is being clicked.
a:active {
  color: red;
}
📌 Gives instant visual feedback when clicking a link.
✅ Removing the Default Underline
Browsers underline links by default. To remove it, use:
a {
  text-decoration: none;
}
This ensures links do not have an underline in any state.