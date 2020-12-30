# Hello Jib demo

Jib crée des conteneurs sans utiliser de fichier Dockerfile ni nécessiter l'installation de Docker.
Vous pouvez utiliser Jib dans les plug-ins Jib pour Maven ou Gradle, ou utiliser la bibliothèque Java Jib.

![jib.png](jib.png)

## Test on local env

```
mvn spring-boot:run
```

Then go to 

```
http://localhost:8080/hello
```

## Build local

```
mvn compile jib:buildTar
```

Image in target folder

## Build direct to grc.io

* Need google clound account

## build direct to docker.io

```
mvn compile jib:build
```

* Need docker account

```
mvn compile jib:dockerBuild
```

## Links

* https://cloud.google.com/java/getting-started/jib