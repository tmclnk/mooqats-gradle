#mooqats-gradle
This is a skeleton project to help demonstrate gradle, grails, and a subset of grails plugins.

## Getting Started
Make sure you have JAVA_HOME set to something recent.  From the project you
should be able to run the application using the gradle wrapper, which is
included in distribution.

> ./gradlew tasks 

For Grails development tasks, you will need to have Grails installed.

## Grails 3.0.1
Support for the grails wrapper (grailsw) was dropped in 3.0.0RC3, so you will
need to have a copy of it installed if you wish to perform grails commands as
indicated in the documentation.

This project uses Grails 3.0.1.

Please vote for [GRAILS-12098](https://jira.grails.org/browse/GRAILS-12092) in
the meantime so that future Grails releases will include support for grailsw.

## Eclipse
This project does not require any Grails specific tooling (ala GGTS), but will
work best if you have IDE support for Gradle.  Search the Eclipse Marketplace
for "Gradle" and install a recent version of "Gradle IDE".

You may wish to configure Gradle EnIDE with the "use wrapper if `gradlew[.bat]`
is present" option.  It is listed in Preferences > Gradle EnIDE.

Because this project is based on Grails 3.0, it requires Groovy 2.4.  You can
use the update site.  For Eclipse 4.4 (Luna) you can use the update site at
[http://dist.springsource.org/snapshot/GRECLIPSE/e4.4/](http://dist.springsource.org/snapshot/GRECLIPSE/e4.4/).



## IntelliJ IDEA
IntelliJ provides native Gradle support, so no additional plugins should be
required.
