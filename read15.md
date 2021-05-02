# Domain, Objects, and the DOM

Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names  

![img](https://miro.medium.com/max/2560/1*AxAm_RRyMUsHvHUglQw2zw.jpeg)


# Creating a JavaScript Object
 ith JavaScript, you can define and create your own objects.

There are different ways to create new objects:

Define and create a single object, using an object literal.
Define and create a single object, with the keyword new.
Define an object constructor, and then create objects of the constructed type.


avaScript has a special keyword, this, that you can use within a method to refer to the current object. For example, suppose you have 2 objects, Managerand Intern. Each object have their own name, age and job.  In the function sayHi(), notice there is this.name. When added to the 2 objects they can be called and returns the 'Hello, My name is' then adds the name value from that specific object. 

# CREATING· OBJECTS USING LITERAL NOTATION  

![img](https://miro.medium.com/max/2012/1*gslNlU_BKtZuSyjLMbmp7Q.png)


# DOM 

The HTML DOM (Document Object Model)
When a web page is loaded, the browser creates a Document Object Model of the page.

The HTML DOM model is constructed as a tree of Objects:
 ![img](https://devopedia.org/images/article/282/1930.1596042011.png)

 # With the object model, JavaScript gets all the power it needs to create dynamic HTML:

- JavaScript can change all the HTML elements in the page
- JavaScript can change all the HTML attributes in the page
- JavaScript can change all the CSS styles in the page
- JavaScript can remove existing HTML elements and attributes
- JavaScript can add new HTML elements and attributes
- JavaScript can react to all existing HTML events in the page
- JavaScript can create new HTML events in the page 

# What is the HTML DOM?

The HTML DOM is a standard object model and programming interface for HTML. It defines:

- The HTML elements as objects
- The properties of all HTML elements
- The methods to access all HTML elements
- The events for all HTML elements 


# Finding HTML Elements

Often, with JavaScript, you want to manipulate HTML elements.

To do so, you have to find the elements first. There are several ways to do this:

- Finding HTML elements by id
- Finding HTML elements by tag name
- Finding HTML elements by class name
- Finding HTML elements by CSS selectors
- Finding HTML elements by HTML object collections 
 

# Traversing the DOM with JavaScript


A good JavaScript developer needs to know how to traverse the DOM—it’s the act of selecting an element from another element.

# WHITESPACE NODES 
 
 Traversing the DOM can be difficult because
some browsers add a text node whenever they
come across whitespace between elements. 

# Traversing the DOM can be difficult because
some browsers add a text node whenever they
come across whitespace between elements. 
 # HTML DOM lastElementChild Property



 he lastElementChild property returns the last child element of the specified element.

The difference between this property and lastChild, is that lastChild returns the last child node as an element node, a text node or a comment node (depending on which one's last), while lastElementChild returns the last child node as an element node (ignores text and comment nodes).

This property is read-only.

Tip: Use the children property to return any child element of a specified element.

Tip: To return the first child element of a specified element, use the firstElementChild property.

# ACCESS & UPDATE A TEXT NODE WITH NODEVALUE 

When you select a text node, you can retrieve or amend the content of it
using the node Va 1 ue property. 

n order to use node Va 1 ue, you
must be on a text node, not the
element that contains the text.
This example shows that
navigating from the element
node to a text node can be
complicated.
If you do not know whether there
will be element nodes alongside
text nodes, it is easier to work
with the containing element. 
# ACCESSING TEXT ONLY 
 
 In order to demonstrate the
difference between textContent
and i nnerText, this example
features a CSS rule to hide the
contents of the <em> element.
JAVASCRIPT
The script starts off by getting
the content of the first list item
using both the textContent
property and i nnerText. It then
writes the values after the list.
Finally, the value of the first
list item is then updated to say
sourdough bread. This is done
using the textContent property 

# ACCESS & UPDATE TEXT & MARKUP WITH INNERHTML 


When getting HTML from an
element, the i nnerHTML property
will get the content of an
element and return it as one long
string, including any markup that
the element contains.
When used to set new content
for an element, it will take a
string that can contain markup
and process that string, adding
any elements within it to the
DOM tree. 

# ADDING ELEMENTS USING DOM MANIPULATION 

DOM manipulation offers another technique
to add new content to a page (rather than
i nnerHTML). It involves three steps:
1
CREATE THE ELEMENT
createEl ement ()
You start by creating a new
element node using the
createElement() method.
This element node is stored
in a variable.
When the element node is
created, it is not yet part of the
DOM tree. It is not added to
the DOM tree until step 3.
In the example at the end of the
chapter, you will see another
method that can be used to
insert an element into the DOM
tree. The i nsertBefore ()
method is used to add a new
element before the selected
DOM node.
@ DOCUMENT OBJECT MODEL
2 3
GIVE IT CONTENT ADD IT TO THE DOM
createTextNode() appendChild()
createTextNode() creates a Now that you have your element
new text node. Again, the node (optionally with some content
is stored in a variable. It can be in a text node), you can add
added to the element node using it to the DOM tree using the
the appendChi l d () method. appendChi 1 d () method.
This provides the content for the The appendChi 1 d () method
element, although you can skip allows you to specify which
this step if you want to attach an element you want this node
empty element to the DOM tree. added to, as a child of it.


# ADDING AN ELEMENT TOTHE DOM TREE

createEl ement () creates an
element that can be added to the
DOM tree, in this case an empty
<l i >element for the list. 
This new element is stored
inside a variable called newEl
until it is attached to the DOM
tree later on.  
createTextNode() allows you to
create a new text node to attach
to an element. It is stored in a
variable called newText. 

 



