                  #HTML OVIERVIEW 
![html](http://itsourcecode.com/wp-content/uploads/2015/10/html.jpg)
Understanding HTML and CSS can help anyone who works with the web; designers can create more attractive and usable sites, website editors can create better content, marketers
can communicate with their audience more effectively, and
managers can commission better sites and get the best out
of their teams.


# HTML Contents 
# body 
 You met the <body> element
in the first example we created.
Everything inside this element is
shown inside the main browser
window.

# head
  Before the <body> element you
will often see a <head> element.
This contains information
about the page (rather than
information that is shown within
the main part of the browser
window that is highlighted in
blue on the opposite page).
You will usually find a <title>
element inside the <head>
element.

# title 
 The contents of the <title>
element are either shown in the
top of the browser, above where
you usually type in the URL of
the page you want to visit, or
on the tab for that page (if your
browser uses tabs to allow you
to view multiple pages at the
same time).

              # HTML General Information 
![Gieral information](https://tse1.mm.bing.net/th?id=OIP.l4CPznhY2M5FicAsg3mLSQHaD2&pid=Api&P=0&w=313&h=163)


# HTML pages are text documents.
# HTML uses tags (characters that sit inside angled
brackets) to give the information they surround special
meaning.
# Tags are often referred to as elements.
# Tags usually come in pairs. The opening tag denotes
the start of a piece of content; the closing tag denotes
the end.
# Opening tags can carry attributes, which tell us more
about the content of that element.
# Attributes require a name and a value.
# To learn HTML you need to know what tags are
available for you to use, what they do, and where they
can go.
                # The Evolution of HTML
# Each new version was designed
to be an improvement on the
last (with new elements and
attributes added and older code
removed) There have also been several
versions of each browser used to
view web pages, each of which
implements new code. Not all
web users, however, have the
latest browsers installed on
their computers, which means
that not everyone will be able to
view all of the latest features and
markup.
      # HTML 4 
# With the exception of a few
elements added in HTML5
(which have been highlighted),
the elements you have seen in
this book were all available in
HTML 4.
Although HTML 4 had some
presentational elements to
control the appearance of pages,
authors are not recommended to
use them any more. (Examples
include the <center> element
for centering content on a
page, <font> for controlling
the appearance of text, and
<strike> to put a line through
the text — all of these can be
achieved with CSS instead.)
# HTML5
     Released 2000
In HTML5, web page authors do
not need to close all tags, and
new elements and attributes will
be introduced. At the time of
writing, the HTML5 specification
had not been completed, but
the major browser makers had
started to implement many of
the new features, and web page
authors were rapidly adopting
the new markup.
Despite the fact that HTML5
is not yet completed, you can
safely take advantage of the
new features of the language as
long as you endeavour to ensure
that users with older browsers
will be able to view your pages
(even though some of the extra
features will not be visible to
them).


# Comments in HTML 

<!-- -->
If you want to add a comment
to your code that will not be
visible in the user's browser, you
can add the text between these
characters:
<!-- comment goes here -->
   # ID Attribute 

Every HTML element can carry
the id attribute. It is used to
uniquely identify that element
from other elements on the
page. Its value should start with
a letter or an underscore (not a
number or any other character).
It is important that no two
elements on the same page
have the same value for their id
attributes (otherwise the value is
no longer unique).

 # Class Attribute

 Every HTML element can
also carry a class attribute.
Sometimes, rather than uniquely
identifying one element within
a document, you will want a
way to identify several elements
as being different from the
other elements on the page.
For example, you might have
some paragraphs of text that
contain information that is more
important than others and want
to distinguish these elements, or
you might want to differentiate
between links that point to other
pages on your own site and links
that point to external sites. 
# Block Elements
Some elements will always
appear to start on a new line in
the browser window. These are
known as block level elements.

# Inline Elements

Some elements will always
appear to continue on the
same line as their neighbouring
elements. These are known as
inline elements

#Grouping Text & Elements In a Block 
<div> chapter-08/grouping-block-elements.html HTML
The <div> element allows you to
group a set of elements together
in one block-level box.
![div in html](https://www.wikihow.com/images/thumb/4/45/4794787-2.JPG/aid4794787-v4-728px-4794787-2.JPG)
#Grouping Text & Elements Inline
The <span> element acts like
an inline equivalent of the <div>
element. It is used to either:
1. Contain a section of text
where there is no other suitable
element to differentiate it from
its surrounding text
2. Contain a number of inline
elements
The most common reason why
people use <span> elements
is so that they can control the
appearance of the content of
these elements using CSS.
# IFrames
An iframe is like a little window
that has been cut into your
page — and in that window you
can see another page. The term
iframe is an abbreviation of inline
frame.
One common use of iframes
(that you may have seen on
various websites) is to embed
a Google Map into a page. The
content of the iframe can be any
html page (either located on the
same server or anywhere else on
the web).

         # General information in markup 

 # DOCTYPES tell browsers which version of HTML you
are using.
# You can add comments to your code between the
<!-- and --> markers.
# The id and class attributes allow you to identify
particular elements.
# The <div> and <span> elements allow you to group
block-level and inline elements together.
# <iframes> cut windows into your web pages through
which other pages can be displayed.
# The <meta> tag allows you to supply all kinds of
information about your web page.
# Escape characters are used to include special
characters in your pages such as <, >, and ©.




                # HTML5 Layout 

  ![html layout](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ1zGy7Tzlc8i77msW7SNoavymJX6Lhr52n3Q&usqp=CAU)



# Traditional HTML Layouts

## For a long time, web page authors used <div> elements to group
together related elements on the page (such as the elements that form a
header, an article, footer or sidebar). Authors used class or id attributes
to indicate the role of the <div> element in the structure of the page.

# New Html5 Layout Elements

## HTML5 introduces a new set of elements that allow you to divide up the
parts of a page. The names of these elements indicate the kind of content
you will find in them. They are still subject to change, but that has not
stopped many web page authors using them already.
# Headers & Footers
   <header> <footer>

    The <header> and <footer>
 elements can be used for:
● The## that appears at the top or
 bottom of every page on the
 site.
 ● A header or footer for an
 individual <article> or
 <section> within the page.
![header and fotter ](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTYd7-2l5SmIpY3wlff3swts2FiyH3K9Aq0ug&usqp=CAU)

 Navigation
# <nav> 
 The <nav> element is used to
contain the major navigational
blocks on the site such as the
primary site navigation.
Going back to our blog example,
if you wanted to finish an article
with links to related blog posts,
these would not be counted as
major navigational blocks and
therefore should not sit inside a
<nav> element.
 Articles 
# <article> 
The <article> element acts as
a container for any section of a
page that could stand alone and
potentially be syndicated.
This could be an individual
article or blog entry, a comment
or forum post, or any other
independent piece of content.
If a page contains several articles
(or even summaries of several
articles), then each individual
article would live inside its own
<article> element.

 Article 
The <aside> element has two
purposes, depending on whether
it is inside an <article>
element or not.
When the <aside> element
is used inside an <article>
element, it should contain
information that is related to the
article but not essential to its
overall meaning. For example, a
pullquote or glossary might be
considered as an aside to the
article it relates to.
When the <aside> element is
used outside of an <article>
element, it acts as a container
for content that is related to
the entire page. For example,
it might contain links to other
sections of the site, a list of
recent posts, a search box, or
recent tweets by the author

 Sections

The <section> element groups
related content together, and
typically each section would
have its own heading.
For example, on a homepage
there may be several <section>
elements to contain different
sections of the page, such as
latest news, top products, and
newsletter signup.
Because the <section> element
groups related items together,
it may contain several distinct
<article> elements that have a
common theme or purpose.
Alternatively, if you have a
page with a long article, the
<section> element can be
used to split the article up into
separate sections

 Heading Groups

The purpose of the <hgroup>
element is to group together a
set of one or more <h1> through
<h6> elements so that they are
treated as one single heading.
For example, the <hgroup>
element could be used to contain
both a title inside an <h2>
element and a subtitle within an
<h3> element.
This element has had a mixed
reception. When it was first
proposed by the people
developing HTML5, there were
some complaints and it was
withdrawn from the HTML5
proposals. However, some
people changed their minds and
it has been added it back into the
language. Some developers do
not like the use of the <hgroup>
element, and prefer to place a
subtitle inside a <p> element
(using an attribute to indicate
that it is a subheading).

# Figures

It is important to note that the
article should still make sense
if the content of the <figure>
element were moved (to another
part of the page, or even to a
different page altogether).
For this reason, it should only be
used when the content simply
references the element (and not
for something that is absolutely
integral to the flow of a page).
Examples of usage include:
● Images
● Videos
● Graphs
● Diagrams
● Code samples
● Text that supports the main
body of an article
The <figure> element should
also contain a <figcaption>
element which provides a text
decription for the content of
the <figure> element. In
this example, you can see a
<figure> has been added inside
the <article> element.

  Sectioning Elements

 It may seem strange to follow
these new elements by revisiting
the <div> element again. (After
all, the new elements are often
going to be used in its place.)
However, the <div> element
will remain an important way to
group together related elements,
because you should not be using
these new elements that you
have just met for purposes other
than those explicitly stated.
Where there is no suitable
element to group a set of
elements, the <div> element will
still be used. In this example, it is
used as a wrapper for the entire
page.
Some people have asked why
there is no <content> element
to contain the main part of
a page. The reason is that
anything that lies outside of the
<header>, <footer> or <aside>
elements can be considered as
the main content.

# Linking Around Block-Level Elements

HTML5 allows web page authors
to place an <a> element around
a block level element that
contains child elements. This
allows you to turn an entire block
into a link.
This is not a new element in
HTML5, but it was not seen as a
correct usage of the <a> element
in earlier versions of HTML.

# Helping Older Browsers Understand 
 Older browsers that do not
know the new HTML5 elements
will automatically treat them as
inline elements. Therefore, to
help older browsers, you should
include the line of CSS on the
left which states which new
elements should be rendered as
block-level elements.
Also, IE9 was the first version of
Internet Explorer to allow CSS
rules to be associated with these
new HTML5 layout elements.
In order to style these elements
using earlier versions of IE, you
need to use a simple JavaScript
known as the HTML5 shiv or
HTML5 shim. 

        # General information HTML5 LAYOUT

#The new HTML5 elements indicate the purpose of
different parts of a web page and help to describe
its structure.
# The new elements provide clearer code (compared
with using multiple <div> elements).
# Older browsers that do not understand HTML5
elements need to be told which elements are
block-level elements.
# To make HTML5 elements work in Internet Explorer 8
(and older versions of IE), extra JavaScript is needed,
which is available free from Google.
