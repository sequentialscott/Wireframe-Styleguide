#Wireframe.css

Wireframe.css is a CSS file you can use to make a page look like a hand sketched wireframe.  
It's useful for exploring designs, usability testing, and early demos.  You can also use 
a set of Angular JavaScript directives if your prototype uses Angular.

##Installation
Download and unzip the repository.  Link your web page to wireframe.css.  Also, make sure that the icon file (wf-sprite.png) is in the same directory 
as the CSS.  (Or update the CSS to point to it.)  To use the Angular directives, make sure your HTML includes the wf-directives.js file and your 
Angular module injects it.  For example:

```
var app = angular.module('myApp', ['wfDirectives']);
```

##Using Wireframe.css
After unzipping the repository, view the page `styleguide.html` to see a style guide that both uses and documents wireframe.css. 
It is a simple Angular application, and you can choose options for most of the styles and see code that you can copy and paste.