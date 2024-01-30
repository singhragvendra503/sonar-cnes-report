# Sonar CNES Report
[![Java CI](https://github.com/cnescatlab/sonar-cnes-report/actions/workflows/java-continuous-integration.yml/badge.svg)](https://github.com/cnescatlab/sonar-cnes-report/actions/workflows/java-continuous-integration.yml)
[![SonarQube Quality Gate](https://sonarcloud.io/api/project_badges/measure?project=fr.cnes.sonar%3Acnesreport&metric=alert_status)](https://sonarcloud.io/dashboard?id=fr.cnes.sonar%3Acnesreport)
[![SonarQube Bugs](https://sonarcloud.io/api/project_badges/measure?project=fr.cnes.sonar%3Acnesreport&metric=bugs)](https://sonarcloud.io/project/issues?id=fr.cnes.sonar%3Acnesreport&resolved=false&types=BUG)
[![SonarQube Coverage](https://sonarcloud.io/api/project_badges/measure?project=fr.cnes.sonar%3Acnesreport&metric=coverage)](https://sonarcloud.io/component_measures?id=fr.cnes.sonar%3Acnesreport&metric=Coverage)
[![SonarQube Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=fr.cnes.sonar%3Acnesreport&metric=sqale_index)](https://sonarcloud.io/component_measures?id=fr.cnes.sonar%3Acnesreport&metric=Maintainability)

I have update plugin for 10.0.x and that package you find under `target/sonar-cnes-report-4.2.1.jar`
SonarQube is an open platform to manage code quality. This program can export code analysis from a SonarQube server as a docx, xlsx, csv, markdown,  and text files.


This tool can be used in standalone as a JAR executable (with the command line) or as a Sonarqube plugin.

### Quickstart
- Setup a SonarQube instance.
- Run an analysis with sonar-scanner, maven, gradle, msbuild, etc.
- Execute cnesreport:
   - In standalone, thanks to command line
   - Give your jar read permissions for others (chmod o+r `sonar-cnes-report-4.2.1.jar`)
   - In plugin mode, copy jar in `/opt/sonarqube/extensions/plugins`, restart sonarqube, then click on "More" > "CNES Report".

