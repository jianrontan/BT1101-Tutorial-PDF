# BT1101-Tutorial-to-PDF
Use this to create printable PDFs for your BT1101 Tutorials to use as a cheatsheet

### Install
```
tinytex::install_tinytex()
```
Run this in your R terminal to install tinytex

### Settings
```
output: 
  pdf_document:
    includes:
      in_header: wrapping.tex
editor_options:
  markdown: 
    wrap: 72
```
Copy and paste this in the heading of your R markdown file

### File
```
\usepackage{fvextra}
\DefineVerbatimEnvironment{Highlighting}{Verbatim}{
  commandchars=\\\{\},
  breaklines,
  breaknonspaceingroup,
  breakanywhere
}
```
Download the file or just copy paste this code into your wrapping.tex file. Place it in the same directory as your R markdown file.
