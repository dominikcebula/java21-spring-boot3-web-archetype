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
 :: Spring Boot ::                (v3.2.2)

2024-09-22T16:20:15.032+02:00  INFO 24930 --- [           main] com.dom.web.Application                  : Starting Application using Java 21.0.4 with PID 24930 (/home/dominik/Development/edu/target/classes started by dominik in /home/dominik/Development/edu)
2024-09-22T16:20:15.034+02:00  INFO 24930 --- [           main] com.dom.web.Application                  : No active profile set, falling back to 1 default profile: "default"
2024-09-22T16:20:15.466+02:00  INFO 24930 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port 8080 (http)
2024-09-22T16:20:15.473+02:00  INFO 24930 --- [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2024-09-22T16:20:15.473+02:00  INFO 24930 --- [           main] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.18]
2024-09-22T16:20:15.498+02:00  INFO 24930 --- [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2024-09-22T16:20:15.499+02:00  INFO 24930 --- [           main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 443 ms
2024-09-22T16:20:15.677+02:00  INFO 24930 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port 8080 (http) with context path ''
2024-09-22T16:20:15.683+02:00  INFO 24930 --- [           main] com.dom.web.Application                  : Started Application in 0.816 seconds (process running for 0.965)
2024-09-22T16:20:21.426+02:00  INFO 24930 --- [nio-8080-exec-1] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring DispatcherServlet 'dispatcherServlet'
2024-09-22T16:20:21.426+02:00  INFO 24930 --- [nio-8080-exec-1] o.s.web.servlet.DispatcherServlet        : Initializing Servlet 'dispatcherServlet'
2024-09-22T16:20:21.427+02:00  INFO 24930 --- [nio-8080-exec-1] o.s.web.servlet.DispatcherServlet        : Completed initialization in 1 ms
```

Generated application will include:

* Home Controller
* Home View using Thymeleaf
* CSS as Static Web Resource
* Dependencies to:
    * Spring Boot Web
    * Thymeleaf
    * HtmlUnit

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

Having application started visit http://localhost:8080/ to see application homepage.

# Author

Dominik Cebula

* https://dominikcebula.com/
* https://blog.dominikcebula.com/
* https://www.udemy.com/user/dominik-cebula/
