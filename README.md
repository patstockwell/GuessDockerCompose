# Number Guessing game


A project made up of a java number guessing game application, and cpu player, and a mysql database.

## Setup Guide
The NumberGuess app and the NumberGuessCpuPlayer both need to be compiled.
It can be built using the build tool maven. 
Uses Docker and Docker-Compose to run.
Navigate to `/` (project root)

### Build
Build using the command
```shell
mvn clean package
```

### Launch
Run using the command
```shell
docker-compose up
```

## Play
To start guessing, open guess.html. You can register, login, and guess all from here.
Navigate to `src/main/resources/guess.html`
