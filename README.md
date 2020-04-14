# Java Agro Spring boot Project
This project is to accept the user data from agro frontned.

## Installation

create a database named agro in mysql. 

change database username and password in application.properties file


```bash
agro-api/src/main/resources/application.properties
```

Open command prompt and hit command to build the project and run the project.

for windows

```bash
gradlew build
gradlew bootRun
```
for linux/unix

```bash
./gradlew build
./gradlew bootRun
```
It will create database table and will run the application.

now after successful run. Hit http://localhost:5000/users

it should give you empty [] response. 

you are good to go.. you have successfully setuped Agro Java Backend Application. Congo. 
