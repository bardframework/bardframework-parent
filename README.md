Bard Framework Parent
===================

[![Build Status](https://travis-ci.org/bardframework/bard-parent.svg)](https://travis-ci.org/bardframework/bard-parent)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.bardframework/bard-parent/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.bardframework/bard-parent/)
[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)

The Bard Framework Parent POM provides common settings for all Bard's components.

Documentation
-------------

More information can be found on the [Bard Framework homepage](https://bardframework.org).
Questions related to the usage of Bard Framework Parent should be posted to the [user mailing list][ml].

Where can I get the latest release?
-----------------------------------
You can download it from [download page](https://repo1.maven.org/maven2/org/bardframework/bard-parent).

Alternatively you can pull it from the central Maven repositories:
```xml
<dependency>
    <groupId>org.bardframework</groupId>
    <artifactId>bard-parent</artifactId>
    <version>1</version>
    <type>pom</type>
    <scope>import</scope>
</dependency>
```
or use it as parent pom:
```xml
<parent>
    <groupId>org.bardframework</groupId>
    <artifactId>bard-parent</artifactId>
    <version>1</version>
</parent>
```
Contributing
------------

We accept Pull Requests via GitHub. The [developer mailing list][ml] is the main channel of communication for contributors.
There are some guidelines which will make applying PRs easier for us:
+ No spaces! Please use tabs for indentation.
+ Respect the code style.
+ Create minimal diffs - disable on save actions like reformat source code or organize imports. If you feel the source code should be reformatted create a separate PR for this change.

You can learn more about contributing via GitHub in our [contribution guidelines](CONTRIBUTING.md).

License
-------
This code is under the [Apache Licence v2](https://www.apache.org/licenses/LICENSE-2.0).

Donations
---------
You like Bard Framework? Then [donate](https://bardframework.org/donate) to support the development.

Additional Resources
--------------------
+ [Bard Framework Homepage](https://bardframework.org)
+ [Bard Framework Parent Issue Tracker](https://github.com/bardframework/bard-parent/issues)
+ [Bard Framework Twitter Account](https://twitter.com/BardFramework)

[ml]:https://bardframework.org/mail-lists.html
