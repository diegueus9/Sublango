django.db.models
================

Models
------

This package provides this snippets:

+-------------------+-----------------------------------------------+
| Trigger           | Snippet for                                   |
+===================+===============================================+
| Model             | A class than inherits from models.Model       |
+-------------------+-----------------------------------------------+
| _get_absolute_url | The method for get_absolute_url in each model |
+-------------------+-----------------------------------------------+
| _unicode          | The method __unicode__                        |
+-------------------+-----------------------------------------------+
| Meta              | The class Meta inside the model               |
+-------------------+-----------------------------------------------+

Fields
------

There is a snippet for each field triggered by the name of field:

* BigIntegerField
* BooleanField
* CharField
* CommaSeparatedIntegerField
* DateField
* DateTimeField
* DecimalField
* EmailField
* FileField
* FloatField
* ForeignKey
* ImageField
* IntegerField
* IPAddressField
* Manager
* ManyToManyField
* Model
* NullBooleanField
* OneToOneField
* PositiveIntegerField
* PositiveSmallIntegerField
* SlugField
* SmallIntegerField
* TextField
* TimeField
* URLField

In addition, you can use `ManyToManyField_through` for generate a snippet for the ManyToManyField and the class used for the option `through`

Field Options
-------------

Support for the next field options and ther values triggered by their own name:

* null
* blank
* choices
* db_column
* db_index
* db_tablespace
* default
* editable
* error_messages
* help_text
* primary_key
* unique
* unique_for_date
* verbose_name
* validators
* max_length
* auto_now
* auto_now_add
* max_digits
* decimal_places
* height_field
* width_field
* limit_choices_to
* related_name
* to_field
* on_delete
* symmetrical
* through
* parent_link