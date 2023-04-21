# Golden Cursor #

* Autorzy: salah atair, Joseph Lee
* Pobierz [wersja stabilna][1]
* Zgodność z NVDA: 2022.4 i nowsze

Ten dodatek umożliwia ruszanie myszą za pomocą klawiatury i zapisywanie
pozycji myszy dla danej aplikacji.

## Polecenia klawiszowe

* Control+NVDA+L: wyświetlanie zapisanych pozycji myszy dla aplikacji, jeśli
  taka istnieje. W tym oknie dialogowym można również przypisać gesty do
  tych pozycji. Po naciśnięciu przypisanego gestu zostanie wykonane
  kliknięcie lewym przyciskiem myszy w zapisanej pozycji.
* Shift+NVDA+L: Zapisz tag lub oznaczenie dla aktualnej pozycji myszy w
  aktualnie otwartej aplikacji.
* Windows+NVDA+C: Zmień jednostkę ruchu myszy.
* Windows+NVDA+R: Przełącz ograniczenie myszy.
* Windows+NVDA+S: Przełącz odczytywanie pozycji myszy w pikselach.
* Windows+NVDA+J: Przesuń mysz do konkretnej pozycji x y.
* Windows+NVDA+P: Odczytaj pozycję myszy.
* Windows+NVDA+M: włącz lub wyłącz strzałki myszy.
* Windows+NVDA+klawisze strzałek (lub tylko klawisze strzałek, jeśli
  strzałki myszy są włączone): ruszaj myszą.

Uwaga! Powyższe gesty można przypisać ponownie w Zdarzeniach Wejścia NVDA, w
kategorii Golden Cursor.

## Uwagi

* Gdy użytkownicy dzielą się ze sobą pozycjami myszy (ich tagami), każdy z
  nich powinien mieć taką samą rozdzielczość ekranu.
* Dla jak największej zgodności, należy zmaksymalizować widok systemu
  naciskając Windows+Strzałka w gurę.
* Podczas dzielenia pozycji myszy, nazwy istniejących pozycji powinny zostać
  zmienione.
* Formaty pozycji myszy w wersji 1.x i 2.x są niezgodne.
* Przed wykonywaniem czynności, które wymagają używania klawiszy strzałek,
  należy wyłączyć strzałki myszy.
* Jeżeli wszystkie zapisane w dodatku pozycje zostaną usunięte, lista
  pozycji dla danej aplikacji zostanie wyczyszczona.

## Wersja 6.2

* Wymaga NVDA 2022.4 lub nowszego.
* Kompatybilny z NVDA 2023.1.

## Wersja 6.1

* Wymaga NVDA 2021.3 lub nowszego.
* Teraz możesz przypisać skróty do zapisanych pozycji z listy stanowisk. Po
  naciśnięciu skrótu zostanie wykonane kliknięcie lewym przyciskiem myszy
  dla pozycji.

## Wersja 5.0

* Zmodernizowany dodatkowy kod źródłowy, aby był kompatybilny z NVDA 2021.1.
* Naprawiono niektóre błędy stylistyczne związane z kodem,  a także
  naprawiono błędy związane z linterem Flake8.

## Wersja 4.0

* Wymaga NVDA 2019.3 lub nowszej.
* Dialogowe okno ustawień Golden Cursor zostało zmienione na panel.

## Wersja 3.3

* Zmiany wewnętrzne do wsparcia nowszych wersji NVDA.

## Wersja 3.2

* Dodatek jest zgodny z NVDA 2018.3 (wxPython 4).

## Wersja 3.0

* Jeżeli państwo używają NVDA 2018.2, ustawienia dodatku można znaleść w
  nowym wielopanelowym  dialogu ustawień w kategorii "Golden Cursor".

## Wersja 2.1

* Naprawiono błąd dekodowania unikodu podczas usuwania nazwy tagu.
* Należy zapobiegać tworzeniu się wielu instancji dodatku, podczas
  otwierania jego różnych okien dialogowych.
* Poprawiono wygląd listy pozycji myszy i okien dialogowych przeskakiwania
  do pozycji.

## Wersja 2.0

* Wymaga NVDA w wersji 2017.3 lub nowszej.
* Format pliku pozycji jest niezgodny z wersjami 1.x. Jeśli program znajdzie
  format pozycji 1.x, stare pozycje zostaną zamienione na nowy format
  podczas instalacji aktualizacji.
* Dodano nowe okno ustawień Golden Cursor do menu ustawień NVDA. Służy ono
  do konfigurowania jednostki ruchu myszy i ustawiania ogłaszania pozycji
  myszy, gdy się nią rusza.
* Zmianie uległy różnego rodzaju wiadomości w tym dodatku.
* Nie będzie już słychać dźwięku przełączania podczas zmiany ustawień.
* Dostępny jest tryb strzałek myszy, który umożliwia ruszanie myszą za
  pomocą samych klawiszy strzałek.
* Zmianom uległo okno dialogowe listy pozycji. Między innymi, zmieniono
  nazwę okna na Pozycje Myszy, a także jego układ, wyświetlanie
  współrzędnych oznaczenia, oraz pokazywanie nazwy otwartej aplikacji jako
  część tytułu okna.
* Naciśnięcie klawisza Enter na zapisanym oznaczeniu w oknie dialogowym
  Pozycje Myszy, przeniesie mysz do zapisanej lokalizacji.
* Gdy podczas zmiany pliku okaże się, że plik o takiej samej nazwie już
  istnieje, pojawi się okno błędu.
* Aby usunąć lub wyczyścić pozycje myszy, musisz potwierdzić swój zamiar
  przyciskiem Tak. Dopiero wtedy pozycje zostaną usunięte lub wyczyszczone.
* Zmiana do funkcji przeskakiwania miszy, włączając w to nową nazwę (od
  teraz się nazywa nowa pozycja myszy) a także możliwość wpisywania
  współrzędnych x i y oddzielnie lub używając strzałek.
* Dialog do zapisywania aktualnej pozycji myszy teraz pokazuje współrzędne
  dla aktualnej pozycji myszy.
* Podczas zapisywania pozycji rozwiązano problem polegający na tym, że NVDA
  może odtwarzać dźwięki błędów, jeśli folder pozycji nie istnieje.

## Wersja 1.4

* Usunięto zależność win32api, aby uzgodnić dodatek z starymi i nowymi
  wersjami NVDA.

## Wersja 1.0

* Wersja pierwotna.

[[!tag stable dev]]

[1]: https://www.nvaccess.org/addonStore/legacy?file=goldenCursor
