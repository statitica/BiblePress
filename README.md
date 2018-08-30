# BiblePress
Files and roadmap for the RPi based BiblePress project

## Roadmap:
* Rebase project on Raspian Lite, for continuity of support
  * Test and finalise software choices
* nginx vs lighttd for captive portal
  * mimetypes to add (apk, dmg, zip)
* Create custom image with software already installed
  * As much as possible, make this a zero internet installation.
* Create script in bash, to automate any parts which are not predictable
  * where systemd fails to give logical names to wifi
* Add script as a cronjob in custom image
* Test
* Condense image as much as possible
* Documentation
 * Installation
 * Use
 * Maintenance
 * Re-install
* Handover to RM

Done.

## Scope:
* Create a version of the BibePress image which automates all of the setup, requiring the user to only flash the image to an SD card.
 * We get to choose whether the user will need to "create" the first wordpress sign in, or if that will also be automated to a standard username and password
* Allow for variations in hardware on initial boot 
* Simple documentation on installation procedures, for untrained persons to be able to follow.
* Present second prototype to RM board, with costings on variations.
* No budget, as hardware was already purchased.
