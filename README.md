# Hello World Java

A minimal Java Maven project that prints `Hello, world!`.

## Prerequisites

- Java 17 or later
- Maven 3.8 or later

## Run

```bash
mvn compile exec:java
```

## Test

```bash
mvn test
```

## Build

```bash
mvn package
```

After building, run the generated JAR:

```bash
java -jar target/hello-world-java-1.0.0.jar
```

## Upload To Git

```bash
git init
git add .
git commit -m "Initial hello world Java project"
git branch -M main
git remote add origin <your-repository-url>
git push -u origin main
```
