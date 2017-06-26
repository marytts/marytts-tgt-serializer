[comment]: <> ([![Build Status](https://travis-ci.org/marytts/marytts-tgt-serializer.svg?branch=master)](https://travis-ci.org/marytts/marytts-tgt-serializer))
[comment]: <> ([![Bintray](https://img.shields.io/bintray/v/marytts/maven/marytts-tgt-serializer.svg)](https://bintray.com/marytts/maven/marytts-tgt-serializer))
[![License: LGPL v3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](http://www.gnu.org/licenses/lgpl-3.0)

# MaryTTS TextGrid serializer

The MaryTTS TextGrid serializer is an artefact compatible with MaryTTS (>= 6.x) to export/import TextGrid file into the MaryTTS system. It is using JTGT as a TextGrid backend conversion: https://github.com/hbuschme/TextGridTools

## Adding the MaryTTS TextGrid serializer to your dependencies

To declare a depency on the MaryTTS TextGrid serializer you can do it:

- in the `pom.xml` for Maven:
```xml
<repositories>
  <repository>
    <url>https://jcenter.bintray.com</url>
  </repository>
</repositories>

<dependencies>
  <dependency>
    <groupId>de.dfki.marytts</groupId>
    <artifactId>marytts-tgt-serializer</artifactId>
    <version>0.5</version>
  </dependency>
</dependencies>
```
- in the `build.gradle` for Gradle
```groovy
repositories {
  jcenter()
}

dependencies {
  compile group: 'de.dfki.marytts', name:'marytts-tgt-serializer', version: '0.5'
}
```
