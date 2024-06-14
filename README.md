
# Pan Tadeusz - Strona z podziałem na księgi

Ten projekt to strona internetowa prezentująca utwór "Pan Tadeusz" Adama Mickiewicza, podzielony na księgi. Strona została stworzona przy użyciu frameworka Flask.

## Zawartość projektu

- `app.py`: Główny plik aplikacji Flask.
- `templates/index.html`: Plik HTML zawierający strukturę strony głównej.
- `static/style.css`: Plik CSS zawierający style dla strony.
- `static/images/PanTadeusz.jpg`: Obrazek użyty na stronie.

## Wymagania

- Python 3.x
- Flask

## Instalacja

1. Sklonuj repozytorium lub pobierz pliki projektu.
2. Upewnij się, że masz zainstalowanego Pythona w wersji 3.x.
3. Zainstaluj wymagane biblioteki za pomocą pip:
    ```bash
    pip install Flask
    ```

## Struktura katalogów

Upewnij się, że struktura katalogów wygląda następująco:

```
your_project/
│
├── static/
│   ├── images/
│   │   └── PanTadeusz.jpg
│   └── style.css
│
├── templates/
│   └── index.html
│
├── app.py
└── requirements.txt
```

## Uruchomienie aplikacji

1. Otwórz terminal w katalogu głównym projektu.
2. Uruchom aplikację Flask:
    ```bash
    python app.py
    ```
3. Otwórz przeglądarkę i przejdź do `http://127.0.0.1:5000/`, aby zobaczyć stronę główną.

## Użycie

Strona główna zawiera linki do poszczególnych ksiąg "Pana Tadeusza". Kliknięcie na dowolny link przeniesie użytkownika do odpowiedniej księgi.

## Autor

Filip Moskała

