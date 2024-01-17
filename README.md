# Icons-display  
## Preview all icons from all SVG sprites in your project.

Preview all icons from SVG sprites in your project.

SVG sprites are fantastic, but identifying the icons they contain can be a challenge. The lack of a preview often leads to unnecessary icon repetition in projects.
Introducing Icons Display, a simple yet powerful web app designed to help you preview all icons from every SVG sprite in your project. 
Icons are neatly organized by sprites, providing you with total counts and individual counts for each sprite. You also have the flexibility to dynamically resize icons for a closer look!  

## How to use:
(1) Download this repository to your project's SVG directory.    
(2) In the "icons-display.html" file, add all sprite names to the "sprites" array.
(3) If you have NodeJS installed, double click on "Show icons.cmd" to load the preview in your default browser using "live-server" (Linux users should change the file extension from "cmd" to "sh"). Alternatively, install NodeJS (+ NPM, globally) or use any simple web server of your choice to serve the icons-display.html file.   

(Hint: Create a shortcut for 'Show icons.cmd' on your desktop for easy access.)  

## How it works:
In a nutshell, JavaScript sends requests to each SVG sprite, adds the code to the DOM, and iterates through all symbol tags. It collects their IDs and builds the UI using HTML templates.

![icons display](https://user-images.githubusercontent.com/26719853/156133184-243ec4ba-942a-4d19-ba45-cc0b215d85f2.png)
