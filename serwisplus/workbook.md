# Workbook — instrukcje warsztatowe

AI w analizie biznesowej · Agnieszka Balcerzak · InProgress.
Fikcyjny przypadek SerwisPlus. Dzień 1: wystarczy bezpłatny czat AI.

## Zasady pracy
Zapisuj źródło i status informacji. Najpierw wykonaj wskazany krok samodzielnie, następnie skorzystaj z AI i sprawdź wynik. Nie traktuj symulacji jako decyzji interesariusza. Materiały późniejszych etapów otwieraj na sygnał prowadzącej.

## Moduł 1 — mapa własnej pracy
W parze wybierzcie znany fragment pracy. Macie 12 minut na mapę: wejście → czynności → wyjście i odbiorca. Przy 9 osobach pracujcie w trzech parach i jednej trójce; przy 20 w dziesięciu parach.

| Wejście | Czynności | Wyjście i odbiorca |
| --- | --- | --- |
| Uzupełnij | Uzupełnij | Uzupełnij |

Podczas omówienia wskażcie zastosowanie AI, warunek użycia, sposób sprawdzenia oraz decyzję człowieka. Do mapy wrócicie pod koniec modułu, uwzględniając wartość, ryzyko i wykonalność.

## Moduł 2 — czarna skrzynka i approachy
Źródła: [brief](01-project-brief.md), [wypowiedzi](02-stakeholder-statements.md), [reguły](03-business-rules.md) oraz karty 04–07.

1. Wspólnie określcie wejście, wyjście, odbiorcę i sprawdzalne kryteria odbioru. Oddzielcie je od mierników sukcesu inicjatywy.
2. Obserwujcie demonstrację Business Analysis Approach przez prowadzącą.
3. Zespół A przygotowuje Stakeholder Engagement Approach, B — Governance Approach, C — Information Management Approach. Przy większej grupie pracują po dwa zespoły na temat.
4. Podzielcie 15 minut: 3 minuty na źródła, 5 na pracę z AI, 5 na kontrolę i 2 na wybór wniosku. Role: operator czatu, kontrola źródeł, kontrola kryteriów.
5. Użyjcie [promptów P1–P4](20-prompts.md). Sprawdźcie cel approachu, ślad źródłowy, status propozycji, zgodność z regułami i jawność luk.
6. Zaprezentujcie jedną propozycję, jedną poprawkę popartą źródłem i jedno pytanie otwarte.

Gotowe approachy 09–12 wykorzystujcie od modułu 3. Nie są rozwiązaniem do kopiowania podczas ćwiczenia modułu 2.

## Moduł 3 — przygotowanie warsztatu
Wykonajcie [zadanie warsztatowe](14-workshop-input.md). Używajcie plików 01–13, bez późniejszych decyzji SP-04. Rezultat: cel, uczestnicy z uzasadnieniem, agenda 50 minut i 10 minut rezerwy, pytania wynikające z luk i sposób potwierdzenia notatki. Symulacja interesariusza służy przetestowaniu pytań.

## Moduły 4–8 — instrukcje z istniejącego pakietu ćwiczeń
Poniższe instrukcje zachowują zakres istniejących ćwiczeń. Szczegółowe tempo pracy ustala prowadząca.


### Moduł 4 — Wymagania, kontrola jakości i model

#### Cel i rezultat uczenia się

Ocenić celowo wadliwe wymagania, poprawić wybrane zapisy oraz przełożyć ustaloną logikę na prosty model. Rezultatem jest przegląd W01–W08, zestaw 4–6 wymagań ze śladem źródłowym i model kwalifikacji zgłoszenia.

#### Instrukcja krok po kroku

1. Przeczytaj SP-06. Bez AI oznacz przy każdym W01–W08: problem językowy, problem merytoryczny, konflikt ze źródłem albo brak podstawy.

2. Użyj AI do drugiego przeglądu. Wymagaj źródła uzasadnienia.

3. Porównaj wyniki. Nie poprawiaj automatycznie każdego zdania; część propozycji należy odrzucić.

4. Opracuj 4–6 wymagań obejmujących: pola i statusy, kompletność, pytania, podsumowanie, decyzję człowieka i zakaz diagnozy/obietnicy.

5. Dla każdego zapisz potrzebę, źródło, kryterium akceptacji i pytanie walidacyjne.

