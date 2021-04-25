# Introducing CSS 

# Understanding CSS:
Thinking Inside the Box

The key to understanding how CSS works is to
imagine that there is an invisible box around
every HTML element.

# BLOCK & INLINE ELEMENTS

You may remember from
pages 185-186 that in there is a
difference between block level
and inline elements and how
how browsers display them.
Block level elements look
like they start on a new line.
Examples include the <h1>-
<h6>, <p> and <div> elements.
Inline elements flow within the
text and do not start on a new
line. Examples include <b>, <i>,
<img>, <em> and <span>.

CSS allows you to create rules that control the
way that each individual box (and the contents
of that box) is presented.

#CSS Associates Style
rules with HTML
elements

CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.


# CSS Properties Affect
How Elements Are
Displayed
CSS declarations sit inside curly brackets and each is made up of two
parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon.

# Using External CSS

<link> chapter-10/using-external-css.html HTML
The <link> element can be used
in an HTML document to tell the
browser where to find the CSS
file used to style the page. It is an
empty element (meaning it does
not need a closing tag), and it
lives inside the <head> element.
It should use three attributes: 
# href
This specifies the path to the
CSS file (which is often placed in
a folder called css or styles).
# type
This attribute specifies the type
of document being linked to. The
value should be text/css.
# rel
This specifies the relationship
between the HTML page and
the file it is linked to. The value
should be stylesheet when
linking to a CSS file.

An HTML page can use more
than one CSS style sheet. To
do this it could have a <link>
element for every CSS file it
uses. For example, some authors
use one CSS file to control the
presentation (such as fonts and
colors) and a second to control
the layout.

# Using Internal CSS

<style>
You can also include CSS rules
within an HTML page by placing
them inside a <style> element,
which usually sits inside the
<head> element of the page.
The <style> element should use
the type attribute to indicate
that the styles are specified in
CSS. The value should be text/
css.
When building a site with more
than one page, you should use
an external CSS style sheet. This:
● Allows all pages to use the
same style rules (rather than
repeating them in each page).
● Keeps the content separate
from how the page looks.
● Means you can change the
styles used across all pages
by altering just one file
# CSS Selectors 

There are many different types
of CSS selector that allow you to
target rules to specific elements
in an HTML document.
The table on the opposite page
introduces the most commonly
used CSS selectors.
On this page, there is an HTML
file to demonstrate which
elements these CSS selectors
would apply to.
CSS selectors are case sensitive,
so they must match element
names and attribute values
exactly.


# How Css Rules Cascade 

If there are two or more rules
that apply to the same element,
it is important to understand
which will take precedence.
LAST RULE
If the two selectors are identical,
the latter of the two will take
precedence. Here you can see
the second i selector takes
precedence over the first.
SPECIFICITY
If one selector is more specific
than the others, the more
specific rule will take precedence
over more general ones. In this
example:
h1 is more specific than *
p b is more specific than p
p#intro is more specific than p
IMPORTANT
You can add !important after
any property value to indicate
that it should be considered
more important than other rules
that apply to the same element.
Understanding how CSS rules
cascade means you can write
simpler style sheets because
you can create generic rules
that apply to most elements and
then override the properties on
individual elements that need to
appear differently.

# Inheritance

If you specify the font-family
or color properties on the
<body> element, they will apply
to most child elements. This is
because the value of the
font-family property is
inherited by child elements. It
saves you from having to apply
these properties to as many
elements (and results in simpler
style sheets).
You can compare this with
the background-color or
border properties; they are not
inherited by child elements. If
these were inherited by all child
elements then the page could
look quite messy.
You can force a lot of properties
to inherit values from their
parent elements by using
inherit for the value of the
properties. In this example, the
<div> element with a class
called page inherits the padding
size from the CSS rule that
applies to the <body> element.

# Why use External
Style Sheets?

When building a website there are several advantages to placing your
CSS rules in a separate style sheet.

All of your web pages can share
the same style sheet. This is
achieved by using the <link>
element on each HTML page of
your site to link to the same CSS
document. This means that the
same code does not need to be
repeated in every page (which
results in less code and smaller
HTML pages).
Therefore, once the user has
downloaded the CSS stylesheet,
the rest of the site will load
faster. If you want to make a
change to how your site appears,
you only need to edit the one
CSS file and all of your pages
will be updated. For example,
you can change the style of
every <h1> element by altering
the one CSS style sheet, rather
than changing the CSS rules on
every page. The HTML code
will be easier to read and edit
because it does not have lots of
CSS rules in the same document.
It is generally considered good
practice to have the content of
the site separated from the rules
that determine how it appears. 


# Different versions of
CSS & Browser Quirks 

CSS1 was released in 1996 and CSS2 followed two years later. Work on
CSS3 has been ongoing but the major browsers have already started to
implement it 


the same way that there have
been several versions of HTML,
there have also been different
versions of CSS.
Browsers did not implement all
CSS features at once, so some
older browsers do not support
every property.
This is mentioned when it is
likely to affect you, along with
notes where CSS properties
might not behave as expected.
 
 

