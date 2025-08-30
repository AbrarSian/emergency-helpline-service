 Answer of the following questions :
 
** What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

 * getElementById = It returns a specific element by its id. (Only one element)
 * getElementsByClassName = This thing returns an HTMLCollection of all elements with given class name.
 * querySelector = It returns the first element (with css selector or tags name).
 * querySelectorAll = This thing returns a nodelist of all element.

** How do you create and insert a new element into the DOM?
 *  let div = document.createElement('div')
    div.innerHTML = <h1> Assalamualaikum </h1>
    document.body.appendChild(div);

    In this way,we can add new element to the DOM.

**  What is Event Bubbling and how does it work?  
 *  When an event trigged on a child element, the same event also triggers on its parent elements, bubbling up to the top parent.

** What is Event Delegation in JavaScript? Why is it useful?
 * Event delegation is a way where we put a single event listener on a parent element to handle events on his child elements. and it's useful because it gives improve performance and no need
   to add separate event listener for child.

** What is the difference between preventDefault() and stopPropagation() methods :
 * preventDefault() = it stops default behaivior of browser for an event , like submit button stop his event that relode a page .
 * stopPropagation() = it stops event bubbling up to parent elements