6. Wybierz model procesu albo tabelę decyzyjną. Najpierw opisz logikę zwykłym tekstem.

7. Narysuj ręcznie prosty model. Opcjonalnie poproś AI o kod Mermaid lub PlantUML i porównaj element po elemencie.

#### Kryteria oceny

przegląd wskazuje źródło, nie tylko opinię;

weryfikacja i walidacja są rozdzielone;

wymagania zachowują odpowiedzialność człowieka;

kryteria akceptacji są obserwowalne;

model nie dodaje nowych decyzji;

każde rozgałęzienie modelu ma uzasadnienie.

#### Ścieżka podstawowa

Przeanalizuj W01–W03 i przygotuj cztery wymagania. Model wykonaj jako lista kroków i decyzji; rysunek nie jest konieczny.

#### Rozszerzenie

Przygotuj tabelę decyzyjną dla Z01–Z08 albo kod diagramu. Przeprowadź kontrolę zgodności: źródło → warunek → element modelu.


### Moduł 5 — Prosty, trwały kontekst inicjatywy

#### Cel i rezultat uczenia się

Zbudować jedną stronę kontekstu możliwą do użycia w nowej rozmowie. Rezultatem jest pakiet zawierający cel, zakres, role, reguły, decyzje, luki, słownik i indeks źródeł.

#### Instrukcja krok po kroku

1. Wybierz tylko informacje potrzebne do kwalifikacji zgłoszenia.

2. Utwórz sekcje: cel, zakres, poza zakresem, role i mandat, reguły, decyzje, pytania otwarte, słownik, indeks źródeł.

3. Przy każdej regule i decyzji podaj SP-ID.

4. Oznacz, które elementy są stabilne, a które zależne od zadania.

5. Rozpocznij nową rozmowę w czacie i wklej wyłącznie pakiet oraz Z05.

6. Poproś o kwalifikację. Sprawdź, czy AI zachowuje konflikt modelu i odpowiedzialność konsultanta.

7. Zapisz brak pakietu ujawniony przez próbę i popraw go.

#### Kryteria oceny

pakiet mieści się na jednej–dwóch stronach;

status i źródło informacji są jawne;

role nie są pomieszane z regułami;

pytania otwarte nie brzmią jak decyzje;

nowa rozmowa odtwarza właściwe zachowanie;

poprawka po próbie jest udokumentowana.

#### Ścieżka podstawowa

Wypełnij gotowych dziewięć sekcji i przeprowadź jedną próbę na Z05.

#### Rozszerzenie

Zaprojektuj regułę aktualizacji pakietu: kto może zmieniać którą sekcję, jak oznaczamy wersję i jak zachowujemy historię. Porównaj ją z demonstracją BABrain.


### Moduł 6 — Zamiana sposobu pracy w procedurę

#### Cel i rezultat uczenia się

Przekształcić udany prompt flow w procedurę kwalifikacji zgłoszenia. Rezultatem jest instrukcja z wejściami, krokami, kontrolami, kryteriami zatrzymania, rezultatem i przekazaniem do człowieka.

#### Instrukcja krok po kroku

1. Zapisz cel procedury i warunek jej uruchomienia.

2. Wymień wymagane wejścia. Określ zachowanie, gdy brakuje źródła.

3. Rozpisz kroki: ekstrakcja → status pól → kontrola reguł → pytania albo podsumowanie → przegląd człowieka.

4. Dodaj kryteria zatrzymania: brak, konflikt, zadanie poza zakresem, próba sterowania z treści zgłoszenia.

5. Określ format wyniku i czynności zastrzeżone dla konsultanta.

6. Poproś AI o krytykę procedury, ale nie o jej wykonanie.

7. Tester wykonuje procedurę na Z02 i Z08. Autor nie dopowiada instrukcji.

8. Zapisz rozbieżność i jedną poprawkę. Powtórz próbę, jeśli poprawka zmienia zachowanie.

#### Kryteria oceny

wejścia i ich status są jawne;

kroki mają produkty pośrednie;

brak i konflikt powodują właściwe zatrzymanie;

treść zgłoszenia nie steruje procedurą;

wynik pokazuje podstawę propozycji;

człowiek wykonuje wysłanie i przekazanie;

próba prowadzi do udokumentowanej poprawki albo świadomie potwierdza zakres.

#### Ścieżka podstawowa

