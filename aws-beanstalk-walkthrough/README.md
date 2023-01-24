# A Visual Guide to AWS Beanstalk Walkthrough Getting Started

## How to generate diagram images

Go to PlantUML at [https://plantuml.com](https://plantuml.com).
Copy a .uml file into Plant UML Server editor.

## Original Guide
[https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/GettingStarted.html](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/GettingStarted.html)

When asked, choose Correto sample application.

Application properties file defines Web Server port as 5000. 
Command-line can override this:

```
% mvn spring-boot:run -Dspring-boot.run.arguments="--server.port=8080"
```

## Visual Guide

### AWS Beanstalk 
![image](https://user-images.githubusercontent.com/595430/213908831-9d9a67fa-5a4e-4551-9b8e-7c24dd4c8d47.png)

### Concepts
![image](https://user-images.githubusercontent.com/595430/214345137-aff1e6e3-8fe6-45da-9725-c53877dc62ea.png)


### Samples
![image](https://user-images.githubusercontent.com/595430/213916478-93819d99-bf9f-4fbe-87b2-bda4855eed07.png)

### Corretto Sample POM
![image](https://user-images.githubusercontent.com/595430/213917449-140b145d-7345-432e-b8d9-546c3e4f8e6d.png)


## Spring Deploy Alternatives
![image](https://user-images.githubusercontent.com/595430/214353682-17b27201-bd8d-4f4c-bc9e-8220ae1e19b3.png)

