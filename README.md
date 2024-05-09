# Visualpathit VProfile Webapp

## Overview

This is the Maven project configuration for the Visualpathit VProfile Webapp. It defines the project structure, dependencies, and build configuration for the web application.

## Project Information

- **Group ID:** com.visualpathit
- **Artifact ID:** vprofile
- **Packaging:** WAR
- **Version:** v2
- **Project URL:** [http://maven.apache.org](http://maven.apache.org)

## Dependencies

This project relies on the following dependencies:

- **Spring Framework:**
  - spring-web: ${spring.version}
  - spring-webmvc: ${spring.version}
  - spring-security-web: ${spring-security.version}
  - spring-security-config: ${spring-security.version}
  - spring-data-jpa: ${spring-data-jpa.version}

- **Hibernate:**
  - hibernate-validator: ${hibernate-validator.version}
  - hibernate-entitymanager: ${hibernate.version}

- **Database Connectivity:**
  - mysql-connector-java: ${mysql-connector.version}
  - commons-dbcp: ${commons-dbcp.version}

- **Web Components:**
  - jstl: ${jstl.version}
  - javax.servlet-api: 3.1.0 (provided)

- **Testing:**
  - junit: ${junit.version} (scope: test)
  - mockito-core: 1.9.5 (scope: test)
  - spring-test: 3.2.3.RELEASE (scope: test)
  - hamcrest-all: 1.3 (scope: test)

- **Logging:**
  - logback-classic: ${logback.version}

- **Other Dependencies:**
  - commons-fileupload: 1.3.1
  - spymemcached: 2.12.3
  - commons-io: 2.4
  - spring-rabbit: 1.7.1.RELEASE
  - amqp-client: 4.0.2
  - elasticsearch: 5.6.4
  - transport: 5.6.4
  - gson: 2.8.2

## Build Configuration

- **Jetty Maven Plugin:** Used for running the web application during development.
- **Jacoco Maven Plugin:** Used for code coverage reporting.
