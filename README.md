# SerwisPlus — materiały źródłowe do ćwiczeń

Fikcyjny projekt wsparcia konsultantów AI przy przygotowaniu zgłoszeń serwisowych. Wszystkie osoby, wiadomości, dane i uzgodnienia są elementami scenariusza szkoleniowego. Pakiet jest publiczny i można go czytać bez logowania.

**Instrukcje pracy w czacie i prompty: [workbook](workbook.md).**

## Co oznacza SP-01?

„SP” oznacza SerwisPlus. Dawne oznaczenia były identyfikatorami materiałów, nie terminami BABOK ani numerami zadań. Nie trzeba się ich uczyć. W pracy wskazuj nazwę pliku oraz nagłówek, numer reguły lub decyzji.

Uwaga: dawne **SP-04 oznacza mail z decyzjami w pliku 15**, a nie plik 04 z architekturą. Poniższa mapa pozwala odczytać starsze odwołania na slajdach i tablicy.

| Dawny skrót | Materiał |
| --- | --- |
| SP-01 | [01 — brief projektu](01-brief-projektu.md) |
| SP-02 | [02 — głosy interesariuszy](02-glosy-interesariuszy.md) |
| SP-03 | [03 — reguły biznesowe](03-reguly-biznesowe.md); np. SP-03.3 to reguła 3 |
| SP-K01 / K01 | [04 — architektura biznesowa](04-architektura-biznesowa.md) |
| SP-K02 / K02 | [05 — słownik](05-slownik-biznesowy.md) |
| SP-K03 / K03 | [06 — zasady pracy z informacją](06-polityki-i-informacje.md) |
| SP-K04 / K04 | [07 — kontekst projektu](07-kontekst-projektu.md) |
| SP-04 | [15 — potwierdzone decyzje po warsztacie](maile/15-potwierdzenie-decyzji-po-warsztacie.md) |
| SP-05 | [16 — przykładowe zgłoszenia](16-przykladowe-zgloszenia.md) |
| SP-06 | [17 — szkic wymagań do oceny](rezultaty/17-wadliwy-szkic-wymagan.md) |
| SP-07 / SP-08 | [18 — późniejsza zmiana](maile/18-zmiana-kolejek-priority-standard.md) / [19 — próby po zmianie](19-proby-po-zmianie.md); dopiero moduł 7 |

## 1. Cztery podejścia do pracy analitycznej — moduł 2

Wspólny punkt wyjścia: [brief](01-brief-projektu.md), [reguły](03-reguly-biznesowe.md) i [kontekst projektu](07-kontekst-projektu.md). Następnie dobierz materiały do swojego zadania:

| Przygotowywany rezultat | Najważniejsze dodatkowe źródła | Jakie dane z nich wykorzystasz |
| --- | --- | --- |
| Business Analysis Approach | [architektura](04-architektura-biznesowa.md), [kontekst projektu](07-kontekst-projektu.md) | Granice analizy, termin rekomendacji, zasoby, niepewności i zależności |
| Stakeholder Engagement Approach | [głosy](02-glosy-interesariuszy.md), [interesariusze](08-interesariusze.md) | Potrzeby, obawy, rozbieżności, dostępność i ograniczenia kontaktu |
| Governance Approach | [brief](01-brief-projektu.md), [zasady informacji](06-polityki-i-informacje.md), [kontekst projektu](07-kontekst-projektu.md) | Znane mandaty, kwestie do decyzji, ograniczenia i brakujący sposób akceptacji, priorytetyzacji oraz obsługi zmian |
| Information Management Approach | [słownik](05-slownik-biznesowy.md), [zasady informacji](06-polityki-i-informacje.md) | Rodzaje informacji, obieg, statusy, dostęp, wersje, powiązania i aktualność |

Źródła opisują sytuację firmy. Uczestnicy proponują sposób prowadzenia analizy. Gotowe przykłady 09–12 są w folderze rezultatów i służą jako wejście dopiero od modułu 3.

## 2. Plan warsztatu — moduł 3

Wykorzystaj kontekst powyżej, [dostępność osób](08-interesariusze.md), [warunki spotkania](07-kontekst-projektu.md) i trzy notatki:

- [Cel inicjatywy i pomiar wartości](notatki-ze-spotkan/R01-cel-inicjatywy.md).
- [Granice automatyzacji](notatki-ze-spotkan/R02-granice-automatyzacji.md).
- [Jakość informacji dla techników](notatki-ze-spotkan/R03-jakosc-przekazania.md).

Przykłady podejść do dalszej pracy: [analiza](rezultaty/09-podejscie-do-analizy.md), [interesariusze](rezultaty/10-wspolpraca-z-interesariuszami.md), [decyzje](rezultaty/11-podejmowanie-decyzji.md), [informacja](rezultaty/12-zarzadzanie-informacja.md). To propozycje, nie zatwierdzone decyzje firmy.

**Stan projektu: przed warsztatem 4 września. Pliku 15 z późniejszymi decyzjami jeszcze nie używaj.**

## 3. Weryfikacja i walidacja wymagań — moduł 4

Obie grupy oceniają [ten sam szkic W01–W08](rezultaty/17-wadliwy-szkic-wymagan.md). Nie jest to zatwierdzona specyfikacja ani wzorzec odpowiedzi.

Kontekst do oceny: [brief](01-brief-projektu.md), [reguły](03-reguly-biznesowe.md), [słownik](05-slownik-biznesowy.md) oraz **[decyzje po warsztacie — D01–D08](maile/15-potwierdzenie-decyzji-po-warsztacie.md)**. [Przykładowe zgłoszenia](16-przykladowe-zgloszenia.md) pomagają sprawdzać scenariusze.

Weryfikacja dotyczy jakości wymagań; walidacja — ich związku z potrzebą, wartością i kontekstem. Definicje, kryteria i schemat własnego prompta znajdują się w workbooku. Zestaw zawiera różne przypadki; materiał nie podaje klucza ocen.

## Kolejne moduły

- Profile do wykorzystania jako dodatkowy kontekst: [osobisty](rezultaty/profil-osobisty-przyklad.md) i [analityka](rezultaty/profil-analityka-przyklad.md).
- Moduł 6: zachowaj wynik M3 i ten sam stan projektu sprzed warsztatu. Późniejsze decyzje nie mogą być wejściem do porównania.
- Moduł 7: dopiero tutaj korzystaj z materiałów 18 i 19.

## Jak pracować z plikami

Otwórz plik i skopiuj jego treść do darmowego czatu albo pobierz repozytorium przez **Code → Download ZIP**. Sam link nie gwarantuje, że czat przeczytał dokument. Podawaj nazwy dołączanych plików.

Maile i notatki pozostają w osobnych folderach. Dwa pierwsze maile powtarzają brief i reguły; nie musisz dołączać obu reprezentacji tego samego źródła. Zestawienie głosów i notatki odnoszą się do tych samych rozmów.

Zachowuj rozróżnienie: obowiązująca reguła, wypowiedź, propozycja, zatwierdzona decyzja i brak informacji. Własne wyniki zapisuj w lokalnej kopii folderu `rezultaty/`. Workbook zawiera wyłącznie pracę w czacie i prompty.
