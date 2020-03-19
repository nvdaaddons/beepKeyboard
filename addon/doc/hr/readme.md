# Zvučni signali za tipkovnicu (Beep Keyboard) #

* Autor: David CM
* Preuzmi [stabilnu verziju][1]
* Preuzmi [razvojnu verziju][2]
* NVDA kompatibilnost: 2018.2 do 2019.2

Ovaj dodatak dopušta korisniku konfigurirati NVDA, kako bi se koristili
zvučni signali za neke događaje na tipkovnici.

## Funkcije

Ovaj dodatak pruža sljedeće funkcije, pomoću kojih je moguće prilagoditi
način rada NVDA tipkovnice:

* Zvučni signal za velika slova kad su velika slova uključena: ako je ova
  funkcija uključena, NVDA će odsvirati zvučni signal tijekom tipkanja
  velikih slova, kad je tipkanje velikim slovima uključeno. S ovom funkcijom
  više nećeš griješiti!
* Zvučni signal za tipkane znakove kad je tipka šift pritisnuta: s ovom
  funkcijom će NVDA odsvirati zvučni signal tijekom tipkanja znakova s
  istovremeno pritisnutom tipkom šift.
* Zvučni signal za promjenu stanja preklopnih tipki: s ovom funkcijom će
  NVDA odsvirati viši zvučni signal, ako se preklopna tipka uključi, a niži
  zvučni signal, ako se isključi. Napomena: Windows ima ugrađeni zvučni
  signal za preklopne tipke u centru za olakšani pristup. Ova izvorna
  funkcija radi dobro, ako se ne koristi postavka za raspored tipkovnice na
  laptopu.
* Najavi promjene stanja preklopnih tipki: samo kad je „Zvučni signal za
  promjenu stanja preklopnih tipki” uključeno. Najavljivanje promjena stanja
  preklopnih tipki je moguće uključiti ili isključiti.
* Zvučni signal za određene znakove: NVDA će odsvirati zvučni signal za sve
  znakove koji su postavljeni u naprednim postavkama.
* Isključi zvučni signal u poljima za lozinku: ova je funkcija standardno
  isključena iz sigurnosnih razloga. Isključi signal, ako želiš čuti zvučni
  signal u poljima za lozinku.

## Preduvjeti

Potrebna je NVDA verzija 2018.2 ili novija.

## Instalacija

Instaliraj ga kao NVDA dodatak.

## Primjena

Za uključivanje ili isključivanje funkcije, prijeđi na NVDA postavke i odaberi kategoriju „Zvučni signali za tipkovnicu”. U toj kategoriji je moguće konfigurirati sve funkcije koje ovaj dodatak podržava.  

* „Zvučni signal za velika slova kad su velika slova uključena” je
  standardno aktivirano.

Ako trebaš daljnje postavke, otvori dijaloški okvir s naprednim postavkama,
koji sadrži sljedeće opcije:

* Zanemareni znakovi s pritisnutom tipkom šift: zvučni signali će se
  ignorirati za sve ovdje navedene znakove, kad je pritisnuta tipka
  šift. Dozvoljena je upotreba slijeda znakova, npr. "\t" za tabulator, "\r"
  za prekid retka.
* Uvijek odsviraj zvučni signal za sljedeće znakove: ovdje postavi sve
  znakove, za koje želiš da NVDA odsvira zvučni signal. Dozvoljena je
  upotreba slijeda znakova, npr. "\t" za tabulator, "\r" za prekid retka.
* Odaberi zvuk koji želiš konfigurirati: možeš konfigurirati parametre za
  sve zvukove. Ovdje odaberi jedan zvuk i postavi parametre u sljedećim
  tekstualnim okvirima. Prilikom promjene odabira, NVDA će odsvirati zvučni
  signal za trenutačno odabrani zvuk s trenutačno postavljenim parametrima u
  dijaloškom okviru.
* Visina zvuka: visina zvuka za trenutačno odabrani zvuk.
* Duljina zvuka: duljina zvuka za trenutačno odabrani zvuk.
* Glasnoća zvuka: glasnoća zvuka za trenutačno odabrani zvuk.
* Testiranje zvuka: ovaj gumb omogućuje sviranje zvuka s trenutačno
  postavljenim parametrima.
* Pritisni gumb „U redu” za spremanje postavki ili pritisni gumb „Odustani”
  za prekid.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard

[2]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard
