# gemsNgelly


# Info

This is the start of a ./Gradle project using Wrapper for CI slickness with a couple additional tools that will be added once everything is flushed out and working.
An open welcome to vauled community improvements

# Versions

Version 1.0 - March 16, 2016


# Project Layout

    Gradle Root
    +--- Project ':root'
    +---  ':src'
    +---  ':main'
    +---  ':com'
    +---  ':project'
    +--- ...

# Overview

    1. Project Structure is Gradle as it is


# Quick Start
Pre-requisite: install brew
brew install gradle to run directly from the .zip distribution on the command line; this will install 
Gradle 2.12 Released

# Upgrading Gradle
Switch your build to use Gradle 2.12 quickly by updating your wrapper properties:

./gradlew wrapper --gradle-version=2.12

Alertnatively
Without requiring a Java IDE, download Gradle 2.12, configure your 
GRADLE_HOME environment variable, add %GRADLE_HOME%\bin to your PATH and run $gradle -v.

# Implemented Features
<table>
  <tr>
    <th>Feature</th>
    <th>Description</th>
  </tr>
  <tr>
    <th>JUnit based</th>
    <td>For use with JUnit 4.12. 
    This dependency is configured by the Gradle build script.</td>
  </tr>
  <tr>
    <th>Jmeter</th>
    <td>For 2.13 or higher.</td>
  </tr>
  <tr>
    <th>Logging and Reporting</th>
    <td>Use plugins within Gradle to be as custom as you wish</td>
  </tr>
  <tr>
    <th>Run Options</th>
    <td>Some options for running the tests: via the Gradle GUI, via your IDE Gradle
    plugin, or via Gradle command line.</td>
  </tr>
</table>

#Features
<table>
  <tr>
    <th>Feature</th>
    <th>Description</th>
  </tr>
  <tr>
    <th>Gradle Dependencies</th> <td> Full support of POM from repositories and replacement of previous.By using 
    .replacedBy as in module("com.foo.fooinspect:foo-fooinspect).replacedBy("com.google.guava:guava")
     List out dependencies $gradle dependencies 
  </tr>
  <tr>
    <th>Gradle Wrapper</th> <td>task wrapper(type: Wrapper)</td>
  </tr>
  <tr>
    <th>Jar executable option</th> <td> gradle jar</td> 
  </tr>
</table>

# Configuration And Setup

#### 
Steps to be added soon:
 
    1. .
    2. .
    3. .

#### IntelliJ-IDEA
Required Gradle functionality is built into IntelliJ-IDEA 15CTE.  
IntelliJ15(IDEA) can be more difficult to configure correctly.

#### Notes
To be added.

# FAQ
To be added.
