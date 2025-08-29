1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

   1. getElementById / etElementsByClassName

      getElementById: it's select one Element. This function returns the ID attribute's value of the element.

      getElementsByClassName: it's select All Element with the given by class name. This function returns the HTML Collection object.

   2. querySelector / querySelectorAll?

      querySelector: querySelector() method returns the first element that matches a CSS selector. If multiple elements occurs, then it returns the result for only the first matching element.

   3. querySelectorAll: querySelectorAll() method returns a NodeList. The querySelectorAll() method returns all the elements within the document which matches the specified CSS selector(s). The index starts with 0

2. How do you create and insert a new element into the DOM?

   const element = document.createElement("element")

3. What is Event Bubbling and how does it work?

   Event Bubbling is a concept in the DOM. It happens when an element receives an event, and that event bubbles up to its parent and ancestor elements in the DOM tree until it gets to the root element.

4. What is JavaScript event delegation?

   An event is a signal that something has happened. It could be a user clicking a button, hovering over an element, pressing a key, or even a system event like the completion of an asynchronous task. In JavaScript, events are represented as objects that contain information about the event and its context.

Why is it useful?

    1. Performance Improvement

    2. Simplified Code

    3. Dynamic Elements

5. What is the difference between preventDefault() and stopPropagation() methods?
