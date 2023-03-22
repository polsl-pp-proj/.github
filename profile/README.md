# Projekt Programistyczny

## Uruchamianie projektu

Aplikacja została zaimplementowana w formie SPA (ang. single page application) z wykorzystaniem frameworka [Angular](https://angular.io/) po stronie frontendu oraz [NestJS](https://nestjs.com/) pracującym w środowisku [Node.js](https://nodejs.org/) po stronie backendu.

W celu uruchomienia lokalnej wersji projektu, wymagane są:

-   kod źródłowy frontendu aplikacji,
-   kod źródłowy backendu aplikacji,
-   serwer systemu zarządzania bazą danych [PostgreSQL](https://www.postgresql.org/).

### Szybki start

1. Uzyskaj dostęp do prywatnych repozytoriów projektu.
2. Sklonuj repozytorium backendu.
3. Sklonuj repozytorium frontendu.
4. Uruchom serwer PostgreSQL.
5. Skonfiguruj backend, kopiując plik `.env.template` jako `.env` i wypełniając go odpowiednimi wartościami.
6. Skonfiguruj frontend, uzupełniając plik `src/environments/environment.ts` oraz `src/environments/environment.prod.ts` odpowiednimi wartościami.
7. Uruchom backend aplikacji wywołując
    ```
    npm run start
    ```
    w katalogu backendu projektu.
8. Uruchom frontend aplikacji wywołując
    ```
    npm run start
    ```
    w katalogu frontendu projektu.
9. Przejdź do adresu wyświetlonego przez serwer frontendu aplikacji.
