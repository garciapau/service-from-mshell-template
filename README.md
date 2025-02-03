# mshell-template
PoC for cookiecutting services: Github Template + Github Action


## Running the Service locally
### As a Java Process

The simplest way to start your microservice locally is to run the following:

```bash
./gradlew run
```

This will simply build the project, then run the jar file created.

You can also create a runnable jar file that contains the compiled microservice and all it’s dependencies. To create the runnable jar use the following command:

```bash
./gradlew build
```

You can then run the jar with the following command:

```bash
java -jar build/libs/microservice-shell-java.jar server dev.yml
```
