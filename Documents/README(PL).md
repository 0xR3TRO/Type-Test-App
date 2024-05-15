## Opis projektu

### Cel:

Projekt "Type Test App" ma na celu dostarczenie użytkownikom narzędzia do mierzenia czasu pisania i ilości naciskanych klawiszy. Aplikacja umożliwia śledzenie wydajności pisania na klawiaturze, co może być wykorzystane do samodoskonalenia, treningu szybkiego pisania oraz analizowania efektywności.

### Opis funkcji:

- **Pomiar czasu:** Użytkownicy mogą mierzyć czas potrzebny na napisanie określonego tekstu.
- **Licznik naciśnięć klawiszy:** Aplikacja rejestruje liczbę naciskanych klawiszy podczas pisania.
- **Personalizacja testu:** Możliwość wyboru długości i trudności tekstu testowego.
- **Historia wyników:** Przechowywanie i przeglądanie wcześniejszych wyników.
- **Udostępnianie wyników:** Opcja udostępniania wyników na platformach społecznościowych lub eksportowania ich do pliku.

## Analiza wymagań:

### Wymagania funkcjonalne:

- **Pomiar czasu:** Użytkownik może mierzyć czas pisania dla wybranego tekstu.
- **Licznik naciśnięć klawiszy:** Aplikacja rejestruje liczbę naciśnięć klawiszy i wyświetla wynik po zakończeniu testu.
- **Personalizacja testu:** Możliwość wyboru różnych tekstów testowych oraz ich poziomów trudności.
- **Historia wyników:** Aplikacja przechowuje historię wyników użytkownika z możliwością przeglądania i analizy.
- **Udostępnianie wyników:** Użytkownik może udostępniać swoje wyniki lub eksportować je do pliku.

### Wymagania niefunkcjonalne:

- **Dokładność pomiaru:** Aplikacja musi precyzyjnie mierzyć czas i liczbę naciśnięć klawiszy.
- **Szybkość działania:** Aplikacja powinna działać płynnie i bez opóźnień.
- **Interfejs użytkownika:** Przyjazny i intuicyjny interfejs, łatwy w obsłudze.

## Projekt interfejsu:

### Szkice/wizualizacje interfejsu:

- _Strona główna:_ Panel sterowania z opcjami rozpoczęcia testu, dostępu do historii wyników, ustawień personalizacji.
- _Okno testu:_ Obszar do wpisywania tekstu, licznik czasu, licznik naciśnięć klawiszy.
- _Historia wyników:_ Przeglądanie i analiza wcześniejszych wyników.

### Mapa strony:

- _Strona główna_
  - Panel sterowania
  - Rozpoczęcie testu
  - Historia wyników
- _Okno testu_
  - Pole do wpisywania tekstu
  - Licznik czasu
  - Licznik naciśnięć klawiszy
- _Historia wyników_
  - Lista wcześniejszych wyników
  - Możliwość udostępniania i eksportowania

## Architektura systemu:

### Opis struktury danych:

Aplikacja przechowuje dane testów pisania, w tym:

- **Parametry testu:** Informacje o wybranym tekście i poziomie trudności.
- **Wyniki:** Przechowywane dane o czasie pisania, liczbie naciśnięć klawiszy oraz dacie wykonania testu.

### Diagramy architektury:

Architektura oparta jest na modelu MVC, gdzie:

- **Model:** Odpowiada za logikę pomiaru i zarządzanie danymi testów.
- **Widok (View):** Prezentuje interfejs użytkownika.
- **Kontroler (Controller):** Zarządza komunikacją między modelem a widokiem.

## Implementacja:

### Opis technologii:

- **Frontend:** HTML, CSS, JavaScript (React.js).
- **Backend:** Flask (Python).
- **Baza danych:** SQLite (przechowywanie danych o testach i wynikach).

### Struktura kodu:

- _Katalogi/pliki_: Oddzielne pliki dla logiki pomiaru, interfejsu, zarządzania danymi.
- _Style pisania kodu_: Zastosowanie modularności, czytelności i komentarzy w kodzie.

## Testowanie:

### Plan testów:

- **Testy jednostkowe:** Sprawdzenie poprawności funkcji pomiaru czasu i naciśnięć klawiszy.
- **Testy integracyjne:** Upewnienie się, że komponenty współpracują ze sobą poprawnie.
- **Testy interfejsu użytkownika:** Sprawdzenie interakcji z użytkownikiem na różnych urządzeniach.
- **Testy wydajnościowe:** Ocena wydajności aplikacji podczas różnych testów pisania.

### Procedury testowania:

- Opracowanie zestawu przypadków testowych dla każdej funkcji aplikacji.
- Ustalenie procedur raportowania i naprawiania znalezionych błędów.

## Wdrożenie i konserwacja:

### Plan wdrożenia:

- **Etapy wdrażania:** Testowanie, poprawki, publikacja na platformach dostępnych dla użytkowników.
- **Terminy:** Określenie dat planowanych etapów.

### Procedury konserwacji:

- **Wsparcie techniczne:** Ustanowienie kanałów komunikacji z użytkownikami w celu zgłaszania problemów.
- **Aktualizacje:** Planowanie regularnych aktualizacji w zależności od potrzeb i feedbacku użytkowników.

## Harmonogram:

### Plan projektu:

- **Etapy realizacji:** Podział prac na konkretne zadania (np. implementacja licznika czasu, interfejsu, testowanie).
- **Terminy:** Określenie czasu potrzebnego na każdy etap.

## Kosztorys:

### Szacunkowe koszty:

- **Rozwój aplikacji:** Wg godzin pracy lub zespołu programistów.
- **Koszty utrzymania:** Serwery, ewentualne opłaty za usługi zewnętrzne, wsparcie techniczne.
