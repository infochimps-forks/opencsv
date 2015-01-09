# Opencsv

## Deployment

You'll need your settings.xml set up with the credentials necessary to
deploy to Infochimps' parent repository. See instructions for setting
this up in https://github.com/infochimps-platform/parent-pom

This package must be built with an older version of Java. I used Sun's
jdk1.5.0_22 and Maven 2.2.0.

If you set things up correctly, deploying to Infochimps' repositories
should just be a matter of running `mvn deploy` in this directory.
