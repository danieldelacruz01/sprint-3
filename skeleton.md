What happens to the layout when you resize the screen to less than 550 px. How do you think that works? 

The layout converts into a mobile-friendly layout with the content rerranged from multiple columns down to one. It does this using a CSS media query which changes the layout according to the pixel width of the window/screen. In this instance, a mobile first responsive design has been created using min-width. In other words, the layout defaults to mobile layout, but if the pixel width is greater than 550px, it converts to desktop layout.
