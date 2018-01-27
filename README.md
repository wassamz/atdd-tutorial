# Acceptance Test Driven Design Sample
- This tutorial involves sample tests to implement ATDD using TestNG, Cucumber, and Maven

### Pre-requisite
- Maven 3.3.9+ installed
- JDK 1.8+ installed

### Setting up environment
1. Clone this repo
1. Import project to IDE
1. Download latest drivers (Note: drivers will be downloaded to _<project_root_dir>/drivers_)
   <br>`mvn clean compile -P download-drivers`
1. Create a local copy of **config.properties** from config-template.properties in _src/main/resources_
1. Update configuration values in config.properties where needed