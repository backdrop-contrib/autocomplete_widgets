;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;; Autocomplete Widgets for CCK Text and Number fields
;; $Id$
;;
;; Module Author: markus_petrux (http://drupal.org/user/39593)
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

OVERVIEW
========

This module adds 2 autocomplete widgets for CCK fields.

- Autocomplete for allowed values list: This widget can be used for Text and
  Number fields and it takes candidate values from the defined list of Allowed
  values of the fields.

- Autocomplete for existing field data: This widget can be used for Text only
  and it takes candidate values from existing values in the database for that
  field.


REQUIREMENTS
============

- CCK (http://drupal.org/project/cck)
- CCK Text and/or Number modules provided by CCK itself.


INSTALLATION
============

- Copy all contents of this package to your modules directory preserving
  subdirectory structure.

- Goto Administer > Site building > Modules to install this module.

- Create or edit content types and start using the widgets for your Text and/or
  Number fields. :)