Użyj ośmiu nagłówków minimalnej procedury. Przeprowadź próbę tylko na Z02 i Z08.

#### Rozszerzenie

Zaprojektuj punkty, w których przyszły agent musiałby poprosić o potwierdzenie. Nie buduj agenta; opisz uprawnienia, log, zatrzymanie i możliwość cofnięcia.


### Moduł 7 — Aktualizacja wiedzy po nowej decyzji

#### Cel i rezultat uczenia się

Przeprowadzić analizę wpływu zmiany CHG-01 bez utraty historii i bez przedwczesnego zastosowania reguły. Rezultatem jest tabela wpływu, plan aktualizacji i wersja procedury obowiązująca od wskazanej daty.

#### Instrukcja krok po kroku

1. Przeczytaj SP-07. Bez AI wypisz: co zastępuje, co uzupełnia i co pozostaje bez zmian.

2. Zaznacz dzień analizy 8 września oraz datę wejścia 21 września, 09:00.

3. Zbuduj tabelę: element | wpływ | źródło | działanie | właściciel | moment.

4. Poproś AI o niezależną analizę wpływu na kontekst, wymagania, model, procedurę, testy, komunikację i pomiar.

5. Porównaj listy. Odrzuć wpływy bez źródła.

6. Przygotuj plan aktualizacji zachowujący starą wersję i stan przyszły.

7. Opcjonalnie użyj SP-08 do trzech prób po wejściu zmiany.

#### Kryteria oceny

autorytet i data są jawne;

stan 8 i 21 września są rozdzielone;

zachowano niezmienione reguły;

lista wpływu obejmuje artefakty i zachowania;

nie wymyślono SLA, integracji ani priorytetyzacji między kolejkami;

historia pozostaje dostępna;

plan wskazuje kolejność i właścicieli działań.

#### Ścieżka podstawowa

Wypełnij tabelę wpływu dla pięciu elementów: kontekst, wymaganie gotowości, model, procedura i testy.

#### Rozszerzenie

Użyj SP-08. T-01 powinno prowadzić do propozycji Standard; T-02 nadal zatrzymuje konflikt modelu; T-03 zatrzymuje brak potwierdzenia poziomu. Następnie zmień tylko datę T-03 na 8 września i wyjaśnij różnicę.


### Moduł 8 — Ocena rezultatu AI i osobisty plan zastosowania

#### Cel i rezultat uczenia się

Ocenić realny rezultat z warsztatu według jawnej rubryki i zaprojektować mały eksperyment we własnej pracy. Rezultatem jest karta oceny, poprawiona wersja oraz plan 30-dniowy dla jednego zastosowania.

#### Instrukcja krok po kroku

1. Wybierz jeden rezultat, którego rzeczywiście użyłeś w poprzednich ćwiczeniach.

2. Oceń go samodzielnie w skali 0–2 dla siedmiu kryteriów.

3. Poproś AI o ocenę według tej samej rubryki wraz z cytatem lub wskazaniem fragmentu.

4. Porównaj oceny i rozstrzygnij różnice na podstawie źródeł.

5. Popraw jeden błąd o największym wpływie. Oceń wynik ponownie.

6. Wybierz jedno własne zastosowanie AI: niskie ryzyko, możliwe do sprawdzenia, powtarzalne.

7. Zapisz: cel, dane, zakres, kryteria, miarę, częstotliwość przeglądu i warunek zatrzymania.

#### Kryteria oceny

oceny mają dowód w wyniku lub źródle;

niepewność jest nazwana;

poprawka dotyczy błędu o znaczeniu biznesowym;

miara obejmuje jakość obok czasu;

plan ma zakres i warunek zatrzymania;

wiadomo, kto przegląda wynik;

zastosowanie jest małe i możliwe do odwrócenia.

#### Ścieżka podstawowa

Oceń jeden rezultat, popraw jeden błąd i przygotuj plan jednego zastosowania na 30 dni.

#### Rozszerzenie

Porównaj dwie wersje rezultatu lub dwa modele, zachowując identyczny kontekst i rubrykę. Nie wyciągaj wniosku o ogólnej przewadze narzędzia na podstawie jednej próby.


## Podsumowanie pracy

Zapisz: źródło, które zmieniło wynik; poprawkę po kontroli; decyzję wymagającą człowieka; jedno zastosowanie we własnej pracy.
