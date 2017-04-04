## Website Performance Optimization portfolio project

- Changes Portfolio Site:
I inlined the complete css and set the google analytics to async, I also deleted all the comments and changed the code so that it has less lines.
Another optimization I made were resizing the images and lower down the quality to improve the performance.

- Changes Pizza Site:
Like it was already showed in the course I made resizing pizza faster and I followed the steps in web cast.
AT the document.addEventListener function I changed the for-loops ending from 200 pizzas to 40, because we dont see more at the page. 
In CSS I added "backface-visibility: hidden;" to the .mover class. On top of that I changed "var items = document. ('.mover');" to 
"var items = document.getElementsByClassName('mover');" at the updatePositions function.

I also changed to beginning of the updatePositions functions for-loop from: "for (var i = 0; i < items.length; i++) {" 
to: "var i;
  var l = items.length;
  for (i = 0; i < l; i++) {"



Steps required to successfully run the application locally:
Open index.html in your browser. 