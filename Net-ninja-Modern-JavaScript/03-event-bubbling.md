# Event Bubbling
Event bubbling is a topic that many people can skip when learning JavaScript. Event bubbling is when a event is occurred that event becomes that event target. 

When this happens JavaScript will look if there are any event listeners for the target and will fire the callback function for the selected target event. That event then bubbles up from the target to its parent element and again JavaScript will look for an event listener and fire the callback and this cycle continues.

We can use the `stopPropagation` method to stop event bubbling whenever we want to in our code.
