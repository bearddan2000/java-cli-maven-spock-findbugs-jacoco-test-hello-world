# java-cli-maven-spock-findbugs-jacoco-test-hello-world

## Description
Analyze source code for potential bugs.
A POC for maven app using spock framework.
Jacoco plugin used for reporting.

## Tech stack
- java
- groovy
- maven
	- findbugs
  - Jacoco
  - spock

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://www.petrikainulainen.net/programming/testing/writing-unit-tests-with-spock-framework-creating-a-maven-project/)
- [Code build model](https://github.com/christoph-frick/spock-test-logging)
