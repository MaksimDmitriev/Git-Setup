VCS Setup
=========

This repository contains scripts that 
  * permorm Git and Mercurial aliases initialization,
  * copy global Git and Mercurial ignore files to the user's home directory,
  * set Git and Mercurial user name and e-mail address,
  * retreive the latest Android.gitignore from GitHub.

#### How to use

Clone and run the `install` excutable file.

#### TODO
* gradle/wrapper/gradle-wrapper.properties should probably be excluded.
* Android Studio wrapper ignore file
* Check if *.iml should be in the wrapper ignore file. Perhaps it should be in Android.hgignore. It depends on the logic of subrepos
* User name and e-mail should be variables.
