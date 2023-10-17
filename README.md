Działanie programu: 

Jest to prosty program napisany w języku Python, który umożliwia wyszukiwanie informacji o produktach na stronie Amazon za pomocą zapytania. Program wykorzystuje biblioteki Pythona, takie jak requests i BeautifulSoup, do pobierania i przetwarzania danych. Po wpisaniu do programu interesującego nas produktu, program wyszukuje pierwszy wynik jaki może znaleźć. Jeżeli program nie będzie mógł znaleźć oceny, ceny lub nazwy zastąpi go napisem:
Brak (cena, ocena, tytuł). Program przyjmuje spacje i zamienia je na + aby url mógł je odczytać. Program działa wyłącznie dla strony amazon.

# Praktyki w WP 2023

## Do zrobienia
| Co | Kiedy
|--- | --- 
Nauczyć się obsługi Githuba | Tydzień 1
Stworzyć README.md i .gitignore | Tydzień 1
Napisać program w pythonie | Tydzień 1 i 2
Stworzyć obraz dockerowy | Tydzień 2 i 3
Stworzyc CI/CD | Tydzień 4

---

### Program wymagania
Program powinien łączyć się ze stroną internetową np. amazon, pobierać z niej interesujące nas dane dla wyszukiwanego produktu: jak. cena, ocena, tytuł.\
Program powinien być podzielony na funkcje. \
Wynik programu w pylint nie może być mniejszy niż 8/10.\
Praca nad programem powinna się odbywać przy wokorzystaniu systemu git.

### Docker wymagania
Obraz ma pozwalać na przekazanie mu za pomocą GitHub Actions projektu pythonowego a następnie konwersję do pliku exe (onefile).

### CI/CD wymagania
CI ma dokonywać konwersji projektu pythonowego do exe (onefile) za pomocą obrazu dockerowego.\
Akcja może być skonfigurowana automatycznie lub po ręcznym wywołaniu.\
Plik wynikowy powinien być odpowiednio wersjonowany i automatycznie lub ręcznie dodany do releases.\
Dodatkowo inne CI powinno wykonać testy pylint plików pythonowych i zwrócić wynik.

1 tydzień - Utworzono .gitignore i Readme.md

2 tydzień - Utworzono program.

2 tydzień - Skończono program w actions

2 tydzień - Ukończono wszystkie zadania