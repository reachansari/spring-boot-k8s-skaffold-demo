![](./img/header.png)

## [spring-boot-k8s-skaffold-demo](#spring-boot-k8s-skaffold-demo)
Deploy springboot app in kubernetes using skaffold.

## [Prerequisite / Libraries used](#Prerequisite)
* Docker and kubernetes cluster
* kubectl
* Spring Boot
* Spring Configuration
* Spring REST Controller
* Skaffold

## [Skaffold](#skaffold)
Skaffold is a command line tool that facilitates continuous development for Kubernetes-native applications. Skaffold handles the workflow for building, pushing, and deploying your application, and provides building blocks for creating CI/CD pipelines. This enables you to focus on iterating on your application locally while Skaffold continuously deploys to your local or remote Kubernetes cluster.

## [Compilation command](#compilation-command)
```mvn clean package -DskipTests```

## [Execution command](#execution-command)
```skaffold dev``` : To build and deploy your app every time your code changes

spring-boot-k8s-skaffold-demo