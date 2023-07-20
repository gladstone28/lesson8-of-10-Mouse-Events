link to the lesson is below:

https://www.codecademy.com/courses/build-interactive-websites/lessons/dom-events/exercises/mouse-events

DOM EVENTS WITH JAVASCRIPT
Mouse Events
When you use a mouse device on a website, mouse events fire. You’ve seen the click and wheel events, but, there are even more mouse events to explore!

The mousedown event is fired when the user presses a mouse button down. This is different from a click event because mousedown doesn’t need the mouse button to be released to fire.

![](https://content.codecademy.com/courses/javascript-dom-events/mousedown.png)

The mouseup event is fired when the user releases the mouse button. This is different from the click and mousedown events because mouseup doesn’t depend on the mouse button being pressed down to fire.

![](https://content.codecademy.com/courses/javascript-dom-events/mouseup.png)

The mouseover event is fired when the mouse enters the content of an element.

![](https://content.codecademy.com/courses/javascript-dom-events/mouseover.png)

The mouseout event is fired when the mouse leaves an element.

![](https://content.codecademy.com/courses/javascript-dom-events/mouseout.gif)

Instructions

1. In this exercise, you’ll modify the list elements using mouse events. You can use the reset element that is already programmed to set the other list element back to their default styles.

First, create a function called increaseWidth() that changes the .width of itemOne to any size greater than '400px'.

Hint
You can set the .width of a DOM element by referencing the .style property first.

element.style.width = '100px';
