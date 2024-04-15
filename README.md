# Projekt Cypress - Testy automatyczne dla aplikacji GoIT

## Opis projektu
Ten projekt zawiera testy automatyczne napisane przy użyciu narzędzia Cypress dla aplikacji GoIT. Testy obejmują dwa scenariusze logowania i wylogowywania się użytkowników na stronie.

## Instalacja
1. Sklonuj repozytorium na swój komputer:
    ```
    git clone <adres_url_repozytorium>
    ```
2. Przejdź do katalogu projektu Cypress:
    ```
    cd nazwa_katalogu_projektu
    ```
3. Zainstaluj wszystkie wymagane zależności:
    ```
    npm install
    ```

## Uruchomienie testów
Po zainstalowaniu projektu, możesz uruchomić testy Cypress w terminalu, wykonując polecenie:
    ```
    npm run cypress:open
    ```
    Wybierz odpowiednią przeglądarkę i kliknij na test, który chcesz uruchomić.

## Testy
### Test 1: Logowanie użytkownika user888
1. Test otwiera stronę logowania GoIT.
2. Wprowadza adres email "user888@gmail.com" i hasło "1234567890".
3. Kliknięcie przycisku "Log in".
4. Znajduje przycisk w prawym górnym rogu, otwiera menu strony i kliknięcie przycisku "Log out".

### Test 2: Logowanie użytkownika testowyqa
1. Test otwiera stronę logowania GoIT.
2. Wprowadza adres email "testowyqa@qa.team" i hasło "QA!automation-1".
3. Kliknięcie przycisku "Log in".
4. Znajduje przycisk w prawym górnym rogu, otwiera menu strony i kliknięcie przycisku "Log out".

## Autor
Autor: Weronika Skarbek
Kontakt: w3r0n1k4sk4rb3k@gmail.com
