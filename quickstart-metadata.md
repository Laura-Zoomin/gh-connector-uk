---
title: Lorem ipsum dolor sit amet
author: Marcus Antonius
keywords: latin, ipsum, template, draft
tags: cat, dog, carrot
labels: enterprise, open-source, admin
---

<meta name="description" content="The quick brown fox jumped over the lazy dog.">
<meta name="author" content="John Smith">
<meta name ="keywords" content="html, markdown, java">

# Heading 1

Here is my text. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas vulputate pretium lacus. Mauris venenatis est at neque varius scelerisque. Maecenas tincidunt risus a tempor suscipit. Curabitur vel nibh libero. Nunc maximus pharetra mauris id dictum. Suspendisse rutrum nibh enim, sed accumsan purus facilisis vitae. Pellentesque nec vulputate lectus. Nunc hendrerit libero ac posuere sodales.

## Installation 
Fusce at interdum lacus. Integer iaculis nunc sit amet erat ullamcorper, a dapibus nisi convallis. In et odio a dolor condimentum hendrerit:
* Curabitur eu urna eget tortor imperdiet placerat.
* Sed gravida rutrum odio, aliquet varius tellus sollicitudin a.
* In metus elit, cursus vitae posuere et, mattis a nulla.
* Maecenas suscipit metus lorem, at faucibus felis tempus a.
* Vestibulum venenatis risus id dolor dictum, vitae auctor nisl pellentesque.
* Nulla in tellus convallis, eleifend purus sed, viverra orci.
* Suspendisse nec pulvinar sem.
* Aliquam ornare gravida lectus vel posuere. Vestibulum vitae efficitur dolor.
* Aliquam tempus pharetra imperdiet.

## Heading 2

Nunc sagittis urna non arcu vehicula, in ultrices neque sagittis. Phasellus condimentum aliquet porta. Nulla vel urna mi. Nam vestibulum arcu enim, eu vehicula ex porttitor in. Quisque dignissim risus eu fermentum suscipit. Aenean condimentum euismod urna a congue. Vivamus neque turpis, pellentesque vel nibh ut, vestibulum finibus libero. Proin consequat convallis interdum. Sed at rhoncus tellus. Phasellus rutrum, risus vitae sagittis sagittis, lorem orci ultricies nibh, in bibendum lectus odio a dolor. Nunc ac pellentesque elit. Donec at nibh sagittis, gravida elit sed, sagittis lorem. Nunc luctus finibus mauris quis pharetra. Pellentesque id convallis justo. In sit amet sem vitae sapien placerat viverra.

![image](GitHub-UK.png)

### Heading 3

Nunc sagittis urna non arcu vehicula, in ultrices neque sagittis. Phasellus condimentum aliquet porta. Nulla vel urna mi. Nam vestibulum arcu enim, eu vehicula ex porttitor in. Quisque dignissim risus eu fermentum suscipit. Aenean condimentum euismod urna a congue. Vivamus neque turpis, pellentesque vel nibh ut, vestibulum finibus libero. Proin consequat convallis interdum. Sed at rhoncus tellus. Phasellus rutrum, risus vitae sagittis sagittis, lorem orci ultricies nibh, in bibendum lectus odio a dolor. Nunc ac pellentesque elit. Donec at nibh sagittis, gravida elit sed, sagittis lorem. Nunc luctus finibus mauris quis pharetra. Pellentesque id convallis justo. In sit amet sem vitae sapien placerat viverra.

| Month    | Amount   | To        | For     |
| -------- | -------- | --------- | ------- |
| January  | $250     | Lisa      | Bday    |
| February | $80      | George    | Gas     |
| March    | $420     | Mary      | Rent    |


### Code block no syntax highligting, tic marks not showing

```
function test() {
  console.log("notice the blank line before this function?");
}
```

### Code block no syntax highligting, tic marks showing


````
```
function test() {
  console.log("notice the blank line before this function?");
}
```
````

### Code block with syntax highlighting

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```


#### (Optional) Sub step 1 - {Subtask name}

Paragraphs are separated by a blank line.

2nd paragraph. *Italic*, **bold**, and `monospace`. Itemized lists
look like:

  * this one
  * that one
  * the other one

Note that --- not considering the asterisk --- the actual text
content starts at 4-columns in.

> Block quotes are
> written like so.
>
> They can span multiple paragraphs,
> if you like.

Use 3 dashes for an em-dash. Use 2 dashes for ranges (ex., "it's all
in chapters 12--14"). Three dots ... will be converted to an ellipsis.
Unicode is supported. ☺## Part 2 - {Description}

Use this section to summarize what users will complete in the following steps.

### More formatting

Here's a numbered list:

 #. first item
    a. more
    b. even more
    c. and then some more
 #. second item
 #. third item

Note again how the actual text starts at 4 columns in (4 characters
from the left side). Here's a code sample:

    # Let me re-iterate ...
    for i in 1 .. 10 { do-something(i) }

As you probably guessed, indented 4 spaces. By the way, instead of
indenting the block, you can use delimited blocks, if you like:

~~~
define foobar() {
    print "Welcome to flavor country!";
}
~~~

(which makes copying & pasting easier). You can optionally mark the
delimited block for Pandoc to syntax highlight it:

~~~python
import time
# Quick, count to ten!
for i in range(10):
    # (but not *too* quick)
    time.sleep(0.5)
    print i
~~~

### Step 2 - {Task name}

Now a nested list:

 1. First, get these ingredients:

      * carrots
      * celery
      * lentils

 2. Boil some water.

 3. Dump everything in the pot and follow
    this algorithm:

        find wooden spoon
        uncover pot
        stir
        cover pot
        balance wooden spoon precariously on pot handle
        wait 10 minutes
        goto first step (or shut off burner when done)

    Do not bump wooden spoon or it will fall.

Notice again how text always lines up on 4-space indents (including
that last line which continues item 3 above).

Here's a link to [a website](http://foo.bar), to a [local
doc](local-doc.html), and to a [section heading in the current
doc](#an-h2-header). Here's a footnote [^1].

[^1]: Footnote text goes here.


### Tables

Tables can look like this:

size  material      color
----  ------------  ------------
9     leather       brown
10    hemp canvas   natural
11    glass         transparent

Table: Shoes, their sizes, and what they're made of

(The above is the caption for the table.) Pandoc also supports
multi-line tables:

--------  -----------------------
keyword   text
--------  -----------------------
red       Sunsets, apples, and
          other red or reddish
          things.

green     Leaves, grass, frogs
          and other things it's
          not easy being.
--------  -----------------------


### Other formatting

A horizontal rule follows.

***

Here's a definition list:

apples
  : Good for making applesauce.
  
oranges
  : Citrus!
  
tomatoes
  : There's no "e" in tomatoe.

Again, text is indented 4 spaces. (Put a blank line between each
term/definition pair to spread things out more.)

Here's a "line block":

| Line one
|   Line too
| Line tree


Inline math equations go in like so: $\omega = d\phi / dt$. Display
math should get its own line and be put in in double-dollarsigns:

$$I = \int \rho R^{2} dV$$

And note that you can backslash-escape any punctuation characters
which you wish to be displayed literally, ex.: \`foo\`, \*bar\*, etc.
