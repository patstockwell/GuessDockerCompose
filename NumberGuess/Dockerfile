#NumberGuess Program


FROM		java:8-jdk
RUN			mkdir /numberguess
WORKDIR		/numberguess
ADD			. /numberguess

ENTRYPOINT	["java","-jar", "/numberguess/target/NumberGuess-0.0.1-SNAPSHOT.jar"]