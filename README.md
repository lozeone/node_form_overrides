This is a project on drupal.org now https://www.drupal.org/project/node_form_overrides
You should download it from there, not here. This one isn't the latest.

# node_form_overrides
Drupal 8 module to overrides the default node create, update, and delete form titles and button labels

Often times when building a Drupal site I find myself using hook_form_alter to change the page titles and button labels based on certian conditions for that content type. This module aims to make that eaiser by putting some of these common overides in the config of the content type.

Currently this only supports node forms, but I may expand it to support other entities in the future.

Suggestions and patches welcome.

**What is the difference between this module and the contrib override_node_options module?** (https://www.drupal.org/project/override_node_options)
They do different things. This module overrides the title and button text, while override_node_options overrides some of the authoring and pluplishing options fields.

What it does
------------
- Adds settings to node type forms for overriding the page titles and button labels of node edit/update forms and node delete confirmation form.
- Supports tokens

Installation & Configuration
------------

 * Install it like any other Druapl module. Place it in your modules folder and enable it.

 * Once installed, go to a node type edit form and set the values you want to override.


