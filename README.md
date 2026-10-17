# NEPTUN — dokumentacja projektu

Dokumentacja projektu **NEPTUN** prowadzonego w ramach przedmiotu Realizacja projektu informatycznego (2026/2027), Politechnika Gdańska, Wydział ETI, Katedra Inżynierii Oprogramowania.

Zespół **PON8-A1**: Kamil Łapacz, Wiktor Tężycki, Bartłomiej Chociaj.

NEPTUN to system przetwarzania języka naturalnego, który w archiwalnych polskich opisach badań TK odnajduje incydentalne guzki płuca (IPN), wyodrębnia ich cechy i przypisuje kategorię ryzyka Lung-RADS. Projekt stanowi część płucną i tekstową projektu MULTIPREVENT realizowanego przez Gdański Uniwersytet Medyczny. Docelowe miejsce wdrożenia: Uniwersyteckie Centrum Kliniczne w Gdańsku.

To repozytorium zawiera **wyłącznie dokumentację przedmiotową**: raporty etapowe, prezentacje i notatki ze spotkań. Kod, dokumentacja techniczna i materiały merytoryczne znajdują się w osobnym, prywatnym repozytorium zespołu.

## Zasada nadrzędna

Projekt pracuje na opisach badań rzeczywistych pacjentów. **Żaden dokument w tym repozytorium nie zawiera tekstu opisów, danych pacjentów, zrzutów ekranu z danymi ani szczegółów infrastruktury, w której dane są przechowywane.** Przykłady w dokumentach są syntetyczne. Dane liczbowe podajemy w postaci zagregowanej.

## Struktura

| Katalog | Zawartość |
|---|---|
| `raporty/` | raporty etapowe RPI (`.docx` oraz eksport `.pdf`) |
| `prezentacje/` | prezentacje na zajęcia i spotkania z opiekunem |
| `spotkania/` | notatki ze spotkań zespołu i z opiekunem |

## Nazewnictwo plików

```
NEPTUN_<TYP>_<Tytuł>_v<X.Y>_<RRRR-MM-DD>.<rozszerzenie>
```

`TYP`: `RAP` (raport), `PRE` (prezentacja), `NOT` (notatka), `SPT` (notatka ze spotkania), `WYT` (wytyczne).

Wersja: `X` rośnie przy oddaniu dokumentu, `Y` przy zmianach roboczych.

```
NEPTUN_RAP_Organizacja-i-infrastruktura_v1.0_2026-10-17.docx
NEPTUN_SPT_Spotkanie-z-opiekunem_v1.0_2026-10-24.md
```

Nazwy plików nie zmieniają się po oddaniu dokumentu. Nowa wersja to nowy plik, poprzedni zostaje w repozytorium.

## Dokumenty

| Dokument | Wersja | Data |
|---|---|---|
| Organizacja i infrastruktura projektu | 1.0 | 2026-10-17 |
