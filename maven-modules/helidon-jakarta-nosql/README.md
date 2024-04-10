## Maven Archetype

This module contains a Maven Archetype Plugin.

## Local install

```
mvn install
```
## Usage

```
mvn archetype:generate -DinteractiveMode=false -DarchetypeGroupId=com.oracle.nosql.archetypes \
   -DarchetypeArtifactId=helidon-jakarta-nosql \
   -DarchetypeVersion=1.0-SNAPSHOT \
   -DgroupId=com.oracle.nosql.example \
   -DartifactId=helidon-jakarta-nosql-sample \
   -Dversion=1.0-SNAPSHOT 
```

```
tree helidon-jakarta-nosql-sample
cd helidon-jakarta-nosql-sample
mvn package
java -jar target/helidon-jakarta-nosql-sample.jar
```

[More instructions in: https://github.com/dario-vega/test-helidon](https://github.com/dario-vega/test-helidon)


