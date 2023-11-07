# Chart.js and Canvas

## Java Script Canvas: 
* `<canvas>` element allows 2D graphics to be drawn using JavaScript  
* The element has at least two attributes: width and height.   
* You can access width and heiught via DOM properties:   
    `const canvas = document.querySelector('#canvas)`  
    `const width = canvas.width; // 500`   
    `const height = canvas.height; //300`    
* To access you need to use `getContext()` method.  
    * Takes one argument which is type of context. Rendering context allows you to draw shapes, text, images, and other objects.  
* `fillStyle` and `strokeStyle` are properties to determine the fill and stroke styles. You can set these properties to a string, gradient object, or pattern object.

## Chart.js
* Provides chart types, plug ins, and customization options. 
* Renders charts on an HTML5 canvas.  
* Area charts, line charts, bar charts, etc.  
* [Click for Instructions on how to create different charts](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)