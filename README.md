# jib-jar-example
JIB example to run jar file


Step to run when using JIB (pom_jib.xml):

1. Run `mvn package jib:dockerBuild`
2. Run `docker run -p 8080:8080 my-jib1`


Step to run when using fabric8 (pom.xml):

1. Run `mvn package docker:run`
