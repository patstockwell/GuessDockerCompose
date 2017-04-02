# Number Guessing game


A project made up of a java number guessing game application, and cpu player, and a mysql database.
Uses Docker and Docker-Compose to run.

## Setup Guide
The NumberGuess app and the NumberGuessCpuPlayer both need to be compiled.
It can be built and run using the build tool maven. 

### App
```shell
/NumberGuess
```
Compile using the command

```shell
mvn clean package
```

### CPU Player
```shell
/NumberGuessCpuPlayer
```
Compile using the command
```shell
mvn clean package
```

### Launch
```shell
/
```
Run using the command

```shell
docker-compose up
```

### Play
To start guessing, open guess.html. You can register, login, and guess all from here.
Navigate to
```shell
src/main/resources/guess.html
```
