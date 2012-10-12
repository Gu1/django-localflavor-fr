=====================
django_localflavor_fr
=====================

Country-specific Django helpers for France.

What's in the France localflavor?
=================================

* FRPhoneNumberField: A form field that validates input as a French local phone
  number. The correct format is 0X XX XX XX XX. 0X.XX.XX.XX.XX and 0XXXXXXXXX
  validate but are corrected to 0X XX XX XX XX.

* FRZipCodeField: A form field that validates input as a French zip code. Valid
  codes consist of five digits.

* FRDepartmentSelect: A ``Select`` widget that uses a list of French departments
  as its choices.

See the source code for full details.

About localflavors
==================

Django's "localflavor" packages offer additional functionality for particular
countries or cultures.

For example, these might include form fields for your country's postal codes,
phone number formats or government ID numbers.

This code used to live in Django proper -- in django.contrib.localflavor -- but
was separated into standalone packages in Django 1.5 to keep the framework's
core clean.

For a full list of available localflavors, see https://github.com/django/
