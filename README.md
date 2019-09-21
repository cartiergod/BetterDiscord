LISTS
* Item 1
* Item 2
 * Item 2a
 * Item 2b
HEADERS
BLOCKQUOTES
As Grace Hopper said:
> I’ve always been more interested
> in the future than in the past.
As Grace Hopper said:
 I've always been more interested
 in the future than in the past.
MARKDOWN
SYNTA X
IMAGES
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
LINKS
http://github.com - automatic!
[GitHub](http://github.com)
Unordered
1. Item 1
2. Item 2
3. Item 3
 * Item 3a
 * Item 3b
Ordered
BACKSLASH ESCAPES
Markdown allows you to use backslash escapes to generate literal characters which
would otherwise have special meaning in Markdown’s formaing syntax.
Markdown provides backslash escapes for
the following characters:
\ backslash
` backtick
* asterisk
_ underscore
{} curly braces
[] square brackets
() parentheses
# hash mark
+ plus sign
- minus sign (hyphen)
. dot
! exclamation mark
EMPHASIS
*This text will be italic*
_This will also be italic_
**This text will be bold**
__This will also be bold__
*You **can** combine them*
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
\*literal asterisks\*
*literal asterisks*
Markdown is a way to style text on the web. You control the display of the document; formaing words as
bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly,
Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *.
GITHUB
FL AVOR ED
MARKDOWN
GitHub.com uses its own version of the Markdown syntax, GFM, that provides an additional set of useful
features, many of which make it easier to work with content on GitHub.com.
USERNAME @MENTIONS
Typing an @ symbol, followed by
a username, will notify that person
to come and view the comment.
This is called an “@mention”,
because you’re mentioning the
individual. You can also @mention
teams within an organization.
ISSUE REFERENCES
Any number that refers to an Issue or
Pull Request will be automatically
converted into a link.
#1
github-flavored-markdown#1
defunkt/github-flavored-markdown#1
TASK LISTS
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](),
**formatting**, and <del>tags</del>
supported
- [x] list syntax required (any
unordered or ordered list
supported)
this is a complete item
this is an incomplete item
@mentions, #refs, links, formaing,
and tags supported
list syntax required (any unordered or
ordered list supported)
FENCED CODE BLOCKS
```javascript
function test() {
 console.log("look ma’, no spaces");
}
```
Markdown coverts text with four leading spaces into a code block; with GFM you can
wrap your code with ``` to create a code block without the leading spaces. Add an
optional language identifier and your code will get syntax highlighting.
function test() {
 console.log("look ma’, no spaces");
}
TABLES
First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column 2
First Header Second Header
Content cell 1 Content cell 2
Content column 1 Content column 2
You can create tables by assembling
a list of words and dividing them
with hyphens - (for the first row),
and then separating each column
with a pipe | :
EMOJI
GitHub supports emoji!
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat:
GitHub supports emoji!
To see a list of every image we
support, check out
www.emoji-cheat-sheet.com
