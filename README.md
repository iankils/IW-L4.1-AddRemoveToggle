# Add, Remove, and Toggle
## How can I change the classes an element has as I interact with the page?

You will be using add, remove, and toggle in various applications. Brushing up on CSS is useful but not required, other than the concept of a class, to get through the lesson . 
This lab is focussed on getting practice creating DOM elements using querySelector and adding and removing classes from the element's class list.

## Objectives
Students will be able to:

- use methods `classList.add()`, `.remove()`, and `.toggle()` to manipulate the list of classes an element contains.

- determine which method makes the most sense based on context.

- refer to documentation for examples on the aforementioned

## Vocabulary
**DOM:** The Document Object Model (DOM) defines the logical structure of documents and the way a document is accessed and manipulated.

**class list:** a read-only property that returns a live DOMTokenList collection of the class attributes of the element. This can then be used to manipulate the class list.

**event listener:** a procedure or function in a computer program that waits for an event to occur.

**query Selector:** The `querySelector()` is a method used for searching and returning the very first element within the document that matches the given selector.

**conditional statement:** statements that are created by the programmer which evaluates actions in the program and evaluates if it's true or false. If-then-else statement allows conditional execution based on the evaluation of an expression.

**toggle:** a function that removes a class from the classList of an element if it exists or adds it if it does not yet exist.

## Part 1

### Mild Activities

1. Find the `ID` for it and change the subheading "Today is September 1st" so that when it is clicked, it turns blue as well.

2. There's currently a reply section with the `ID` `#reply-message` that has the class `hidden`. When the "Reply" button is clicked, remove this class name from the `#reply-message` div.

3. Now that the reply section is open, the "Send Message" and "Cancel" button should both hide the section when clicked. In other words, when they're clicked, the hidden class should be added to the `#reply-message` div again.

### Medium Activities

4. The "Open" button should do 3 things:

    - add the class `is-read` to the entire inbox with ID `#inbox`

    - remove the `hidden` class from the ID `#inbox-message`

    - remove the `hidden` class (un-hide) the "Mark as Unread" button. (See if you can find the ID for this button in the `index.html`)
 
5. Find the ID for the X button at the top right of the inbox message. when clicked it should make the inbox message disappear again.

### Spicy Activities

6. Code the "Mark as Unread" button to hide the inbox message and turn the message background white again. The button itself should also disappear.

7. Let's redo the "Today is September 1st" subtitle. Create your own class with different attributes in it. When the subtitle is clicked, change something somewhere else on the page by adding your newly created class. Here's the tricky part! If the class is already added, remove it, if it's not already added, add it. You may need to check out this [link](https://www.w3schools.com/jsref/met_domtokenlist_contains.asp) on `contains()`.
