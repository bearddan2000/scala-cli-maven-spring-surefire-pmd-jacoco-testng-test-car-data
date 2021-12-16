# scala-cli-maven-spring-surefire-pmd-jacoco-testng-test-car-data

## Description
Analyze source code for bugs.
A POC for spring app using testng
framework with jacoco and surefire
plugins.

## Tech stack
- scala
- maven
	- pmd
  - spring
  - testng
  - jacoco
  - surefire

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- jacoco report under bin/target/site/jacoco

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept] (https://github.com/eugenp/tutorials/tree/master/testing-modules/testng)
- [Jacoco config] (https://www.baeldung.com/jacoco)
