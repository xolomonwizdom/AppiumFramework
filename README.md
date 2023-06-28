# AppiumFramework
AppiumFramework
Uses Java as a programming language and tests mobile applications using Appium

Dependencies used for the creation of this framework:

Selenium support
Appium 2.0
Commons IO
Jackson
Extent Report
TestNG
Maven
Profiling using Maven
Structure of Framework :

Multilevel Inheritance is used to setup drivers and base actions
Drivers are setup using beforeClass annotations which help in the single implementation of it
Activities can be loaded using beforeMethod and vice-versa
Reports can be generted using the extent report helper class and testNGListeners class
Base class for web-view testing
