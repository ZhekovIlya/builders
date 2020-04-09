# Ant+Ivy

Needs `build.xml` in directory

To start build run `ant clean build` 
To start tests run `ant clean test`

Could be started in each of separate project e.g.:
`cd admin`
`ant clean test`

# Maven

Needs `pom.xml`

To start build run `mvn clean package` 
To start tests run `mvn clean test`

Could be started in each of separate project e.g.:
`cd admin`
`mvn clean test`

# Gradle

Needs `gradlew && gradlew.bat`

To start build run `gradlew` 
To start tests run `gradlew test`

To build separate project u need specify which one and task, e.g.:
`gradlew :admin:build`

