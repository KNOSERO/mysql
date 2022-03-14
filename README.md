# Projekt konfiguracji dockera z mysql oraz phpmyadmin
## Utworzenie lokalnie bazy danych
1. Instalujemy 
    - Node.js
    - Docker
    - WSL
    - yarn
2. Tworzymy plik `.env` z pliku `.env.template` 
3. Wyszykujemy lokalizacje projektu w konsoli WSL
4. Uruchamiamy komende
```
docker-compose up -d --build
```