# Klawiatura dźwiękowa #

* Autor: David CM
* Pobierz [Wersja stabilna][1]
* Pobierz [wersja rozwojowa][2]
* Zgodność z NVDA: od 2018.2 do 2019.2

Ten dodatek pozwala użytkownikowi skonfigurować NVDA do sygnałów dźwiękowych
z niektórymi zdarzeniami klawiatury.

## Funkcje

Ten dodatek udostępnia następujące funkcje, za pomocą których można
dostosować zachowanie klawiatury NVDA:

* Sygnał dźwiękowy dla wielkich liter, gdy Caps Lock jest włączony: jeśli ta
  funkcja jest włączona, NVDA będzie emitować sygnał dźwiękowy podczas
  wpisywania wielkich liter i caps lock jest włączony. Nie popełniaj więcej
  błędów pisanych wielkimi literami!
* Sygnał dźwiękowy dla wpisanych znaków po naciśnięciu Shift: dzięki tej
  funkcji NVDA będzie emitować sygnał dźwiękowy, jeśli wpiszesz znak z
  wciśniętym Shift.
* Sygnał dźwiękowy dla zmian przełączania: dzięki tej funkcji NVDA będzie
  emitować wyższy sygnał dźwiękowy, jeśli przełączania będzie włączony, i
  niższy ton, jeśli zgaśnie. Należy pamiętać, że system Windows ma wbudowaną
  funkcję sygnału dźwiękowego przełączania wbudowaną w Centrum ułatwień
  dostępu. Ta natywna funkcja działa dobrze, jeśli nie używasz ustawień
  układu klawiatury laptopa.
* Ogłaszaj zmiany przełączania: tylko wtedy, gdy włączony jest sygnał
  dźwiękowy dla zmiany przełączania. Możesz włączyć lub wyłączyć NVDA, aby
  ogłosić stan klucza przełączania.
* Sygnał dźwiękowy dla określonych znaków: NVDA będzie emitować sygnał
  dźwiękowy dla wszystkich znaków ustawionych w ustawieniach zaawansowanych.
* Wyłącz piszczenie w polach haseł: ta funkcja jest domyślnie włączona w
  celu wyeliminowania zagrożeń bezpieczeństwa. Wyłącz go, jeśli chcesz
  słyszeć sygnały dźwiękowe w polach haseł.

## Wymagania

Potrzebujesz NVDA 2018.2 lub nowszego.

## Instalacja

Wystarczy zainstalować go jako dodatek NVDA.

## Użycie

Aby włączyć lub wyłączyć funkcje, przejdź do ustawień NVDA i wybierz kategorię klawiatury dźwiękowej. W tej kategorii można skonfigurować wszystkie obsługiwane funkcje przez ten dodatek.  

* Opcja Sygnał dźwiękowy dla wielkich liter, gdy włączona jest Caps Lock
  jest domyślnie włączona.

Jeśli potrzebujesz więcej ustawień, otwórz okno dialogowe ustawień
zaawansowanych zawierające następujące opcje:

* Ignorowane znaki z wciśniętą zmianą: wszystkie postacie tutaj będą
  ignorowane do piszczenia po naciśnięciu shift. Sekwencje ucieczki są
  dozwolone, np. "\t" dla tab, "\r" dla powrotu karetki.
* Sygnał dźwiękowy zawsze dla następujących znaków: ustaw tutaj wszystkie
  znaki, dla których chcesz nvda emitować sygnały dźwiękowe. Sekwencje
  ucieczki są dozwolone, np. "\t" dla tab, "\r" dla powrotu karetki.
* Wybierz ton do skonfigurowania: możesz skonfigurować parametry dla
  wszystkich tonów. Wybierz jeden z nich i ustaw parametry w następnych
  polach tekstowych. Po zmianie wyboru NVDA wyda sygnał dźwiękowy dla
  bieżącego wybranego tonu z bieżącymi parametrami ustawionymi w oknie
  dialogowym.
* Ton tonu: wysokość tonu dla aktualnie wybranego tonu.
* Długość tonu: długość tonu dla aktualnie wybranego tonu.
* Głośność tonu: głośność tonu dla bieżącego wybranego tonu.
* Ton testowy: ten przycisk umożliwia odtworzenie testu z aktualnie
  ustawionymi parametrami.
* Naciśnij przycisk OK, aby zapisać ustawienia, lub anuluj, aby je odrzucić.

[[!tag dev stable]]

[1]: https://www.nvaccess.org/addonStore/legacy?file=beepkeyboard

[2]: https://www.nvaccess.org/addonStore/legacy?file=beepkeyboard
