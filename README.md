Autocomplete Widgets
======================

This module adds 4 autocomplete widgets.

- Autocomplete for allowed values list: This widget can be used for List fields
  and it takes candidate values from the defined list of Allowed values of the
  fields.

- Autocomplete for existing field data: This widget can be used for Text only
  and it takes candidate values from existing values in the database for that
  field.

- Autocomplete for suggested values: This widget can be used for Text only
  and it takes candidate values from a user-defined list of Suggested values.

- Autocomplete for existing field data and some node titles: This widget works
  just like the "existing field data" widget above except it will also suggest
  node titles for nodes of a specific content type(s).

- Autocomplete for some node titles: This widget can be used to suggest
  node titles for nodes of a specific content type(s).

All these widgets allow you to choose the method used to match values: either
 'Starts with' or 'Contains'.

When the Internationalization module [1] is enabled, the 'Autocomplete for
existing field data' widget also provides an option to filter values by the
language assigned to their corresponding nodes. This option allows you to
provide a different set of allowed values per language.

[1] http://backdropcms.org/project/i18n


Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.

- Visit the configuration page under Administration > Structure > Types
  (admin/structure/types) and create or configure fields on content types
  to start using the widgets for your Text and/or List fields.

Documentation
-------------

Additional documentation is located in the Wiki:
https://github.com/backdrop-contrib/autocomplete_widgets/wiki/Documentation.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/autocomplete_widgets/issues.

Current Maintainers
-------------------

- Jen Lampton (https://github.com/jenlampton).
- Seeking additional maintainers.

Credits
-------

- Ported to Backdrop CMS by [Jen Lampton](https://github.com/jenlampton).
- Maintined for Drupal by [Alexander Ross](https://www.drupal.org/u/bleen).
- Originally written for Drupal by [Marc Ferran](https://www.drupal.org/u/markus_petrux).

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

