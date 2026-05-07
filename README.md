# Basis Maven Buildtools #

This project publishes checkstyle and PMD rules to Maven, so that they
can be reused in multiple projects using the maven-checkstyle-plugin
and maven-pmd-plugin.

- [Generate a user token](https://central.sonatype.com/usertoken)
- Add that token to your Maven settings.xml

```
mvn release:prepare

mvn releaes:perform
#  --OR--
 mvn release:perform -Darguments=-Dgpg.passphrase=MY_PASSPHRASE
```
