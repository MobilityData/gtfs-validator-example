# gtfs-validator-example
A example project using the libraries gtfs validator from maven central.

This project contains a single java file (GtfsValidatorExample.java) that runs the validator on a fixed example gtfs dataset.

Included are minimal configration for building with maven or gradle.

To build and run with maven, from the root of the project:

- `mvn compile package`
- `java -cp "target/Example-1.0.jar:target/libs/*" GtfsValidatorExample`

To build and run with gradle, from the root of the project:

- `./gradlew build deployLocally`
  - the `deployLocally` task is there to make all the dependencies available to run locally.
- `java -cp "build/libs/*" GtfsValidatorExample` 

 


