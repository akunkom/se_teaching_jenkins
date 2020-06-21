Jenkins
=======

1. Uruchom jenkins-a (z poziomu roota):

   ::

     make build_jenkins

     make run_jenkins

2. Otwórz w przeglądarce 127.0.0.1:8080, jeśli zostaniesz poproszony o hasło dla admina, wybierz:

   ::

     cat jenkins/secrets/initialAdminPassword

3. Wybierz *Suggested plugins*.
4. Aby się zalogować, użyj loginu 'admin' i hasła użytego podczas konfigurowania Jenkinsa.
 (do sprawdzenia hasła w root: cat jenkins/secrets/initialAdminPassword) 


Related
-------

- https://github.com/sheehan/job-dsl-gradle-example
