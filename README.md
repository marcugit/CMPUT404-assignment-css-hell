Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

License/Copyright
=================

Textual content is copyright Abram Hindle and Ana Marcu (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.


NOTES:
File structure:
- there are two folders: part one and part 2, for each part there is another folder 'screenshots' within part 1 or part 2, for the screenshots
For the Gutenberg project, the html pages were changed as follows:
- the following line was added before the <body> tag : <link href="gutenberg.css" rel="stylesheet">
- the h1 header tag was modified with : class="caption"
- h2 headers before the 'contents' were modified with : class="nocolor"
- the contents (at the top) with chapter links were modified with: class = "toc" for all of them


- for part 2, some css elements are specific to firefox (the complementary safari syntax is commented out) - the file is now set for firefox

