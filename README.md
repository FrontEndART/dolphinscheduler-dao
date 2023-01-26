# dolphinscheduler-dao

The dao module extracted from the full DolphinScheduler project for evaluation purposes.

To be able to compile, one needs to install the common jar located in the lib folder with the following command:
```
mvn install:install-file -Dfile=lib/dolphinscheduler-common-2.0.5.jar -DgroupId=org.apache.dolphinscheduler -DartifactId=dolphinscheduler-common -Dversion=2.0.5 -Dpackaging=jar -DgeneratePom=true

mvn install:install-file -Dfile=lib/dolphinscheduler-spi-2.0.5.jar -DgroupId=org.apache.dolphinscheduler -DartifactId=dolphinscheduler-spi -Dversion=2.0.5 -Dpackaging=jar -DgeneratePom=true
```
