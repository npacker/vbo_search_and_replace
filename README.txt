Views Bulk Operations (VBO) Search And Replace
==============================================

This module exposes a new action to Views Bulk Operations that allows one to
perform Search and Replaces on the entity fields and properties of selected row
items. Currently only supports Text fields.

Installation
------------

 - Download module and install as any other drupal module
 - Add a views bulk operations field to a view (or edit an existing one)
 - Select "Search and replace on Entity values" from the "Selected bulk
   operations" fieldset. And configure (settings are described below)

Settings
--------

There are few settings for the search and replace bulk operation:

 - "Display Checkboxes Inline": Enable this to add some css to the page to
   display the checkboxes inline as columns.
 - "Display Values": Specify which fields/properties are able to be search and
   replaced on.
