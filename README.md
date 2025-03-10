Treebranches
============

This is a system that makes it easy to view large family trees.

When a user types in any two members of the family tree, they'll be shown a drawing of
only the few tree branches that connect the two members.

Treebranches consists of a single file that runs within any web browser. It does not
require a server.

Treebranches is wriiten in HTML, CSS, and JavaScript. The input uses the JSON format and
the output uses the SVG graphics format.


## Purpose of the Project

Most family trees are difficult to view because the bottom levels usually have hundreds
of people at the same level. A system for viewing partial branches makes things easier.

This system still contains all of the normal family tree's data, it's just that it will
only display a few branches at a time.


## How It Works

The people's names are collected from the input form using JavaScript.

The tree branches will be generated using the SVG graphics format.

Since the SVG format is based on XML, it can be modified like a HTML document.

The family tree's raw data will be stored within the page using the JSON format.

You can view the project's source code by opening this page on a computer's browser and
then right-clicking anywhere on the page and selecting "View page source".

