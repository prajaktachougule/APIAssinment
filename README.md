# APIAssinment


## API


## Framework

### Structure
This project is your standard Maven Java project with `src` folders and `POM.xml`.

### Utility
`src/main/java/utility` represent API entities with class properties equal to JSON response fields. This lets us serialize and deserialize  requests and responses easily.
In order for the serialization to work properly, names of the fields must match JSON convention thus they violate Java camel case convention (it can be overriden using `@JsonProperty` annotations in real-life projects).

### Properties
`src/test/resources/config.properties` is a simple properties file to store various configurations

### Tests
