# TDD Training application

The TDD training application is based on the Weinberg-Myers triangle program [example](http://www.testdesigners.com/testingstyles/triangleexample.html).

## Required

The following application must be install for running the TDD Training application

* jkd 1.6+
* [maven 3](http://maven.apache.org/)

## First run

Before starting the application or running the test the following command must be run

`mvn clean install`

## Running the application

The application can be run with the following command

`sh startJettyDebug.sh`

## Running tests

The test that are already in the application available can be run with the following command

`mvn verify`

This will run thucydides junit and thucydides jbehave tests.