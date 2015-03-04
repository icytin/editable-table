

editable-table
=================

This tiny (3KB, < 120 lines) jQuery plugin turns any table into an editable spreadsheet. Here are the key features:

* No magic - works on a normal HTML table (so you can plug it in into any web
table)
* Supports validation and change events (so you can warn about invalid input or
prevent invalid changes)
* Uses standard DOM focus for selection (so does not interrupt scrolling or
tabbing outside the table)
* Native copy/paste support
* Does not force any styling (so you can style it any way you want, using normal
CSS)
* Works well with Bootstrap
* Depends only on jQuery

Extended Features
-----------

* Added the possibility to prevent edit of certain columns. For example if second and third column not should be editable, you simply initializes the table as:

  $('#table').editableTableWidget({ editor: $('<input>'), preventColumns: [ 2, 3 ] });

Thanks Gojko Adzic for a nice and light weighted library!

Basic Usage
-----------

See http://mindmup.github.com/editable-table/

Dependencies
------------
* jQuery http://jquery.com/
