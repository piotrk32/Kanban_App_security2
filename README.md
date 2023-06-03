Uruchomienie aplikacji

Wymagane programy: - Intellij (środowisko Java) - Dbeaver (program do zarzadzania bazą danych, mogą być inne(postgresql)) - Pgadmin4 (do utworzenia bazy danych) - Postman (do obsługi zapytań HTTP)

Tworzymy bazę danych w pgAdmin4.
Tworzymy połączenie z bazą danych np w DBeaver.
Wprowadzamy dane połączenia z bazą danych w pliku .yml.
Uruchamiamy aplikację.
Baza danych zostanie wygenerowana automatycznie po uruchomieniu aplikacji jeśli mamy skonfugurowane połączenie.
Po uruchomieniu aplikacji zostanie wygenerowany token
Uruchamiamy postmana
Wprowadzamy doken do Auth w postmanie aby żądanie mogło byc prawidłowo obsłużone
Wprowadzamy żądane parametry dla danego endpointu w kontrolerze.
