Uruchomienie aplikacji

Wymagane programy: - Intellij (środowisko Java) - Dbeaver (program do zarzadzania bazą danych, mogą być inne(postgresql)) - Pgadmin4 (do utworzenia bazy danych) - Postman (do obsługi zapytań HTTP)

1. Tworzymy bazę danych w pgAdmin4.
2. Tworzymy połączenie z bazą danych np w DBeaver.
3. Wprowadzamy dane połączenia z bazą danych w pliku .yml.
4. Uruchamiamy aplikację.
5. Baza danych zostanie wygenerowana automatycznie po uruchomieniu aplikacji jeśli mamy skonfugurowane połączenie.
6. Po uruchomieniu aplikacji zostanie wygenerowany token
7. Uruchamiamy postmana
8. Wprowadzamy doken do Auth w postmanie aby żądanie mogło byc prawidłowo obsłużone
9. Wprowadzamy żądane parametry dla danego endpointu w kontrolerze.


Application Launch

Required programs:

  IntelliJ (Java IDE)
  DBeaver (database management tool, other options like PostgreSQL are also possible)
  Pgadmin4 (for creating the database)
  Postman (for handling HTTP requests)
  
1. Create a database in pgAdmin4.
2. Establish a connection to the database, for example, using DBeaver.
3. Enter the connection details to the database in the .yml file.
4. Launch the application.
5. The database will be automatically generated upon application startup if the connection is properly configured.
6. After launching the application, a token will be generated.
7. Launch Postman.
8. Enter the token into the Auth section in Postman to ensure proper handling of the request.
9 Enter the desired parameters for a specific endpoint in the controller.
