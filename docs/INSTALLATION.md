# Kopiowanie polskiego dubbingu

1. [Pobierz pliki do przeniesienia](https://github.com/kriskrej/007-First-Light-PL-dub/releases/download/v1.0.0/007-First-Light-PL-dub-1.0.0-pliki-do-przeniesienia.zip) i rozpakuj ZIP. Zamknij grę.
2. Otwórz folder gry: **Steam > Właściwości > Zainstalowane pliki > Przeglądaj**.
3. Zrób poza folderem gry kopię **Runtime/packagedefinition.txt** oraz **Runtime/chunk0patch1.rpkg** i **Runtime/chunk1patch1.rpkg**, jeśli już istnieją.
4. Skopiuj folder **Runtime** z paczki do folderu **007 First Light** i zgódź się na zastąpienie trzech plików.
5. W grze ustaw **audio English** i **napisy Polski**.

ZIP zawiera tylko:

```text
INSTRUKCJA.txt
Runtime/
  chunk0patch1.rpkg
  chunk1patch1.rpkg
  packagedefinition.txt
```

Nie uruchamiasz żadnego programu ani skryptu.

Paczka jest przygotowana dla czystej instalacji Steam, build **25753571**. Nie łącz jej z innymi modami zmieniającymi te same trzy pliki. Inne wersje gry wymagają osobnego sprawdzenia zgodności.

## Cofnięcie

Zamknij grę i przywróć swoje kopie. Jeśli wcześniej nie było plików `chunk0patch1.rpkg` i `chunk1patch1.rpkg`, usuń tylko te dwa pliki. Nie usuwaj bazowych `chunk0.rpkg` ani `chunk1.rpkg`.
