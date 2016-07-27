# DOManipulator

Based on JQuery, DOManipulator makes it easier to work with DOM elements.  It can also be used to make XMLHttpRequests

## Public API
* $l.extend(target [, object1 ][, objectN ]) - merge optional objects into target object
* $l.ajax(options) - asynchronous XMLHttpRequest

## DOMNodeCollection

### Constructor
* $l(selector) - create new DOMNodeCollection or add DOMContentLoaded callback

### DOM Manipulation
* addClass(className) - adds class to each element in collection
* removeClass(className) - removes class to each element in collection
* append(child) - adds child to each element in collection
* attr(attrName, value) - gets and sets attribute for each element in collection
* empty() - sets DOM elements to empty string
* on(event, callback) - adds an event listener to DOM elements
* off(event, callback) - removes event listener from DOM elements
* remove() - removes DOM elements

### DOM Retrieval

* children() - returns children of elements in collection
* parent() - returns parent of each element in collection
* find(selector) - returns collection of DOM elements by selector
* forEach() - iterates through the collection of DOM elements
