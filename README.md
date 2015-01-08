Apache Olingo Spring and CXF Reference Scenarion Sample
=======================================================

## Pre-Requisites
To use this it is necassary to...
  * ...check out [this commit](https://git-wip-us.apache.org/repos/asf?p=olingo-odata2.git;a=commit;h=92531140bb369a98a12c6a85f3f8aac08fb803bc)
  * ...build checked out project (`mvn clean install`)
  * ...as well as the separate `odata2-spring` extension (via `mvn clean install`)

Afterwards this project can be build and run without problems.

## Quick-Sample-Start
Just call `mvn` and after startup is finished open [http://localhost:8080/](http://localhost:8080/) in the browser

## Sample Start

### Build
Simple build with `mvn clean install`

### Run
After build deploy created WAR (e.g. `target/spring-cxf-ref-0.1.0.war`) in application server (e.g. *Tomcat*)

### Test
Simpe call [http://localhost:8080/](http://localhost:8080/) to see the welcome site with additional links
