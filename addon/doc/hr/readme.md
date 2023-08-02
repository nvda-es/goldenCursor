# Zlatni kursor (Golden Cursor) #

* Autor: Salah Atair, Joseph Lee
* Preuzmi [stabilnu verziju][1]
* NVDA kompatibilnost: 2022.4 i novije verzije

Ovaj dodatak dozvoljava pomicati strelicu miša koristeći tipkovnicu i
spremanje pozicije miša za programe.

## Tipkovnički prečaci

* Kontrol+NVDA+L: pregled spremljenih pozicija miša za aplikaciju, ako ih
  ima. Također možeš dodijeliti geste tim pozicijama u ovom dijaloškom
  okviru. Pritiskom na dodijeljenu gestu, izvršit će se lijevi klik u
  spremljenoj poziciji.
* Šift+NVDA+l: spremi oznaku ili vrijednost za trenutačnu poziciju miša u
  trenutačno fokusiranoj aplikaciji.
* Windows+NVDA+C: promijeni jedinicu pomicanja miša.
* Windows+NVDA+R: promijeni ograničenje pomicanja miša.
* Windows+NVDA+S: uključi ili isključi izvještavanje o poziciji miša u
  pikselima.
* Windows+NVDA+J: premjesti poziciju miša na određenu x i y poziciju.
* Windows+NVDA+P: izvijesti o poziciji miša.
* Windows+NVDA+M: uključi ili isključi pomicanje miša strelicama.
* Windows+NVDA+tipke strelica (ili samo tipke strelica, ako je uključeno
  pomicanje miša strelicama): pomakni miša.

Napomena: Ove geste je moguće promijeniti u dijaloškom okviru „Ulazne geste”
pod kategorijom „Zlatni kursor”.

## Napomene

* Kad se pozicije (oznake) dijele, svatko treba koristiti istu rezoluciju
  ekrana.
* Za maksimalnu kompatibilnost, trebate maksimizirati prozore pritiskom
  kombinacije tipaka Windows+Strelica gore.
* Kad se pozicije dijele, potrebno je preimenovati postojeće vrijednosti
  pozicija.
* Formati verzije 1.x i 2.x pozicije miša nisu kompatibilni.
* Za izvođenje funkcija koje zahtijevaju korištenje tipki strelica, najprije
  isključi strelice miša.
* Tijekom brisanja spremljenih pozicija, ako više nema spremljenih pozicija,
  uklonit će se pozicije za aplikaciju.

## Verzija 6.2

* Zahtijeva NVDA verziju 2022.4 ili noviju.
* Kompatibilno s NVDA čitačem 2023.1.

## Verzija 6.1

* Zahtijeva NVDA 2021.3 ili noviju verziju.
* Sada možeš dodijeliti prečace za spremljene pozicije iz popisa
  pozicija. Kad pritisneš prečac izvršit će se lijevi klik za poziciju.

## Verzija 5.0

* Moderniziran izvorni kod dodatka kako bi bio kompatibilan s NVDA 2021.1.
* Riješeno mnogo problema sa stilom kodiranja i potencijalnih grešaka s
  Flake8.

## Verzija 4.0

* Zahtijeva NVDA 2019.3 ili noviju verziju.
* Dijaloški okvir za Golden Cursor postavke, zamijenjen je s pločom za
  Golden Cursor postavke.

## Verzija 3.3

* Unutarnje promjene, kako bi se podržala buduća NVDA izdanja.

## Verzija 3.2

* Dodatak je kompatibilan s NVDA 2018.3 (wxPython 4).

## Verzija 3.0

* U NVDA 2018.2, postavke dodatka se nalaze u novom višekategorijskom
  prozoru postavki  pod kategorijom „Zlatni kursor”.

## Verzija 2.1

* Ispravljena greška dekodiranja unikoda tijekom pokušaja brisanja naziva
  oznake.
* Sprečavanje višestrukih instanci prilikom otvaranja dijaloških okvira
  raznih dodatka.
* Poboljšan izgled popisa pozicija miša i skok na dijaloške okvire pozicija.

## Verzija 2.0

* Zahtijeva NVDA 2017.3 i noviji.
* Format datoteke pozicije nije kompatibilan s 1.x verzijama. Ako je
  pronađen format pozicije u 1.x formatu, pozicije u starom formatu bit će
  pretvorene u novi format tijekom instalacije.
* U NVDA izborniku postavki je dodan novi dijaloški okvir „Postavke dodatka
  Zlatni kursor” za definiranje jedinice pomicanja miša i za obavještavanje
  o pozicijama miša prilikom pomicanja miša.
* Promijenjene su različite poruke ovog dodatka.
* Prilikom uključivanja i isključivanja različitih postavki, više se neće
  čuti odgovarajući zvuk.
* Sad je moguće pokrenuti modus pomicanje miša strelicama, u kojem je moguće
  pomicati miša pomoću tipki sa strelicama.
* Promjene u dijaloškom okviru Popis pozicija uključuju novo ime (sad se
  zove „Pozicije miša”) i raspored, prikaz koordinata miša za vrijednost i
  prikaz imena trenutačnog programa kao dio naslova.
* U dijaloškom okviru „Pozicije miša”, pritiskom tipke Enter na spremljenu
  vrijednost, miš će se pomaknuti na spremljenu lokaciju.
* Ako se pozicija miša preimenuje, pojavit će se dijaloški okvir greške ako
  postoji vrijednost s istim imenom.
* Prilikom brisanja ili uklanjanja pozicija miša, sad je potrebno odgovoriti
  s „Da”, prije samog brisanja ili uklanjanja.
* Promjene u značajki Skok na poziciju miša uključuju novo ime (sad se zove
  „Nova pozicija miša”) i mogućnost unošenja X i Y koordinata odvojeno ili
  korištenja tipki sa strelicama gore ili dolje.
* Dijaloški okvir koji se prikazuje tijekom spremanja trenutne pozicije miša
  sada prikazuje koordinate za trenutnu lokaciju miša.
* Tijekom spremanja pozicija, ispravljena je greška gdje je NVDA ponekad
  reproducirao zvukove pogreške ako mapa pozicija ne postoji.

## Verzija 1.4

* Uklonjena je ovisnost od win32api kako bi dodatak bio kompatibilan s
  prošlim i budućim verzijama NVDA čitača.

## Verzija 1.0

* Inicijalno izdanje.

[[!tag stable dev]]

[1]: https://www.nvaccess.org/addonStore/legacy?file=goldenCursor
