# Icons-display  
## Preview all icons from all SVG sprites in your project.

SVG sprites are awesome, but it’s a real struggle to find out what icons they contain.  
The inability to preview what icons your project has, leads in most cases to huge icons repetition.  
This simple, yet powerful web program helps you preview all icons, from all SVG sprites in your project.  
And that’s not all! The icons are beautifully grouped by sprites, you get info of the total count, and the count of all icons in each sprite.  
Also you can dynamically resize the icons, if you need a closer look!  

## How to use:
(1) Download this repo to your project's SVG directory;    
(2) In icons-display.html file, add all sprite's names to the "sprites" array;  
(3) If you have NodeJS installed, just double click "Show icons.cmd" file, and the preview will load in your default browser with "live-server" (Linux users must change "cmd" extention to "sh"). Otherwise, install NodeJS (+ NPM, globally), or use any simple web server of your choice, to serve icons-display.html file.   

(Hint: create shortcut of 'Show icons.cmd' on your desktop for easy access)  

## How it works:
The short explanations is: JS sends request to each SVG sprite and adds the code to the DOM. Then iterates all symbol tags, collects their IDs and builds the UI using HTML templates.

![icons display](https://user-images.githubusercontent.com/26719853/156133184-243ec4ba-942a-4d19-ba45-cc0b215d85f2.png)
