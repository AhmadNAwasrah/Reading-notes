# Lists 

# Ordered Lists

<ol>
The ordered list is created with
the <ol> element.
<li>
Each item in the list is placed
between an opening <li> tag
and a closing </li> tag. (The li
stands for list item.)
Browsers indent lists by default.
Sometimes you may see a type
attribute used with the <ol>
element to specify the type of
numbering (numbers, letters,
roman numerals and so on). It
is better to use
![img](https://www.w3docs.com/uploads/media/book_gallery/0001/04/ccd38a521877cfd6fedac08b631769c909b4241f.png)

# Unordered Lists


<ul>
The unordered list is created
with the <ul> element.
<li>
Each item in the list is placed
between an opening <li> tag
and a closing </li> tag. (The li
stands for list item.)
Browsers indent lists by default.
Sometimes you may see a type
attribute used with the <ul>
element to specify the type of
bullet point (circles, squares,
diamonds and so on)
![img](https://www.w3docs.com/uploads/media/default/0001/01/3b29b697c81407acb8327bf06b9d1e0a8f98ac7a.png)


# Definition Lists 

<dl>
The definition list is created with
the <dl> element and usually
consists of a series of terms and
their definitions.
Inside the <dl> element you will
usually see pairs of <dt> and
<dd> elements.
<dt>
This is used to contain the term
being defined (the definition
term).
<dd>
This is used to contain the
definition.
Sometimes you might see a list
where there are two terms used
for the same definition or two
different definitions for the same
term.

![img](https://i.ytimg.com/vi/y4QwbHBUjE4/hqdefault.jpg)

# Nested Lists 

You can put a second list inside
an <li> element to create a sublist or nested list.

![img](https://i.stack.imgur.com/rqAiC.jpg)

# Boxes 

# Box Dimensions
 width, height 

 By default a box is sized just big
enough to hold its contents. To
set your own dimensions for a
box you can use the height and
width properties.
The most popular ways to
specify the size of a box are
to use pixels, percentages, or
ems. Traditionally, pixels have
been the most popular method
because they allow designers to
accurately control their size.
When you use percentages,
the size of the box is relative to
the size of the browser window
or, if the box is encased within
another box, it is a percentage of
the size of the containing box.
When you use ems, the size
of the box is based on the size
of text within it. Designers
have recently started to use
percentages and ems more for
measurements as they try to
create designs that are flexible
across devices which have
different-sized screens.

# Limiting Width

**min-width** 
**max-width**


Max-width and min-width can be used together to target a specific range of screen sizes. @media only screen and (max-width: 600px) and (min-width: 400px) {...} The query above will trigger only for screens that are 600-400px wide. This can be used to target specific devices with known widths.


# Limiting Height

**min-height**
**max-height**

In the same way that you might
want to limit the width of a box
on a page, you may also want
to limit the height of it. This is
achieved using the min-height
and max-height properties.
The example on this page
demonstrates these properties
in action. It also shows you what
happens when the content of the
box takes up more space than
the size specified for the box.
If the box is not big enough to
hold the content, and the content
expands outside the box it can
look very messy. To control
what happens when there is not
enough space for the content of
a box

# Overflowing Content

**overflow**

The overflow property tells the
browser what to do if the content
contained within a box is larger
than the box itself. It can have
one of two values:
hidden
This property simply hides any
extra content that does not fit in
the box.
scroll
This property adds a scrollbar to
the box so that users can scroll
to see the missing content.
On the left, you can see two
boxes whose contents expand
beyond their set dimensions. The
first example has the overflow
property with a value of hidden.
The second example has the
overflow property with a value
of scroll.
The overflow property is
particularly handy because some
browsers allow users to adjust
the size of the text to appear as
large or as small as they want. If
the text is set too large then the
page can become an unreadable
mess. Hiding the overflow on
such boxes helps prevent items
overlapping on the page.

# Border, Margin & Padding

![img](https://s1.o7planning.com/en/12495/images/51121937.png)

# White space & Vertical Margin

The padding and
margin properties
are very helpful
in adding space
between various
items on the page.

# Border Width

The border-width property
is used to control the width
of a border. The value of this
property can either be given
in pixels or using one of the
following values:
thin
medium
thick
(You cannot use percentages
with this property.)
You can control the individual
size of borders using four
separate properties:
border-top-width
border-right-width
border-bottom-width
border-left-width
You can also specify different
widths for the four border values
in one property, like so:
border-width: 2px 1px 1px
2px;
The values here appear in
clockwise order: top, right,
bottom, left.


![img](https://media.geeksforgeeks.org/wp-content/uploads/borderbottomwidth.png)

# Border Style & color
 
 You can control the style of a
border using the border-style
property. This property can take
the following values:
solid a single solid line
dotted a series of square dots
(if your border is 2px wide, then
the dots are 2px squared with a
2px gap between each dot)
dashed a series of short lines
double two solid lines (the
value of the border-width
property creates the sum of the
two lines)
groove appears to be carved
into the page
ridge appears to stick out from
the page
inset appears embedded into
the page
outset looks like it is coming
out of the screen
hidden / none no border is
shown
You can individually change the
styles of different borders using:
border-top-style
border-left-style
border-right-style
border-bottom-style

![img](https://s3.amazonaws.com/webucator-how-tos/2304.png)

# padding 

You can specify different values
for each side of a box using:
padding-top
padding-right
padding-bottom
padding-left

# margin 
You can specify values for each
side of a box using:
margin-top
margin-right
margin-bottom
margin-left

# Hiding Boxes
 

 visibility 
 The visibility property allows
you to hide boxes from users
but It leaves a space where the
element would have been.
This property can take two
values:
hidden
This hides the element.
visible
This shows the element.
If the visibility of an element
is set to hidden, a blank space
will appear in its place.
If you do not want a blank space
to appear, then you should use
the display property with
a value of none instead (as
covered on the previous page). 


# CSS3: Border Images
 
 border-image
 
 The border-image property
applies an image to the border of
any box. It takes a background
image and slices it into nine
pieces.
Here is the image. I have
added marks where it is
sliced in the example,
taking 18 pixels from each corner
to place an entire circle in each
corner. The corner slices are
always placed in the four corners
of the box, but we have a choice
whether the sides are stretched
or repeated.
This property requires three
pieces of information:
1: The URL of the image
2: Where to slice the image
3: What to do with the straight
edges; the possible values are:
 stretch stretches the image
 repeat repeats the image
 round like repeat but if the
tiles do not fit exactly, scales
the tile image so they will
The box must also have a border
width for the image to be shown.
The -moz-border-image
and -webkit-border-image
properties are not in the CSS
specification but help earlier
versions of Chrome, Firefox, and
Safari display this effect.

![img](https://i.stack.imgur.com/pgJhM.png)

# CSS3: Box Shadows
 

 box-shadow

The box-shadow property
allows you to add a drop shadow
around a box. It works just like
the text-shadow property that
you met on page 288. It must
use at least the first of these two
values as well as a color:
Horizontal offset
Negative values position the
shadow to the left of the box.
Vertical offset
Negative values position the
shadow to the top of the box.
Blur distance
If omitted, the shadow is a solid
line like a border.
Spread of shadow
If used, a positive value will
cause the shadow to expand in
all directions, and a negative
value will make it contract.
The inset keyword can also
be used before these values to
create an inner-shadow.
Chrome, Firefox, and Safari were
quick to support this property
using the -moz-box-shadow
and -webkit-box-shadow
properties. 

![img](https://static1.tothenew.com/blog/wp-content/uploads/2016/07/11.png)

# CSS3: Rounded Corners
 
 border-radius 
 You can specify individual values
for each corner of a box using:
border-top-right-radius
border-bottom-right-radius
border-bottom-left-radius
border-top-left-radius 

![img](https://i2.wp.com/www.tutorialbrain.com/wp-content/uploads/2019/03/border-radius.JPG.png?fit=1284%2C563&ssl=1)









