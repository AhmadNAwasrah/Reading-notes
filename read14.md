# Images, Color, Text 

# HTML Images
 
 Images can improve the design and the appearance of a web page.

![img](https://www.wikihow.com/images/thumb/d/dc/Insert-Images-with-HTML-Step-5-Version-5.jpg/v4-460px-Insert-Images-with-HTML-Step-5-Version-5.jpg)

The HTML img  tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The img tag creates a holding space for the referenced image.

The img tag has two required attributes:

src - Specifies the path to the image :


alt - Specifies an alternate text for the image

# Image Size - Width and Height
 You can use the style attribute to specify the width and height of an image.

 ![img](https://www.wikihow.com/images/thumb/0/00/Set-Image-Width-and-Height-Using-HTML-Step-2-Version-3.jpg/v4-460px-Set-Image-Width-and-Height-Using-HTML-Step-2-Version-3.jpg.webp)

 The width and height attributes always define the width and height of the image in pixels.

# Aligning Images Horizontally

# align

 chapter-05/aligning-images-horizontally.html HTML
The align attribute was
commonly used to indicate how
the other parts of a page should
flow around an image. It has
been removed from HTML5
and new websites should use
CSS to control the alignment of
images

left
This aligns the image to the left

right
This aligns the image to the right 

# Aligning Images Vertically

There are three values that the
align attribute can take that
control how the image should
align vertically with the text that
surrounds it:
# top
This aligns the first line of the
surrounding text with the top of
the image.
# middle
This aligns the first line of the
surrounding text with the middle
of the image.
# bottom
This aligns the first line of the
surrounding text with the bottom
of the image

# Tools to Edit & Save Images 

 - Adobe Photoshop
 - Adobe Fireworks
- Pixelmator
- PaintShop Pro
- Paint.net
# Online Editors
- www.photoshop.com
- www.pixlr.com
- www.splashup.com
- www.ipiccy.com

# Image Resolution
mages created for the web should be saved at
a resolution of 72 ppi. The higher the resolution
of the image, the larger the size of the file. 



# Color 
The color CSS property sets the foreground color value of an element's text and text decorations, and sets the <currentcolor> value. currentcolor may be used as an indirect value on other properties and is the default for other color properties, such as border-color 

# CSS Colors
Colors in CSS can be specified by the following methods:

- Hexadecimal colors
- Hexadecimal colors with transparency
- RGB colors
- RGBA colors
- HSL colors
- HSLA colors
- Predefined/Cross-browser color names
- With the currentcolor keyword


# Background Color background-color

CSS treats each HTML element
as if it appears in a box, and the
background-color property
sets the color of the background
for that box.
You can specify your choice of
background color in the same
three ways you can specify
foreground colors: RGB values,
hex codes, and color names
(covered on the next page).
If you do not specify a
background color, then the
background is transparent.
By default, most browser
windows have a white
background, but browser users
can set a background color for
their windows, so if you want
to be sure that the background
is white you can use the
background-color property on
the body element.


# Text 


# HTML Text Formatting
 

 HTML contains several elements for defining text with a special meaning.

 HTML Formatting Elements
Formatting elements were designed to display special types of text:

- b - Bold text
- strong - Important text
- i - Italic text
- em - Emphasized text
- mark - Marked text
- small  - Smaller text
 -del-  - Deleted text
- ins - Inserted text
- sub - Subscript text
- sup  - Superscript text

![img](https://4.bp.blogspot.com/-yd9RMCLq_xA/W-66clFTwdI/AAAAAAAAAAk/rrtK6MZ-V4kZOTfQ7B2bJzNxisefRqj6wCLcBGAs/s280/html-7-638.jpg)

# font-family
 
 Generic Font Families
In CSS there are five generic font families:

- Serif fonts have a small stroke at the edges of each letter. They create a sense of formality and elegance.
- Sans-serif fonts have clean lines (no small strokes attached). They create a modern and minimalistic look.
- Monospace fonts - here all the letters have the same fixed width. They create a mechanical look. 
- Cursive fonts imitate human handwriting.
- Fantasy fonts are decorative/playful fonts.
All the different font names belong to one of the generic font families. 


# Font size 

The font-size property enables
you to specify a size for the
font. There are several ways to
specify the size of a font. The
most common are:
pixels
Pixels are commonly used
because they allow web
designers very precise control
over how much space their text
takes up. The number of pixels is
followed by the letters px.
percentages
The default size of text in
browsers is 16px. So a size of
75% would be the equivalent of
12px, and 200% would be 32px.
If you create a rule to make all
text inside the  body  element
to be 75% of the default size (to
make it 12px), and then specify
another rule that indicates the
content of an element inside the
 body element should be 75%
size, it will be 9px (75% of the
12px font size).
ems
An em is equivalent to the width
of a letter m.

![img](https://i1.wp.com/www.tutorialbrain.com/wp-content/uploads/2019/06/CSS-UNITS.png?fit=474%2C790&ssl=1)
# Font face
![img](https://i.pinimg.com/originals/83/45/1d/83451d27ca4b42103241b825e1f32104.gif)

# font-weight 
The font-weight property
allows you to create bold text.
There are two values that this
property commonly takes:
normal
This causes text to appear at a
normal weight.
bold
This causes text to appear bold.
In this example, you can see
that the element whose class
attribute has a value of credits
has been bolded.
You might wonder why there is
a normal weight. This is because
if, for example, you created a
rule for the body element
indicating that all text inside the
body should appear bold, you
might need an option that allows
the text in certain instances
to appear normal weight. So
it is essentially used as an "off
switch." 


# font-style

If you want to create italic text,
you can use the font-style
property. There are three values
this property can take:
normal
This causes text to appear in a
normal style (as opposed to italic
or oblique).
italic
This causes text to appear italic.
oblique
This causes text to appear
oblique.
In this example, you can see that
the credits have been italicized.
Italic fonts were traditionally
stylized versions of the font
based on calligraphy, whereas an
oblique version would take the
normal version and put it on an
angle.
It is not unusual for the browser
to fail to find an italic version of a
typeface, in which case it will use
an algorithm to place the normal
version of the type on a slant,
which means that a lot of italic
text online is actually oblique. 

# UpperCase & LowerCase 

- text-transform 
The text-transform property
is used to change the case of
text giving it one of the following
values:
- uppercase
This causes the text to appear
uppercase.
- lowercase
This causes the text to appear
lowercase.
- capitalize
This causes the first letter of
each word to appear capitalized.
In this example, the h1
element is uppercase, the h2
element is lowercase, and the
credits are capitalized. In the
HTML, the word by in the credits
had a lowercase b. 

# text-decoration 

The text-decoration property
allows you to specify the
following values:
- none
This removes any decoration
already applied to the text.
- underline
This adds a line underneath the
text.
- overline
This adds a line over the top of
the text.
- line-through
This adds a line through words.
- blink
This animates the text to make it
flash on and off (however this is
generally frowned upon, as it is
considered rather annoying).

# line-height
 Leading (pronounced ledding) is
a term typographers use for the
vertical space between lines of
text. In a typeface, the part of
a letter that drops beneath the
baseline is called a descender,
while the highest point of a letter
is called the ascender. Leading
is measured from the bottom of
the descender on one line to the
top of the ascender on the next.

![img](https://mo3aser.com/wp-content/uploads/2018/06/line-height-31.jpg)


# letter-spacing, word-spacing 
 

 Kerning is the term
typographers use for the space
between each letter. You can
control the space between each
letter with the letter-spacing
property.
It is particularly helpful to
increase the kerning when
your heading or sentence is
all in uppercase. If your text is
in sentence (or normal) case,
increasing or decreasing the
kerning can make it harder to
read.
You can also control the gap
between words using the
word-spacing property.
When you specify a value for
these properties, it should
be given in ems, and it will be
added on top of the default value
specified by the font.
The default gap between
words is set by the typeface
(often around 0.25em), and
it is unlikely that you would
need to change this property
regularly. If the typeface is bold
or you have increased the space
between letters, then a larger
gap between words can increase
readability. 


# text-align 


The text-align property allows
you to control the alignment of
text. The property can take one
of four values:
- left
This indicates that the text
should be left-aligned.
- right
This indicates that the text
should be right-aligned.
- center
This allows you to center text.
 - justify
This indicates that every line in
a paragraph, except the last line,
should be set to take up the full
width of the containing box.
When you have several
paragraphs of text, it is
considered easiest to read if the
text is left-aligned. 


# vertical-align
 
 ![img](https://i.stack.imgur.com/0UAAb.png)

 The vertical-align property is
a common source of confusion.
It is not intended to allow you to
vertically align text in the middle
of block level elements such as
p and div, although it does
have this effect when used with
table cells the td and th
elements).
It is more commonly used with
inline elements such as <]img,
em, or strong elements.
When used with these elements,
it performs a task very similar to
the HTML align attribute used
on the img element, which
you met on pages 103-106. The
values it can take are:
- baseline
- sub
- super
- top
- text-top
- middle
- bottom
 - text-bottom

 # text-indent 

The text-indent property
allows you to indent the first
line of text within an element.
The amount you want the line
indented by can be specified in
a number of ways but is usually
given in pixels or ems.
It can take a negative value,
which means it can be used
to push text off the browser
window. You can see this
technique used in this example,
where the <h1> element uses a
background image to represent
the heading. The text has been
moved far to the left, off the
screen

![img](https://i.ytimg.com/vi/0aV9L6C8e9k/hqdefault.jpg)


# text-shadow 
The text-shadow property has
become commonly used despite
lacking support in all browsers.
It is used to create a drop
shadow, which is a dark version
of the word just behind it and
slightly offset. It can also be used
to create an embossed effect by
adding a shadow that is slightly
lighter than the text. 


![img](https://i.stack.imgur.com/R3rg7.png)

    # first-letter, :first-line

You can specify different values
for the first letter or first line of
text inside an element using
:first-letter and
:first-line.
Technically these are not
properties. They are known as
pseudo-elements.
You specify the pseudo-element
at the end of the selector, and
then specify the declarations as
you would normally for any other
element. 
![img](https://assets.hongkiat.com/uploads/css-better-paragraph/drop-cap.jpg)

# :link, :visited 

Browsers tend to show links
in blue with an underline by
default, and they will change
the color of links that have been
visited to help users know which
pages they have been to.
In CSS, there are two pseudoclasses that allow you to set
different styles for links that
have and have not yet been
visited.
:link
This allows you to set styles
for links that have not yet been
visited.
:visited
This allows you to set styles for
links that have been clicked on.
They are commonly used to
control colors of the links and
also whether they are to appear
underlined or not. 


![img](data:image/png;base64,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)





# :hover, :active, :focus
 
 There are three pseudo-classes
that allow you to change the
appearance of elements when a
user is interacting with them.
- :hover
This is applied when a user
hovers over an element with a
pointing device such as a mouse.
This has commonly been used
to change the appearance of
links and buttons when a user
places their cursor over them. It
is worth noting that such events
do not work on devices that use
touch screens (such as the iPad)
because the screen is not able to
tell when someone is hovering
their finger over an element.
- :active
This is applied when an element
is being activated by a user; for
example, when a button is being
pressed or a link being clicked.
Sometimes this is used to make
a button or link feel more like it
is being pressed by changing the
style or position of the element
slightly.
 - :focus
This is applied when an element
has focus. Any element that
you can interact with, such as a
link you can click on or any form
control can have focus. 

# Attribute Selectors
 ![img](https://i0.wp.com/www.tutorialbrain.com/wp-content/uploads/2019/03/Attribute-Selectors.png?fit=1920%2C1080&ssl=10)