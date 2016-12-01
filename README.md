# PBDB_changelog

Recent enhancements and bugfixes to the [Paleobiology Database](www.paleobiodb.org). To report bugs with the website or data service, please email admin@paleobiodb.org.

## Version 2.00 

#### System changes
+ On 11/30/2016 A new version of the PBDB backend and web interface now hosted by the 

#### GUI changes
+ New global menubar with active reference indicator and Taxon quick search
+ Numerous improvements to formatting and display of forms and output.

#### Added a new user-management system.
+ Authorizers have direct management control of enterers and students.
+ Added password security.
+ Optional addition of ORCID to user record.
+ Advanced user management tools for the database administrators.
+ Clarified database roles as Authorizer, Enter, Student and Guest.
+ Automated sign-up (new account) and role promotion mechanisms.
+ New user settings pages
+ CAPTCHA question-response system to prevent bot signups

#### Main menu changes.
+ Changed the main menu layout which is now contextual based on users database role.
+ New global header menu with additional features and menu choices.

#### Front (aka Splash) page changes.
+ Improved the layout of the front page.
+ Added a link to the changelog.
+ Added database search links to front page.

#### Navigator diversity curve generator changes.
+ Added "save image" function.
+ Added temporal and taxonomic resolution options.
+ Changed layout.

#### Data Service Updates
+ Added a lookup table of geoplate_id and tectonic plate names to the definitions route.
+ Added the ability to include private data in a download request
+ Removed legacy download forms as the modern data service is more powerful, efficient and includes all of the same functionality.

#### Bug Fixes
+ Fixed the paleocoordinate rotations to use a single EarthByte model. It formerly used a mixture of two models, which was creating erroneous results.
+ Wright et al. (2013) Towards community-driven paleogeographic reconstructions: integrating open-access paleogeographic and paleobiology data with plate tectonics. *Biogeosciences* 10:1529-1541
