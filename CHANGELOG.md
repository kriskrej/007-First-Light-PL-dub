# Changelog

## Paczka do kopiowania - 28.10.2026

- Gotowe pliki `Runtime` oraz krótka instrukcja kopiowania zamiast instalatora.
- W załączniku dla graczy brak EXE, BAT, CMD i skryptów.
- Nagrania pozostają w wersji 1.0.0; zmiana dotyczy sposobu dostarczenia.

## 1.0.0 - kompletne

- Końcowe poprawki po odsłuchu: zaakceptowane polskie CIVUKF05 i CIVEEF01, poprawiony tekst CIVVTM01, dwie kwestie CIVMRM03 zachowane w oryginale.
- 38 478 polskich nagrań, samodzielny instalator Windows i odinstalowanie.
- Instrukcja dla graczy na początku README oraz osobna paczka w Releases.
- Nowy adres repozytorium: https://github.com/kriskrej/007-First-Light-PL-dub.


## 0.9.0-rc1 - przygotowanie 2026-10-21

- Instalator odbiorcy odtwarza teksty z lokalnych oryginałów, dobiera wolne patche i używa dziennika z rollbackiem. Ta sama wersja instaluje się jednokrotnie; blokada zapobiega równoległym operacjom.
- Trwały i atomowy zapis opłaconego WAV przed potwierdzeniem w ledgerze; wcześniejszy plik pozostaje poprawny przy błędzie zapisu.
- Zawężenie płatnej generacji do jawnej listy zasobów; osobna kontrola pojedynczych, przejrzanych zmian modelu bez automatycznej pętli kolejnych wersji.
- Domknięcie większości ostatnich dialogów NPC z tekstem; dalsze reakcje bez napisów wyłączone z produkcji.

## Historia przygotowań

- Uporządkowana publikacja kodu narzędzi i dokumentacji.
- Oddzielne patche RPKG, kontrola zgodności i odczytu po zapisie.
- Dziennik instalacji, rollback oraz odzyskiwanie przerwanych operacji.
- Obsługa oficjalnego PL, wielosegmentowych dialogów i markerów WEM.
- Wznawialna produkcja z cache i limitami płatnych żądań.
- Odczyt pojedynczych wypowiedzi zapisanych w polu `dialogue` historii API; zapisany identyfikator żądania ma pierwszeństwo przed podobieństwem tekstu, a niejednoznaczne wyniki pozostają wstrzymane bez ponownej płatnej generacji.
- Kolejka pierwszych wersji nakłada oczekiwanie na jedną następną generację na lokalne kodowanie, zachowując pojedyncze płatne żądanie naraz.
- Ponowne wykorzystanie polskiego nagrania po dowodzie identycznego oryginalnego PCM, zgodności aktora i castingu; każdy cel zachowuje własne markery.
- Kontrola zachowanych fragmentów oryginalnego audio próbka po próbce.
- Dekodowanie pojedynczego przebiegu zasobów z pętlą smpl; automatyczne odtworzenie niezgodnego cache wyłącznie ze źródła o sprawdzonej sumie kontrolnej.
- Osobne raportowanie pokrycia korpusu z napisami i dodatkowych nagrań bez tekstu; pełny procent gry pozostaje nieustalony.
- Korekta kolejności markerów cue/LIST; 19.10.2026 potwierdzono w grze działanie ust przez całą rozmowę z Q w laboratorium.
- Próbka dubbingu w grze dostępna z README na YouTube.
- Uzupełnienie komend obsługiwanych przez wrapper PowerShell.
- Walidacja konfiguracji przed otwarciem SQLite i uniezależnienie testów od prywatnego workspace.
- Dokumentacja instalacji, zgodności, testowania, licencji i znanych problemów.

Wcześniejsze wpisy opisują przygotowanie przed publikacją 1.0.0.
