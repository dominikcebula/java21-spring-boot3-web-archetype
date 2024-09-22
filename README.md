# Java 21 Spring Boot 3 Web Archetype

## Intro

This repository contains a Maven Archetype that can be used to generate a Java 21 Spring Boot 3 Web project.

Included example code will create a Spring Boot 3 Web Application:
```
  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::                (v3.0.2)

...
2023-02-07T22:06:26.555+01:00  INFO 9308 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 8080 (http)
2023-02-07T22:06:26.587+01:00  INFO 9308 --- [           main] com.dominikcebula.Application            : Started Application in 4.083 seconds (process running for 4.816)
```

Generated application will include:

* TBD

## Usage

Invoke command:
```
$ mvn archetype:generate -DarchetypeGroupId=com.dominikcebula.archetypes -DarchetypeArtifactId=java21-spring-boot3-web-archetype
```

Maven Archetype will ask about `groupId`, `artifactId`, `version`, `package name` and will generate a project skeleton.

## Generated project

Having the project generated, invoke:
```
$ mvn clean install
```

Executable jar with all dependencies will be generated under `target` folder.

You can execute generated `jar` using command:
```
$ java -jar target/generated-output-1.0-SNAPSHOT.jar
```

Example endpoint can be used with following request:
TBD
