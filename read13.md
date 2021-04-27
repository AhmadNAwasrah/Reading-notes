# Links

Links are the defining feature of the web
because they allow you to move from
one web page to another — enabling the
very idea of browsing or surfing. 

# Writing Links

Links are created using the <a> element. Users can click on anything
between the opening <a> tag and the closing </a> tag. You specify
which page you want to link to using the href attribute.

![img](https://qph.fs.quoracdmain-qimg-67615bd1c41490a9200cac3ea1179e99)

# Linking to Other Sites

<a> chapter-04/linking-to-other-sites.html HTML
Links are created using the <a>
element which has an attribute
called href. The value of the
href attribute is the page that
you want people to go to when
they click on the link.
Users can click on anything that
appears between the opening
<a> tag and the closing </a>
tag and will be taken to the page
specified in the href attribute.
When you link to a different
website, the value of the href
attribute will be the full web
address for the site, which is
known as an absolute URL. 

# Absolute URLs

URL stands for Uniform
Resource Locator. Every web
page has its own URL. This is the
web address that you would type
into a browser if you wanted to
visit that specific page.
An absolute URL starts with
the domain name for that site,
and can be followed by the path
to a specific page. If no page is
specified, the site will display the
homepage.
 

 # Linking to Other Pages on the Same Site

 <a>
When you are linking to other
pages within the same site,
you do not need to specify the
domain name in the URL. You
can use a shorthand known as a
relative URL.
If all the pages of the site are in
the same folder, then the value
of the href attribute is just the
name of the file.
If you have different pages of a
site in different folders, then you
can use a slightly more complex
syntax to indicate where the
page is in relation to the current
page. You will learn more about
these on the pages 81-84.
If you look at the download
code for each chapter, you will
see that the index.html file
contains links that use relative
URLs. 
# Directory Structure

On larger websites it's a good idea to organize your code by placing the
pages for each different section of the site into a new folder. Folders on a
website are sometimes referred to as directories. 



# Relative URLs 


Relative URLs can be used when linking to pages within your own
website. They provide a shorthand way of telling the browser where to
find your files.

When you are linking to a page
on your own website, you do
not need to specify the domain
name. You can use relative URLs
which are a shorthand way to tell
the browser where a page is in
relation to the current page.
This is especially helpful when
creating a new website or
learning about HTML because
you can create links between
pages when they are only on
your personal computer (before
you have got a domain name and
uploaded them to the web).
Because you do not need to
repeat the domain name in each
link, they are also quicker to
write.
If all of the files in your site are
in one folder, you simply use the
file name for that page.
If your site is organized into
separate folders (or directories),
you need to tell the browser
how to get from the page it is
currently on to the page that you
are linking to.
If you link to the same page from
two different pages you might,
therefore, need to write two
different relative URLs.


# Email Links 

mailto: chapter-04/email-links.html HTML
To create a link that starts up
the user's email program and
addresses an email to a specified
email address, you use the <a>
element. However, this time the
value of the href attribute starts
with mailto: and is followed by
the email address you want the
email to be sent to.
On the right you can see that
an email link looks just like any
other link but, when it is clicked
on, the user's email program
will open a new email message
and address it to the person
specified in the link. 

# Opening Links in a New Window 

target
If you want a link to open in a
new window, you can use the
target attribute on the opening
<a> tag. The value of this
attribute should be _blank.
One of the most common
reasons a web page author
might want a link to be opened
in a new window is if it points to
another website. In such cases,
they hope the user will return
to the window containing their
site after finishing looking at the
other one.
Generally you should avoid
opening links in a new window,
but if you do, it is considered
good practice to inform users
that the link will open a new
window before they click on it.

# Linking to a Specific Part of the Same Page
At the top of a long page
you might want to add a list
of contents that links to the
corresponding sections lower
down. Or you might want to add
a link from part way down the
page back to the top of it to save
users from having to scroll back
to the top.
Before you can link to a specific
part of a page, you need to
identify the points in the page
that the link will go to. You do
this using the id attribute (which
can be used on every HTML
element). You can see that the
<h1> and <h2> elements in this
example have been given id
attributes that identify those
sections of the page. 

# Layout 


## Key Concepts in Positioning Elements 

Building Blocks
CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box.
Block-level boxes start on a new line and act as the main building blocks
of any layout, while inline boxes flow between surrounding text. You can
control how much space each box takes up by setting the width of the
boxes (and sometimes the height, too). To separate boxes, you can use
borders, margins, padding, and background colors. 
![img](https://www.bitdegree.org/learn/storage/media/images/inline-elements.o.png)

# Containing Elements
 If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.
It is common to group a number of elements together inside a <div>
(or other block-level) element. For example, you might group together
all of the elements that form the header of a site (such as the logo and
the main navigation). The <div> element that contains this group of
elements is then referred to as the containing element.
 

 # Controlling the Position of Elements 

 CSS has the following positioning schemes that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property 


- Normal flow
Every block-level element
appears on a new line, causing
each item to appear lower down
the page than the previous one.
Even if you specify the width
of the boxes and there is space
for two elements to sit side-byside, they will not appear next
to each other. This is the default
behavior (unless you tell the
browser to do something else). 

![img](https://image.slidesharecdn.com/css-160124050959/95/css-79-638.jpg?cb=1453612252)
- Relative Positioning
This moves an element from the
position it would be in normal
flow, shifting it to the top, right,
bottom, or left of where it
would have been placed. This
does not affect the position of
surrounding elements; they stay
in the position they would be in
in normal flow. 
![img](https://i.stack.imgur.com/PIIYY.jpg)
- Absolute positioning
This positions the element
in relation to its containing
element. It is taken out of
normal flow, meaning that it
does not affect the position
of any surrounding elements
(as they simply ignore the
space it would have taken up).
Absolutely positioned elements
move as users scroll up and
down the page 

# Normal Flow
 position:static 

 In normal flow, each block-level
element sits on top of the next
one. Since this is the default
way in which browsers treat
HTML elements, you do not
need a CSS property to indicate
that elements should appear
in normal flow, but the syntax
would be:
position: static;
I have not specified a width
property for the heading
element, so you can see how it
stretches the width of the entire
browser window by default.
The paragraphs are restricted
to 450 pixels wide. This shows
how the elements in normal flow
start on a new line even if they
do not take up the full width of
the browser window. 
# Relative Positioning
 
 position:relative 

 Relative positioning moves an
element in relation to where it
would have been in normal flow.
For example, you can move it 10
pixels lower than it would have
been in normal flow or 20% to
the right.
You can indicate that an element
should be relatively positioned
using the position property
with a value of relative.
You then use the offset
properties (top or bottom and
left or right) to indicate how
far to move the element from
where it would have been in
normal flow.
To move the box up or down,
you can use either the top or
bottom properties.
To move the box horizontally,
you can use either the left or
right properties. 
# Absolute Positioning
 
 position:absolute 
 When the position property
is given a value of absolute,
the box is taken out of normal
flow and no longer affects the
position of other elements on
the page. (They act like it is not
there.)
The box offset properties (top
or bottom and left or right)
specify where the element
should appear in relation to its
containing element.
In this example, the heading has
been positioned at the top of the
page and 500 pixels from its left
edge. The width of the heading is
set to be 250 pixels wide.
The width property has
also been applied to the <p>
elements in this example
to prevent the text from
overlapping and becoming
unreadable 
# Fixed Positioning
 
 position:fixed 
 Fixed positioning is a type
of absolute positioning that
requires the position property
to have a value of fixed.
It positions the element in
relation to the browser window.
Therefore, when a user scrolls
down the page, it stays in the
exact same place. It is a good
idea to try this example in your
browser to see the effect.
To control where the fixed
position box appears in relation
to the browser window, the box
offset properties are used.
In this example, the heading
has been positioned to the top
left hand corner of the browser
window. When the user scrolls
down the page, the paragraphs
disappear behind the heading.
The <p> elements are in normal
flow and ignore the space that
the <h1> element would have
taken up. Therefore, the
margin-top property has
been used to push the first <p>
element below where the fixed
position <h1> element is sitting. 

# Overlapping Elements
 
 When you use relative, fixed, or
absolute positioning, boxes can
overlap. If boxes do overlap, the
elements that appear later in the
HTML code sit on top of those
that are earlier in the page.
If you want to control which
element sits on top, you can use
the z-index property. Its value
is a number, and the higher the
number the closer that element
is to the front. For example, an
element with a z-index of 10
will appear over the top of one
with a z-index of 5.
This example looks similar to
the one on page 368, but it
uses relative positioning for
the <p> elements. Because
the paragraphs are relatively
positioned, by default they
would appear over the top of the
heading as the user scrolls down
the page. To ensure that the
<h1> element stays on top, we
use the z-index property on the
rule for the <h1> element.
The z-index is sometimes
referred to as the stacking
context (as if the blocks have
been stacked on top of each
other on a z axis). If you are
familiar with desktop publishing
packages, it is the equivalent
of using the 'bring to front' and
'send to back' features.
Overlapping Elements

# Floating Elements
 
 float 
 The float property allows you
to take an element in normal
flow and place it as far to the
left or right of the containing
element as possible.
Anything else that sits inside
the containing element will
flow around the element that is
floated.
When you use the float
property, you should also use the
width property to indicate how
wide the floated element should
be. If you do not, results can be
inconsistent but the box is likely
to take up the full width of the
containing element (just like it
would in normal flow).
In this example, a
<blockquote> element is
used to hold a quotation. It's
containing element is the
<body> element.
The <blockquote> element
is floated to the right, and the
paragraphs that follow the quote
flow around the floated element. 

# Using Float to Place Elements Side-by-Side


When elements are floated, the
height of the boxes can affect
where the following elements sit.
In this example, you can see six
paragraphs, each of which has a
width and a float property set.
The fourth paragraph does not
go across to the left hand edge
of the page as one might expect.
Rather it sits right under the
third paragraph. 



# Clearing Floats
 
 clear 

 The clear property allows you
to say that no element (within
the same containing element)
should touch the left or righthand sides of a box. It can take
the following values:
left
The left-hand side of the box
should not touch any other
elements appearing in the same
containing element.
right
The right-hand side of the
box will not touch elements
appearing in the same containing
element.
both
Neither the left nor right-hand
sides of the box will touch
elements appearing in the same
containing element.
none
Elements can touch either side.
In this example, the fourth
paragraph has a class called
clear. The CSS rule for this
class uses the clear property
to indicate that nothing should
touch the left-hand side of it. The
fourth paragraph is therefore
moved further down the page
so no other element touches its
left-hand side. 
# Parents of Floated Elements: Problem

If a containing element only
contains floated elements, some
browsers will treat it as if it is
zero pixels tall.
As you can see in this example,
the one pixel border assigned
to the containing element has
collapsed, so the box looks like a
two pixel line.

# Parents of Floated Elements: Solution

Traditionally, developers got
around this problem by adding
an extra element after the
last floated box (inside the
containing element). A CSS
rule would be applied to this
additional element setting the
clear property to have a value
of both. But this meant that an
extra element was added to the
HTML just to fix the height of the
containing element.
More recently, developers have
opted for a purely CSS-based
solution because it means that
there is no need to add an extra
element to the HTML page after
the floated elements. The pure
CSS solution adds two CSS rules
to the containing element (in this
example the <div> element):
● The overflow property is
given a value auto.
● The width property is set to
100%. 

# CREATING Multi-Column Layouts with Floats

Many web pages use multiple
columns in their design. This
is achieved by using a <div>
element to represent each
column. The following three CSS
properties are used to position
the columns next to each other:
width
This sets the width of the
columns.
float
This positions the columns next
to each other.
margin
This creates a gap between the
columns.
A two-column layout like the one
shown on this page would need
two <div> elements, one for the
main content of the page and
one for the sidebar.
Inside each of the <div>
elements there can be headings,
paragraphs, images, and even
other <div> elements. 


# Screen Sizes
 
 Different visitors to your site will have different sized screens that show
different amounts of information, so your design needs to be able to
work on a range of different sized screens.

# Screen Resolution

Resolution refers to the number of dots a screen shows per inch. Some
devices have a higher resolution than desktop computers and most
operating systems allow users to adjust the resolution of their screens.

# Page Sizes
 
 Because screen sizes and display resolutions vary so much, web
designers often try to create pages of around 960-1000 pixels wide
(since most users will be able to see designs this wide on their screens). 
Judging the height that people
are likely to see on the screen
without scrolling down the page
is much harder. For several
years, designers assumed that
users would see the top 570-
600 pixels of a page without
having to scroll and some tried
to fit all of the key messages in
this area (fearing that people
would not scroll down the page).
As screen sizes have increased
and handheld devices have
become more popular, the
area users will see is far more
variable.
The area of the page that users
would see without scrolling was
often referred as being “above
the fold” (a term newspapers
had originally coined to describe
the area of the front page you
would see if the paper were
folded in half).
It is now recognized that if
someone is interested in the
content of the page, they are
likely to scroll down to see more.
Having said which, usability
studies have shown that visitors
can judge a page in under a
second so it is still important to
let new visitors know that the
site is relevant to them and their
interests.
As a result, many designs still
try to let the user know what the
site is about within the top 570-
600 pixels, as well as hint at
more content below this point.
But do not try to cram too much
into that top area.


# Fixed Width Layouts
 
 Fixed width layout
designs do not
change size as the
user increases
or decreases
the size of their
browser window.
Measurements tend
to be given in pixels.
Fixed Width Layouts
Lorem • Ipsum • Dolor • Consectetur Lorem Ipsum
Lorem ipsum dolor sit amet, consectetur
adipisicing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud
exercitation ullamco laboris nisi ut aliquip ex
ea commodo consequat. Duis aute irure dolor
in reprehenderit in voluptate velit esse cillum
dolore eu fugiat nulla pariatur. Excepteur sint
occaecat.
Lorem ipsum dolor
sit amet, consectetur
adipisicing elit, sed
do eiusmod tempor
incididunt ut labore et
Advantages
● Pixel values are accurate
at controlling size and
positioning of elements.
● The designer has far greater
control over the appearance
and position of items on the
page than with liquid layouts.
● You can control the lengths
of lines of text regardless of
the size of the user's window.
● The size of an image will
always remain the same
relative to the rest of the
page.
Disadvantages
● You can end up with big gaps
around the edge of a page.
● If the user's screen is a much
higher resolution than the
designer's screen, the page
can look smaller and text can
be harder to read.
● If a user increases font sizes,
text might not fit into the
allotted spaces.
● The design works best on
devices that have a site or
resolution similar to that of
desktop or laptop computers.
● The page will often take up
more vertical space than a
liquid layout with the same
content.

# Liquid Layouts
 
 Liquid layout designs
stretch and contract
as the user increases
or decreases the
size of their browser
window. They tend to
use percentages. 
# A Fixed Width Layout
To create a fixed width layout,
the width of the main boxes on
a page will usually be specified
in pixels (and sometimes their
height, too).
Here you can see several <div>
elements, each of which uses an
id or class attribute to indicate
its purpose on the page.
In a book like this, the result of
both the fixed and liquid layouts
look similar. To get a real feel for
them, you need to view them in
your browser and see how they
react when you adjust the size of
the browser window.
The fixed width layout will stay
the same width no matter what
size the browser window is,
whereas the liquid layout will
stretch (or shrink) to fill the
screen. 
# A Liquid Layout

The liquid layout uses
percentages to specify the width
of each box so that the design
will stretch to fit the size of the
screen. 


# Layout Grids 

Composition in any visual art (such as design, painting, or photography)
is the placement or arrangement of visual elements — how they are
organized on a page. Many designers use a grid structure to help them
position items on a page, and the same is true for web designers. 

# CSS Frameworks
 

 CSS frameworks aim to make your life easier by providing the code for
common tasks, such as creating layout grids, styling forms, creating
printer-friendly versions of pages and so on. You can include the CSS
framework code in your projects rather than writing the CSS from scratch. 

# Multiple Style Sheets
 
 ## link 

 On this page you can see the
other technique for including
multiple style sheets. Inside the
<head> element is a separate
<link> element for each style
sheet.
The contents of site.css are
identical to styles.css on the
left hand page, except the code
does not contain @import rules.
As with all style sheets, if two
rules apply to the same element
then rules that appear later in a
document will take precedence
over previous rules.
In the example on this page,
any rules in typography.css
would take precedence over
rules in site.css (because the
typography rules are included
after the other rules).
In the example on the previous
page, the rules in styles.css
would take precedence over the
rules in typography.css. This
is because when the @import
rule is used, that is the point at
which the browser considers the
rules live. 

