# ***Read07***

## ***Domain Modeling***
*	*Domain modeling* is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

*	Here's some tips to follow when building your own domain models:
1.	When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2.	Model its attributes with a constructor function that defines and initializes properties.
3.	Model its behaviors with small methods that focus on doing one job well.
4.	Create instances using the new keyword followed by a call to a constructor function.
5.	Store the newly created object in a variable so you can access its properties and methods from **outside.**
6.	Use the this variable within methods so you can access the object's properties and methods from **inside.**
## ***JavaScript***

### Tables

*	A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.
*	*table* element is used to create a table. The contents of the table are written out row by row
*	*tr* for row
*	*td* is a list element inside of *tr*
*	*th*its purpose is to represent the heading for either a column or a row and itâ€™s used inside of *tr* 
*	In long tables we uce *thead* for the headings , *tbody* for the inside part and *tfoot* for what is inside the footer of the table
*	You can make cells of a table span more than one row or column using the rowspan and colspan attributes.

### Objects

*	CREATING OBJECTS USING CONSTRUCTOR SYNTAX, to use the method, you can use the object name followed by the method name
*	The keyword this is commonly used inside functions and objects. Where the function is declared alters what this means. It always refers to one object, usually the object in which the function operates.
*	When a function is created at the top level of a script (that is, not inside another object or function), then it is in the global scope or global context.
*	All global variables also become properties of the window object. so when a function is in the global context, you can access global variables using the window object, as well as its other properties.
*	In JavaScript, data is represented using name/value pairs. To organize your data, you can use an array or object to group a set of related values. In arrays and objects the name is also known as a key.
*	A variable has just one key (the variable name) and one value.
*	Arrays can store multiple pieces of information. Each piece of information is separated by a comma. The order of the values is important because items in an array are assigned a number (called an index).
*	If you want to access items via a property name or key, use an object (but note that each key in the object must be unique). If the order of the items is important, use an array.
*	Browsers come with a set of **built-in objects** that represent things like the browser window and the current web page shown in that window. These built-in objects act like a toolkit for creating interactive web pages.
The first thing you need to do is get to know what tools are available. You can imagine that your new toolkit has three compartments:
- The Browser Object Model contains objects that represent the current browser window or tab. It contains objects that model things like browser history and the device's screen.
- The global JavaScript objects represent things that the JavaScript language needs to create a model of. For example, there is an object that deals only with dates and times.
- The Document Object Model uses objects to create a representation of the current page. It creates a new object for each element (and each individual section of text) within the page.
*	The window object represents the current browser window or tab. It is the topmost object in the Browser Object Model, and it contains other objects that tell you about the browser.
*	The topmost object in the Document Object Model (or DOM) is the document object. It represents the web page loaded into the current browser window or tab.
*	Whenever you have a value that is a string, you can use the properties and methods of the String object on that value. 
*	Whenever you have a value that is a number, you can use the methods and properties of the Number object on it.

***In JavaScript there are six data types:***
1.	String
2.	Number
3.	Boolean
4.	Object
5.	Undefined
6.	Null 
