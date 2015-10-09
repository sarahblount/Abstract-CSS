# Abstract CSS
A simple CSS framework using ITCSS methodology.

It is intended to work as a boilerplate for starting modular builds swifly and is ideal for managing beautiful scalable UI architecture.

# How it works

Abstract CSS imports sass files in layers of specificity, starting with the most global to the most specific. 

Each file sits in a folder ordered from A to E.

<b>A) Settings</b> - Global variables that could be used anywhere. No CSS output.<br />
<b>B) Tools</b> - Global utilities that could be used anywhere. No CSS output.<br />
<b>C) Generic</b> - Base styling. First CSS to be output.<br />
<b>D) Objects</b> - Class based, non cosmetic global styling<br />
<b>E) Modules</b> - Individual components that make up the UI. This should be most of your project<br />
<b>F) Exclusive</b> - Occasionnaly needed specific location based styles or overrides.<br />

# Example structure
- a.settings
  - globals
  - colours
  - breakpoints
- b.tools
  - grid
  - utilities
- c.generic
  - reset
  - typography
  - buttons
- d.objects
  - layout
- e.modules
  - header
  - primary-nav
  - feature-block
  - search-panel
- f.exclusive
  - registration-page
   
