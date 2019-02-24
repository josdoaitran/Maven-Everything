# Maven-Everything
Maven-Everything
## I. Maven ?

Maven is a Java tool, so you must have Java installed in order to proceed.
Maven is an automation and management tool developed by `Apache` Software Foundation.
It helps to *build projects* , *dependency*, and *documentation*. Its development process is very similar to ANT.However, it is much advanced than ANT.

Maven is also able to build any number of projects into desired output such as jar, war, metadata.

## II. Maven Local Repository ?

We will have this flow for manage repositories with maven

## III. Maven Everything

### 3.1 Installation:

First, download Maven and follow the installation instructions. After that, type the following in a terminal or in a command prompt:

```mvn --version```

### 3.2 Maven command

#### 3.2.1 Create a Maven project

`mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false`

#### 3.2.2 POM file

pom.xml

```
project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
  xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
  <modelVersion>4.0.0</modelVersion>
 
  <groupId>com.mycompany.app</groupId>
  <artifactId>my-app</artifactId>
  <version>1.0-SNAPSHOT</version>
 
  <properties>
    <maven.compiler.source>1.7</maven.compiler.source>
    <maven.compiler.target>1.7</maven.compiler.target>
  </properties>
 
  <dependencies>
    <dependency>
      <groupId>junit</groupId>
      <artifactId>junit</artifactId>
      <version>4.12</version>
      <scope>test</scope>
    </dependency>
  </dependencies>
</project>
```
