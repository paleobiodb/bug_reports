# The PBDB Project Changelog

Recent enhancements to the [Paleobiology Database](www.paleobiodb.org) including the core Web Application, the graphical Navigator and the supporting Data Service/Public API. To report bugs with the PBDB website or data service, please email admin@paleobiodb.org.

## Version 2.1
4 May 2017

### Navigator changes
+ Updated all API calls made by Navigator to use version 1.2 of the data service
+ Bug fix: the searchable list of people is no longer truncated halfway through the alphabet
#### New feature: advanced diversity curve plotter 
+ Rangethrough counts, including/excluding singletons
+ Extinction and origination rates (boundary-crossing method)
#### Added more information to auto-completed search results
+ Taxa: synonymies, accepted names, and immediate parents
+ Stratigraphic units: location by country
+ Time intervals: beginning and ending ages
+ Contributors: academic affiliation

### Data service changes
+ Incremented version to 1.2 (v2).
+ Added new operation combined/auto for better auto-completion
+ When returning paleocoordinates, an explanatory message has been added in cases where the coordinates are not computable using the selected model
+ Full documentation at https://paleobiodb.org/data1.2/changelog_doc.html

## Version 2.0
11/30/2016

#### System changes
+ A new version of the PBDB backend and web interface was launched. Now called Version 2, this version is supported by a true web application framework in conjuction with Wing, a modern web services toolkit. The result is greater efficiency, security and modularity of the system as a whole together with access to a host of advanced built-in features.

#### GUI changes
+ New global menubar with active reference indicator and Taxon quick search
+ Numerous improvements to formatting and display of forms and output.

#### Added a new user-management system
+ Authorizers have direct management control of enterers and students.
+ Added password security.
+ Optional addition of ORCID to user record.
+ Advanced user management tools for the database administrators.
+ Clarified database roles as Authorizer, Enter, Student and Guest.
+ Automated sign-up (new account) and role promotion mechanisms.
+ New user settings pages
+ CAPTCHA question-response system to prevent bot signups

#### Main menu changes
+ Changed the main menu layout which is now contextual based on users database role.
+ New global header menu with additional features and menu choices.

#### Front (aka Splash) page changes
+ Improved the layout of the front page.
+ Added a link to the changelog.
+ Added database search links to front page.

#### Navigator diversity curve generator changes
+ Added "save image" function.
+ Added temporal and taxonomic resolution options.
+ Changed layout.

#### Data Service Updates
+ Added a lookup table of geoplate_id and tectonic plate names to the definitions route.
+ Added the ability to include private data in a download request
+ Removed legacy download forms as the modern data service is more powerful, efficient and includes all of the same functionality.

#### Minor Bug Fixes
+ Fixed the paleocoordinate rotations to use a single EarthByte model. It formerly used a mixture of two models, which was creating erroneous results.
+ Wright et al. (2013) Towards community-driven paleogeographic reconstructions: integrating open-access paleogeographic and paleobiology data with plate tectonics. *Biogeosciences* 10:1529-1541
