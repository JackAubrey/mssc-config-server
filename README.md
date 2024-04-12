# SFG CONFIG SERVER

## Commands used to push to DockerHub and manage the version:
* mvn clean package -DskipTests docker:build docker:push
* mvn release:prepare
* mvn release:perform
* git checkout tags/<ARTIFACT>-<TAG>
* mvn clean package -DskipTests docker:build docker:push