# JavaCard tools

Minor utilities to help with JavaCard development.

## Include

Maven

```xml
<dependency>
  <groupId>com.klinec</groupId>
  <artifactId>javacard-tools</artifactId>
  <version>0.0.4</version>
</dependency>
```

Gradle

```groovy
compile 'com.klinec:javacard-tools:0.0.4'
```


## Repository

New version requires apdu4j which is not currently published on maven central.

You can add additional repositories to the gradle:

```
repositories {
    maven { url "https://javacard.pro/maven" }
    maven { url "https://deadcode.me/mvn" }
}
```

Or provide the required libraries as a static JARs. 
