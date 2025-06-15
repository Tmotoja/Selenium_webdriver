# Selenium Webdriver - Przykłady automatyzacji przeglądarki

To repozytorium zawiera przykłady testów oraz automatyzacji przeglądarki internetowej z wykorzystaniem Selenium Webdriver w języku Python. Skrypty pokazują, jak otwierać strony, wyszukiwać informacje, obsługiwać okna i karty oraz wykonywać zrzuty ekranu.

## Wymagania

- Python 3.x
- Selenium (`pip install selenium`)
- ChromeDriver (dołączony w repozytorium jako `chromedriver`)

## Opis plików

- **wyszukowanie_selenium.py**  
  Skrypt otwiera stronę Google, akceptuje cookies, wpisuje zapytanie w wyszukiwarkę i wysyła je. Przykład prostego wyszukiwania.

- **test_wyszukiwanie_google.py**  
  Skrypt testowy (funkcja `test_wyszukiwanie`) wykonujący podobne kroki jak powyżej, z asercją sprawdzającą tytuł strony oraz wyszukiwaniem wyników.

- **opening_browser_tabs_selenium.py**  
  Przykład otwierania nowej karty w przeglądarce, przełączania się między kartami oraz ładowania różnych stron.

- **url_test_selenium.py**  
  Skrypt otwierający stronę W3Schools, obsługujący cookies, nawigujący po menu, otwierający nowe okno oraz wykonujący zrzut ekranu.

## Jak uruchomić skrypty

1. Upewnij się, że masz zainstalowanego Pythona oraz bibliotekę Selenium.
2. Upewnij się, że plik `chromedriver` jest w tym samym katalogu co skrypty lub w zmiennej PATH.
3. Uruchom wybrany skrypt poleceniem:

   ```sh
   python NAZWA_PLIKU.py
   ```
