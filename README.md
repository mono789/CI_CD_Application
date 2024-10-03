[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=mono789_CI_CD_Application&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=mono789_CI_CD_Application)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=mono789_CI_CD_Application&metric=bugs)](https://sonarcloud.io/summary/new_code?id=mono789_CI_CD_Application)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=mono789_CI_CD_Application&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=mono789_CI_CD_Application)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=mono789_CI_CD_Application&metric=coverage)](https://sonarcloud.io/summary/new_code?id=mono789_CI_CD_Application)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=mono789_CI_CD_Application&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=mono789_CI_CD_Application)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=mono789_CI_CD_Application&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=mono789_CI_CD_Application)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=mono789_CI_CD_Application&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=mono789_CI_CD_Application)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=mono789_CI_CD_Application&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=mono789_CI_CD_Application)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=mono789_CI_CD_Application&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=mono789_CI_CD_Application)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=mono789_CI_CD_Application&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=mono789_CI_CD_Application)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=mono789_CI_CD_Application&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=mono789_CI_CD_Application)

Implementation of a Simple App with the next operations:
* Get random nations
* Get random currencies
* Get random Aircraft
* Get application version
* health check
Including integration with GitHub Actions, Sonarqube (SonarCloud), Coveralls and
Snyk
### Folders Structure
In the folder `src` is located the main code of the app
In the folder `test` is located the unit tests
### How to install it
Execute:
```shell
$ mvnw spring-boot:run
```
to download the node dependencies
### How to test it
Execute:
```shell
$ mvnw clean install
```
### How to get coverage test
Execute:
```shell
$ mvwn -B package -DskipTests --file pom.xml
```
