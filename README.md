# SonarQube with PostgreSQL using docker-compose

* Clone repo
  
  `git@github.com:khawarhere/sonarqube-docker-compose.git`

* cd into folder
  
* Buid and run docker compose to make sonarqube live

`docker-compose up`

* To view sonarqube dashboard open in browser

[http://localhost:9000](http://localhost:9000)

# Analyse Maven project:

` ./mvnw sonar:sonar -Dsonar.host.url=http://localhost:9000 `