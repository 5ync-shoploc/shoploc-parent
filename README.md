
> **This repository is reserved for common Maven configuration. Do not add application code or microservice-specific configuration here.**
# ShopLoc Parent

Maven parent project for the ShopLoc microservices architecture.

This repository centralizes the common Maven configuration shared by the ShopLoc Java/Spring Boot microservices.

## Purpose

The `shoploc-parent` project provides common configuration for:

- Java version
- Spring Boot dependency management
- Maven plugins
- Testing configuration
- JaCoCo configuration
- Common Maven properties

Each microservice inherits from this parent POM.

Example:

```xml
<parent>
    <groupId>com.shoploc</groupId>
    <artifactId>shoploc-parent</artifactId>
    <version>1.0.0-SNAPSHOT</version>
</parent>
