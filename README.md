# Aplikacja do Zarządzania Sprzedażą Wielokanałową - Menedżer Ofert

## Cel Projektu

Celem projektu jest stworzenie aplikacji webowej (narzędzia typu SaaS) przeznaczonej dla sprzedawców internetowych, która zautomatyzuje i ułatwi zarządzanie ofertami na wielu platformach e-commerce jednocześnie.

## Główne Funkcjonalności

Aplikacja, wykorzystując oficjalne API partnerów, umożliwi:
1.  **Import ofert:** Pobieranie aktywnych ofert z platformy Allegro.pl.
2.  **Kopiowanie ofert:** Proste przenoszenie i wystawianie zaimportowanych ofert na platformie OLX.pl, z możliwością edycji i dostosowania danych (tytuł, opis, cena, zdjęcia, atrybuty).
3.  **Synchronizacja stanów magazynowych:** Automatyczne monitorowanie sprzedaży na obu platformach. W przypadku sprzedaży produktu na jednym z serwisów, aplikacja automatycznie zaktualizuje stan magazynowy lub zakończy ofertę na drugim, aby zapobiec sprzedaży przedmiotów, które nie są już dostępne.

## Wykorzystywane Technologie

*   **Platformy API:** Allegro REST API, OLX Partner API
*   **Stos technologiczny:** Node.js, Express.js, React, TypeScript, PostgreSQL

## Informacje dla Weryfikatorów API

Aplikacja jest obecnie w aktywnej fazie deweloperskiej. Dostęp do API jest niezbędny do dalszego rozwoju i testowania kluczowych funkcjonalności. Wnioskujemy o dostęp w celu integracji i zapewnienia zgodności z wytycznymi technicznymi platformy.

**Adres URL aplikacji (deweloperski):**
W fazie rozwoju, do testowania przepływu OAuth 2.0, wykorzystywany jest tymczasowy, bezpieczny tunel HTTPS generowany przez ngrok. Finalna aplikacja będzie hostowana pod stałą, publiczną domeną z certyfikatem SSL.```
