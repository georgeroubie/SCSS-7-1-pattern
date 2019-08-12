# File names
 + Start your file name with an underscore
 + Use hyphens for your file name: `_user-profile.scss` 

# File architecture 

## Abstracts
 + The `abstracts` folder gathers all Sass tools and helpers used across the project
 + Every global variable, function, mixin and placeholder should be put in here

## Vendors
 + The `vendors` folder containing all the CSS files from external libraries and frameworks

## Base
 + The `base` folder holds what we might call the boilerplate code for the project 
 + In there, you might find the reset file, some typographic rules, and probably a stylesheet defining some standard styles for commonly used HTML elements 

## Layout
 + The `layout` folder contains everything that takes part in laying out the application
 + This folder could have stylesheets for the main parts of the application
 
## Components
 + The `components` folder is more focused on widgets
 + It contains all kind of specific modules like a slider, a loader, a widget, and basically anything along those lines
 + There are usually a lot of files in components since the whole application should be mostly composed of tiny modules

## Vendors Extensions
 + If you have to override or extend a section of any vendor, you need to use the `vendors-extensions` folder
 + Inside this folder the files must be named exactly as the vendors they overwrite

## Pages
 + If you have page-specific styles, it is better to put them in a `pages` folder, in a file named after the page

## Themes
 + On large applications, it is not unusual to have different themes based on a state
 + Add inside the `themes` folder a different file for every state