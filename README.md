Webform
=======

Webform is the module for making forms and surveys in Backdrop.

This module adds a webform content type to your Backdrop site.
A webform can be a questionnaire, contact or request form. These can be used
by visitor to make contact or to enable a more complex survey than polls
provide. Submissions from a webform are saved in a database table and
can optionally be mailed to e-mail addresses upon submission.

Results can be exported into Excel or other spreadsheet applications. Webform
also provides some basic statistical review and has an extensive API for
expanding its features.

Installation
------------

1. Install this module using the official Backdrop CMS instructions at
   <https://backdropcms.org/guide/modules>.
2. Login as an administrator. Enable the module in the "Administer" > "Modules"
3. (Optional) Edit the settings under "Administer" > "Configuration" >
   "Content authoring" > "Webform settings"
4. Create a webform node at node/add/webform.

Support
-------

Please use the issue queue for filing bugs with this module at
<https://github.com/backdrop-contrib/webform/issues>

Webform is a popular non-utility contrib module. It is a large, rich module
used by hundreds of thousands of sites. If you are using Webform, please give
back to our community. We need your help triaging issues, answering support
requests, writing patches, reviewing/testing patches.

Please always use the project issue tracker to report bugs, request support
and/or request new features. The maintainers neither read the forums nor reply
to direct e-mails for support.

Open one issue for each problem/request; don't bundle several issues into one
submission. Please search the queue and read the handbook pages to avoid
duplicate issues.

Background
----------

Backdrop Webform is based on the Webform module for Drupal 7--starting at
version 7.x-4.4. For additional examples of Webform configuration, the
existing documentation and videos the Drupal 7 verison will likely be useful
for the Backdrop version as well. Note that Webform for Drupal 8 continues the
'Webform' name and serves the same general purpose, but is a different product
with different features and configuration.

Versions
--------

In Oct 2017 we bumped the version number from 1.x-1.6.2 to 1.x-4.16.0 to 
syncronize with the version numbers for the Drupal version of this module. 
Despite appearances this was a minor update and users should be able to upgrade
from 1.6.2 to the most recent release without any problem. There is no reason 
for anyone to use the 1.x-1.6.2 today. We recommend that you always start with 
and upgrade to the most recent release. 

Future
------

The Backdrop version of Webform will continue to track Webform 7.x-4.x as long as 
it gets updates. There are no plans to track Webform for Drupal 8, 9 or above, 
since the codebase is quite different. However we will consider merging requests 
that incorporate new features from the Drupal 8.x-5.x/6.x branches of Webform as 
they are submitted. 

If you would like to see a new feature in Webform, open an issue in the issue
queue for discussion. 

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

Maintainers
-----------

- quicksketch <https://github.com/quicksketch>
- herbdool <https://github.com/herbdool>

Credits
-------

Ported to Backdrop from Drupal 7 by biolithic <https://github.com/biolithic>. 
The Drupal 7 version originally written and maintained by a large number of
contributors, including:

- quicksketch <https://www.drupal.org/u/quicksketch>
- fenstrat <https://www.drupal.org/u/fenstrat>
- danchadwick <https://www.drupal.org/u/danchadwick>
- torotil <https://www.drupal.org/u/torotil>

Special thanks
--------------

This Backdrop module is supported by the hosted survey-solution website
Webform.com and Lullabot.
