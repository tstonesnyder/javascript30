# Day 3: Update CSS Variables with JavaScript

CSS variables can now be updated with JavaScript (not talking about Sass or LESS), meaning that when you update a variable in CSS everywhere on the page that the var is referenced will update itself.  With Sass you define vars at COMPILE time and they can't be changed after that. 

You declare CSS vars on an element or on root (which is the highest level, similar to declaring it on the html element).  You do this inside your CSS definitions (ex: ```:root {--base: #ffc600; ...}```) or inside a style attribute in HTML (ex: ```<h2 style="--base:#BADA55;">...</h2>```).