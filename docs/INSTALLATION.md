# Instalacja dla graczy

1. W [Releases](https://github.com/kriskrej/007-First-Light-PL-dub/releases/tag/v1.0.0) pobierz **007-First-Light-PL-dub-1.0.0-Windows-Steam.zip** z sekcji **Assets**.
2. Rozpakuj cały ZIP. Nie uruchamiaj instalatora bezpośrednio z archiwum.
3. Zamknij grę i uruchom **ZAINSTALUJ.cmd**.
4. Poczekaj na zakończenie. W grze wybierz **English** jako język audio oraz **Polski** jako język napisów.

Potrzebujesz własnej kopii 007 First Light na Steam dla Windows, build **25753571**. Instalator sprawdza lokalne pliki i odmawia zapisu przy niezgodności. Nie potrzebujesz Pythona, Wwise ani klucza API. Paczka jest instalowana ręcznie; nie używaj instalacji przez Vortex.

## Usunięcie moda

Zamknij grę i uruchom **USUN.cmd**. Usuwane są instalacje wykonane tym instalatorem; zachowane zostają wcześniejsze pliki, zapisy gry i inne mody. Nie usuwaj folderu `.007pl` z katalogu gry, ponieważ zawiera dzienniki i backupy.

## Gdy instalator nie wykryje gry

Uruchom w rozpakowanym folderze:

```powershell
.\ZAINSTALUJ.cmd --game-root "pełna ścieżka do folderu gry"
```

W Steam znajdziesz tę ścieżkę przez Właściwości gry, Zainstalowane pliki, Przeglądaj.

## Sprawdzenie plików i aktualizacje

**SPRAWDZ.cmd** sprawdza paczkę. **TEST-BEZ-ZMIAN.cmd** pokazuje plan instalacji bez zmiany gry. Ten sam pakiet można uruchomić ponownie bez tworzenia duplikatu instalacji. Przed aktualizacją gry najlepiej usuń mod dołączonym skryptem; po aktualizacji sprawdź zgodność buildu. Nie podmieniaj ręcznie całego `packagedefinition.txt` i nie usuwaj bazowych archiwów Runtime.

Pliki **Source code** w Releases służą programistom. Nie zawierają gotowego dubbingu. [Pomoc](KNOWN_ISSUES.md).
