# Devel Form Debug
<!--
The first paragraph of this file should be kept short as it will be used as the
project summary on BackdropCMS.org. Aim for about 240 characters (three lines at
80 characters each).

All lines in this file should be no more than 80 characters long for legibility,
unless including a URL or example that requires the line to not wrap.
|<- - - - - - - This line is exactly 80 characters for reference - - - - - - ->|

Detail in READMEs should be limited to the minimum required for installation and
getting started. More detailed documentation should be moved to a GitHub wiki
page; for example: https://github.com/backdrop-contrib/setup/wiki/Documentation.
-->
Devel Form Debug provides a contextual link for all forms that enables you to
easily find out the form_id, the form variables ($form) and get a quick
template for creating a hook_form_FORM_ID_alter() function.

## Requirements

This module requires the following modules:
- Devel
- Search Krumo

Using this module requires the following permissions:
- Use contextual links (Core - Contextual Links)
- Access developer information (Devel)
- Access devel form debug contextual links

## Installation
<!--
List the steps needed to install and configure the module. Add/remove steps as
necessary.
-->
- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.

## Usage
- Hover over any form and you will see a contextual link available.
- Expand the link and you will see the form ID.
- Click on the link and you will see a modal window with copyable form id and
hook_form_FORM_ID_alter() function template.
- Clicking on the "Print form variables" button and you can  print out the form
variables using the Devel Krumo variable explorer.

## Issues
<!--
Link to the repo's issue queue.
-->
Bugs and Feature Requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/devel_form_debug/issues.

## Current Maintainers
<!--
List the current maintainer(s) of the module, and note if this module needs
new/additional maintainers.
-->
- [Martin Price](https://github.com/yorkshire-pudding) - [System Horizons Ltd](https://www.systemhorizons.co.uk)
- Collaboration welcome!

## Credits
<!--
Give credit where credit's due.
If this is a Drupal port, state who ported it, and who wrote the original Drupal
module. If this module is based on another project, or uses third-party
libraries, list them here. You can also mention any organisations/companies who
sponsored the module's development.
-->
- Ported to Backdrop CMS by - [Martin Price](https://github.com/yorkshire-pudding) - [System Horizons Ltd](https://www.systemhorizons.co.uk).
- Port to Backdrop CMS and ongoing development sponsored by [System Horizons Ltd](https://www.systemhorizons.co.uk).
- Created for and maintained on [Drupal](https://www.drupal.org/project/devel_form_debug) by [Tim Kamanin](https://github.com/timonweb)
- Drupal development sponsored by [TimonWeb](https://timonweb.com/)

## License
<!--
Mention what license this module is released under, and where people can find
it.
-->

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
