Komendy do GIT:
1. Sklonowanie repozytorium: git clone <adres url>
2. Zmiana brancha / stworzenie nowego brancha: git checkout <branch name>
3. Sciągnięcie z serwera zmian będących na branchu: git pull
4. Dodanie zmienionego pliku do commita: git add <file name>
5. Dodanie opisu do commita: git commit -m '<description>'
6. Wysłanie zmian na serwer: git push
7. Usunięcie brancha jeśli nie jest już potrzebny
7.1. Lokalnie: git delete -d <branch name>
7.2. Z serwera: git push origin --delete <branch name>