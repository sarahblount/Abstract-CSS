# Abstract CSS
A simple CSS framework using ITCSS methodlogy.

It is intended to work as a boilerplate for starting modular builds swifly and is perfect for managing scalability.

# How it works

Abstract CSS imports sass files in layers of specificity, starting with the most global to the most specific. 

Each file sits in a folder ordered from A to E.

Within each folder, files are numerically ordered for increased organisation of your project.

<b>A) Settings</b> - Global variables that could be used anywhere. No CSS output.<br />
<b>B) Tools</b> - Global utilities that could be used anywhere. No CSS output.<br />
<b>C) Generic</b> - Base styling. First CSS to be output.<br />
<b>D) Objects</b> - Class based, non cosmetic global styling<br />
<b>E) Modules</b> - Individual components that make up the UI. This should be most of your project<br />
<b>F) Exclusive</b> - Occasionnaly needed specific location based styles or overrides.<br />

# Example structure
- a.settings
  - 1.globals
  - 2.colours
  - 3.breakpoints
- b.tools
  - 1.grid
  - 2.mixins
  - 2.animations
- c.generic
  - 1.reset
  - 2.typography
  - 3.buttons
- d.objects
  - 1.layout
- e.modules
  - 1.header
  - 2.primary-nav
  - 3.feature-block
  - 4.search-panel
- f.exclusive
  - 1.registration-page
   
