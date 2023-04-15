# Responsive Navbar Menu
This code implements a fully responsive navigation menu that adapts to different screen sizes. It is written in JavaScript and uses event listeners to make the menu interactive.

- The addClick function is responsible for showing and hiding submenus when clicking on menu items. It uses the clientHeight property to get the submenu height and scrollHeight to set its height when displaying it. Additionally, it changes the menu item's class to reflect its current state.

- The deleteStyleHeight function is used to remove the height style on submenus when the screen is resized and the full menu becomes visible. This ensures that the menu displays correctly on large screens and prevents display issues.

- The resize event listener detects changes in screen size and updates the menu accordingly. If the screen is large enough, deleteStyleHeight is called to reset the submenu styles. If the screen is small enough, addClick is called to make the menu interactive.

- Finally, the click event listener is used to show and hide the menu on small screens. When the hamburger menu button is clicked, a CSS class is added or removed to show or hide the menu.
