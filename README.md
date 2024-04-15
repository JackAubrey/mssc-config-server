# SFG CONFIG SERVER

## Commands used to push to DockerHub and manage the version:
* mvn release:prepare
* mvn release:perform
* git checkout tags/<TAG>
* mvn clean package -DskipTests docker:build docker:push