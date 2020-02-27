# Pípajúca klávesnica #

* Autor: David CM
* Stiahnuť [stabilnú verziu][1]
* stiahnuť [vývojovú verziu][2]
* Funguje s NVDA 2018.2 do 2019.2

Umožňuje  zapnúť pípanie pri určitých klávesových skratkách.

## Vlastnosti

Dostupné sú tieto funkcie:

* Pípať pri písaní veľkých písmen s Capslockom: NVDA bude pípať, ak napíšete
  znak so shiftom a súčasne je zapnutý capslock.
* Pípať pri písaní veľkých písmen so Shiftom: NVDA bude pípať, ak s písmenom
  stlačíte súčasne shift.
* Pípať pri prepínaní Capslocku, Numlocku a iných preraďovačov: NVDA nižším
  tónom oznamuje vypnutie a vyšším zapnutie. Takto môžete mať oznamované
  zapnutie a vypnutie capslocku a numlocku. Táto funkcia je dostupná aj
  priamo v centre prístupnosti v systéme Windows. Funkcia priamo v doplnku
  lepšie funguje na rozložení desktop.
* Oznamovať prepínanie Capslocku, Numlocku a iných preraďovačov (: Ak
  zapnete pípanie, môžete si ešte nechať okrem zvukov oznamovať stav aj
  hlasom.
* Vždy pípať pri napísaní týchto znakov: NVDA bude pípať pri znakoch, ktoré
  nastavíte v pokročilých nastaveniach.
* Nepípať v heslových editačných poliach: Toto nastavenie je predvolene
  začiarknuté, aby sa predišlo bezpečnostným rizykám. Môžete ho odčiarknuť,
  ak chcete oznamovať znaky pri písaní hesiel pípaním.

## Systémové  požiadavky

Potrebujete NVDA od verzie 2018.2.

## Inštalácia

Doplnok stačí ainštalovať pomocou správcu doplnkov.

## Použitie

Nastavenia doplnku nájdete v nastaveniach NVDA, vo vetve pípajúca klávesnica.

* Predvolene je zapnuté pípanie v situáciách, ak je zapnutý capslock a
  súčasne píšete znaky so Shiftom.

Ďalšie nastavenia môžete upraviť v dialógu Pokročilé nastavenia.

* Ignorované znaky so stlačeným shiftom: Tu uveďte znaky, pri ktorých nebude
  NVDA pípať. Môžete použiť aj "\t" pre tab, "\r" pre koniec riadka.
* Vždy pípať pri napísaní týchto znakov: Tu uveďte znaky, pri ktorých bude
  NVDA pípať. môžete použiť "\t" pre tab, "\r" pre koniec riadka.
* Vyberte tón, ktorého nastavenia chcete upraviť. Môžete upraviť parametre
  pre všetky zvuky. Hodnoty zadáte v nasledujúcich editačných poliach. NVDA
  zapípa pri vybratí príslušného zvuku.
* Výška: Výška aktuálne vybratého tónu.
* Dĺžka: Dĺžka práve vybratého tónu.
* Hlasitosť: Hlasitosť vybratého tónu.
* Testovať: Prehrá zvuk s novými nastaveniami.
* Nastavenia uložíte tlačidlom OK, zahodíte tlačidlom Zrušiť.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard

[2]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard
