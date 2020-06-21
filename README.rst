Jenkins
=======

1. Uruchom jenkins-a:

   ::

     make build_jenkins
     make run_jenkins - jesli docker jest wyczony

     docker ps -a | grep jenkins

     komenda sprawdza jaki doker mamy odpalony

     docker start jenkins-wsb

     komenda do uruchomienia jenkinsa o nazwie jenkins-wsb


2. Otwórz w przeglądarce 127.0.0.1:8080, jeśli zostaniesz poproszony o hasło dla admina, wybierz:

   ::

     cat jenkins/secrets/initialAdminPassword

3. Wybierz *Suggested plugins*.


Related
-------

- https://github.com/sheehan/job-dsl-gradle-example
