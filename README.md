Designer
========

Designer is a platform for designing web components. Designer is unique in that the final output is not a single webpage or component. Designer aims to be a modular design pattern.

This works for both web apps, and websites. 

A website would have a 'layout' module, which handles the location of the navigation, columns, and site content. It then might have many other modules for blog posts, comment threads, the navigation bar, or the log in screen. Each of these elements may reference other elements inside of them, giving the designer a preview of what the Blog module looks like in different segments of the site.

A web app designer might use the tool to design different web components for the app. A chat box might be composed of three or four different modules. These could be designed in expanded and collapsed modes, for module and desktop devices.

The goal of Designer is to be able to design these components without any abstraction between HTML, CSS, and the final output. Designer aims to be platform agnostic. This means that mobile first, RWD, or other paradigms are supported; but not the main focus of the application.


Many of the components of Designer aim to be designed with Designer itself. As much as possible, this tool must be robust enough to be used in the workplace. It should be the unification between design and implementation, between concept and actual production code.


Designer should output HTML and CSS without regards to platform. This means that SCSS, LESS, SMACSS, BEM, Ember, Angular, etc. should be supported out of the box. Exporting is handled by standardized modules supported by the community.

Keyboard shortcuts and other productivity tools are aimed to be completely configurable by users. Similar to Sublime Text 2, ultimately an API is the goal for Designer.


Initial Prototype
-----------------

To provide a proof of concept, Designer v0.1 should support desktop authoring of a percentage based layout. Being able to design components using both images and solid shapes is a primary component. Isolating the display of content from the actual interface is an integral component. Working out the file system, and how content is saved, is an integral goal to this. Usability testing will determine further steps to refine the design process.



