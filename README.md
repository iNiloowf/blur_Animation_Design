# blur_Animation_Design
Readme Note:

This code selects DOM elements and adds event listeners to create various functionalities on a web page. The following features are included:

Modal window: The script adds event listeners to the modal window to open and close it. The function 'openModal' removes the 'hidden' class from the modal and overlay elements, while 'closeModal' adds the 'hidden' class to these elements. The script also listens for the 'Escape' key press to close the modal window.

Button Scrolling: The script listens for clicks on the navigation links and scrolls to the corresponding section on the page using smooth scrolling.

Tabbed Component: The script listens for clicks on the tabs and shows the corresponding content container while hiding the others.

Menu Fade Animation: The script adds hover event listeners to the navigation links and fades the other links and logo when the mouse hovers over a particular link.

Sticky Navigation: The script uses the Intersection Observer API to make the navigation bar stick to the top of the page when it scrolls past it.

Reveal Section: The script uses the Intersection Observer API to reveal hidden sections of the page when they come into view.

Lazy Loading Images: The script uses the Intersection Observer API to load images only when they come into view, thereby reducing the page load time.

Note that some parts of the code have been commented out, such as the sticky navigation using the window scroll event listener.
