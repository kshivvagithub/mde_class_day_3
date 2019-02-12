# backend_os
backend_os
testing Jenkins build on AWS after configuring key new job jenkins

Day 3 Steps:
1) git clone https://github.com/kshivvagithub/mde_class_day_3.git
2) Open STS or eclispe, import as maven project, right click on the project and select maven -> update project
3) open command promp -> go to folder -> mde_class_day_3 -> mvn spring-boot:run -Drun.profiles=h2
4) try the following URLS
  http://localhost:8080/h2-console
  http://localhost:8080/todo
  http://localhost:8080/metrics
  http://localhost:8080/health
  http://localhost:8080/autoconfig
5) pgAdmin4 - login: password: postgres (sample)
    create database: tododb
    connection URL-> localhost:5432
    Database: postgres or tododb
6)    
  
