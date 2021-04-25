 # Text 

 #  Headings 

 <h1>
<h2>
<h3>
<h4>
<h5>
<h6>
HTML has six "levels" of headings:

![img](https://www.tutorialrepublic.com/lib/images/html/html-headings.png)

# Paragraphs
<p>
To create a paragraph, surround
the words that make up the
paragraph with an opening <p>
tag and closing </p> tag.
By default, a browser will show
each paragraph on a new line
with some space between it and
any subsequent paragraphs.

# Bold & Italic
<b>
By enclosing words in the tags
<b> and </b> we can make
characters appear bold.
The <b> element also represents
a section of text that would be
presented in a visually different
way (for example key words in a
paragraph) although the use of
the <b> element does not imply
any additional meaning.

<i>
By enclosing words in the tags
<i> and </i> we can make
characters appear italic.
The <i> element also represents
a section of text that would be
said in a different way from
surrounding content — such as
technical terms, names of ships,
foreign words, thoughts, or other
terms that would usually be
italicized.


# Superscript & Subscrip 

<sup>
The <sup> element is used
to contain characters that
should be superscript such
as the suffixes of dates or
mathematical concepts .

<sub>
The <sub> element is used to
contain characters that should
be subscript. 

# White Space 

In order to make code easier to
read, web page authors often
add extra spaces or start some
elements on new lines.
When the browser comes across
two or more spaces next to each
other, it only displays one space.
Similarly if it comes across a line
break, it treats that as a single
space too. This is known as
white space collapsing.
You will often see that web page
authors take advantage of white
space collapsing to indent their
code in order to make it easier
to follow.

# Line Breaks & Horizontal Rules

<br />
As you have already seen, the
browser will automatically show
each new paragraph or heading
on a new line. But if you wanted
to add a line break inside the
middle of a paragraph you can
use the line break tag <br />.

<hr />
To create a break between
themes — such as a change of
topic in a book or a new scene
in a play — you can add a
horizontal rule between sections
using the <hr /> tag.

# Visual Editors & Their Code views
Content management systems and HTML editors such as Dreamweaver
usually have two views of the page you are creating: a visual editor and a
code view.
Visual editors often resemble
word processors. Although
each editor will differ slightly,
there are some features that
are common to most editors
that allow you to control the
presentation of text.

# Semantic Markup 

There are some text elements that are not intended to affect the
structure of your web pages, but they do add extra information to the
pages — they are known as semantic markup. 

# Strong & Emphasis 
<strong>
The use of the <strong>
element indicates that its
content has strong importance.
For example, the words
contained in this element might
be said with strong emphasis.
By default, browsers will show
the contents of a <strong>
element in bold.
 
 <em>
The <em> element indicates
emphasis that subtly changes
the meaning of a sentence.
By default browsers will show
the contents of an <em> element
in italic.
# Quotations 

There are two elements
commonly used for marking up
quotations:
<blockquote>
The <blockquote> element is
used for longer quotes that take
up an entire paragraph. Note
how the <p> element is still
used inside the <blockquote>
element.
Browsers tend to indent the
contents of the <blockquote>
element, however you should not
use this element just to indent a
piece of text — rather you should
achieve this effect using CSS.
<q>
The <q> element is used for
shorter quotes that sit within
a paragraph. Browsers are
supposed to put quotes around
the <q> element, however
Internet Explorer does not —
therefore many people avoid
using the <q> element.
Both elements may use the cite
attribute to indicate where the
quote is from. Its value should
be a URL that will have more
information about the source of
the quotation. 


# Abbreviations & Acronyms

<abbr> chapter-02/abbreviations.html HTML
If you use an abbreviation or
an acronym, then the <abbr>
element can be used. A title
attribute on the opening tag is
used to specify the full term.
In HTML 4 there was a separate
<acronym> element for
acronyms. To spell out the full
form of the acronym, the title
attribute was used (as with the
<abbr> element above). HTML5
just uses the <abbr> element
for both abbreviations and
acronyms. 


# Citations & Definitions 

<cite>
When you are referencing a
piece of work such as a book,
film or research paper, the
<cite> element can be used
to indicate where the citation is
from.
In HTML5, <cite> should not
really be used for a person's
name — but it was allowed in
HTML 4, so most people are
likely to continue to use it.
Browsers will render the content
of a <cite> element in italics.
<dfn>
The first time you explain some
new terminology (perhaps an
academic concept or some
jargon) in a document, it is
known as the defining instance
of it.
The <dfn> element is used to
indicate the defining instance of
a new term.
Some browsers show the
content of the <dfn> element in
italics. Safari and Chrome do not
change its appearance.

# Author Details
 <address> chapter-02/address.html HTML
The <address> element has
quite a specific use: to contain
contact details for the author of
the page.
It can contain a physical address,
but it does not have to. For
example, it may also contain a
phone number or email address.
Browsers often display the
content of the <address>
element in italics.
You may also be interested in
something called the hCard
microformat for adding physical
address information to your
markup.
Online extra:
You can find out more about
hCards on the website
accompanying this book.

# Changes to Content 

<ins>
<del>
The <ins> element can be used
to show content that has been
inserted into a document, while
the <del> element can show text
that has been deleted from it.
The content of a <ins> element
is usually underlined, while the
content of a <del> element
usually has a line through it 

<s>
The <s> element indicates
something that is no longer
accurate or relevant (but that
should not be deleted).
Visually the content of an <s>
element will usually be displayed
with a line through the center.
Older versions of HTML had a
<u> element for content that
was underlined, but this is being
phased out



