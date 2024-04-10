## Maven Archetype (Draft)

This module contains a Maven Archetype Plugin.

## Local install

```
mvn install
```
## Usage

```
mvn archetype:generate -DinteractiveMode=false -DarchetypeGroupId=com.oracle.nosql.archetypes \
   -DarchetypeArtifactId=spring-boot-nosql \
   -DarchetypeVersion=1.0-SNAPSHOT \
   -DgroupId=com.oracle.nosql.example \
   -DartifactId=spring-boot-nosql-sample \
   -Dspring-boot-starter=3.2.1 \
   -Dversion=1.0-SNAPSHOT 
```

```
tree spring-boot-nosql-sample
cd spring-boot-nosql-sample
# Please review src/resource/application.properties
mvn compile
mvn exec:java -D exec.mainClass="com.oracle.nosql.example.App"
```
