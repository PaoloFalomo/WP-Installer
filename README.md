# WP-Installer
## Description
A thin wordpress php installer.
## What You Need to know?
* No Php skils are required. Just put this file in your destination folder with a wordpress zip file beside
* ...what you are doing. Seriusly, if you don't know what are you doing please ask first. 

## Prerequisites
* A server
* An FTP connection
* Internet
* A Brain (that works, if you haven't one you can find it [here](http://lmgtfy.com/?q=brain) ) :)
## Features
* He installs wordpress by the zip (needed) side this php file.
* He works great :) now with new graphics too!
* He request you the folder to install (automatically catch it, the default one as '/')

---
### CHANGELOG
#### Version 1.5
New Graphics and Folder support
* Added folder support
* Added graphic (thanks to [codrops](http://tympanus.net/codrops/,"Codrops") for the design inspirations)
* Bug Fixes (we all says this, but most of time is just some stuff that we don't knwo how to say :| )

#### Version 1.0 
(beta... alpha... pre alpha... naah! This was too baad maaaan!)
* ... Seriusly... the code was just [this](http://php.net/manual/it/ziparchive.extractto.php):
```php
  $zip = new ZipArchive;
  if ($zip->open('wordpress.4.1.zip') === TRUE) {
      $zip->extractTo('/');
      $zip->close();
      echo 'ok';
  } else {
      echo 'failed';
  }
  ```
---
## NEXT Features
* Coming next (soon):
* Ajax response of installation
  * Zip get from wordpress.org of the latest wordpress version
  * Choose old version (a select that make you deice
