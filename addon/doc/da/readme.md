# Bip Tastatur #

* Forfatter: David CM
* Download [stabil version][1]
* Download [Udviklingsversion][2]
* NVDA-kompatibilitet: 2018.2 til 2019.2

Denne tilføjelse giver brugeren mulighed for at konfigurere NVDA til at
bippe ved nogle tastaturhændelser.

## Funktioner

Denne tilføjelse indeholder følgende funktioner, du kan bruge til at
tilpasse tastaturets funktionsmåde, når NVDA er aktiv:

* Bip for store bogstaver, når Caps Lock er slået til: Hvis denne funktion
  er aktiveret, bipper NVDA, når du skriver et stort bogstav og Caps Lock er
  slået til. Nu kan du helt undgå at skrive med store bogstaver!
* Bip for indtastede tegn, når der trykkes på Skift: med denne funktion vil
  NVDA bippe, hvis du skriver et tegn med Shift-tasten trykket ned.
* Bip, når tilstanden for til/fra-taster ændres: Med denne funktion vil NVDA
  bippe med en højere tone, hvis en til/fra-tast slås til, og en lavere
  tone, hvis denne slås fra. Bemærk venligst, at Windows har en lignende
  funktion indbygget i indstillingerne for øget tilgængelighed. Denne
  indbyggede funktion fungerer godt, hvis du ikke bruger NVDA i
  laptop-tastaturlayout.
* Annoncér ændringer i tilstanden for til/fra-taster: Denne indstilling
  fungerer kun, hvis indstillingen "Bip, når tilstanden for til/fra-taster
  ændres" er slået til. Du kan få NVDA til annoncerer status af disse
  til/fra-taster.
* Bip altid ved brug af følgende tegn: NVDA vil bippe ved brug af alle tegn,
  som du kan indstille i tilføjelsens avancerede indstillinger.
* Deaktiver bip i adgangskodefelter: Denne funktion er deaktiveret som
  standard for at undgå sikkerhedsrisiko. Slå funktionen til, hvis du ønsker
  at NVDA bipper ved indtastning af adgangskoder.

## Systemkrav

Du skal bruge NVDA 2018.2 eller nyere.

## Installation

Installér blot filen som en NVDA-tilføjelse.

## Brug

Hvis du vil aktivere eller deaktivere funktioner, skal du gå til NVDA-indstillinger og vælge kategorien "Bip Tastatur". I denne kategori kan du konfigurere alle tilføjelsens funktioner.

* "Bip ved store bogstaver, hvis Caps Lock er slået til" er slået til som
  standard.

Hvis du har brug for flere indstillinger, skal du åbne dialogboksen
Avancerede indstillinger, der indeholder følgende indstillinger:

* Ignorerede tegn, når shift-tasten trykkes: Alle tegn i denne liste vil
  ikke bippe, når shift-tasten trykkes ned.-sekvenser er tilladt,
  f.eks. "\t" for tab, "\r" for vognretur.
* Bip altid for følgende tegn: Angiv alle de tegn, du vil have NVDA bipper
  for. Escape-sekvenser er tilladt, f. eks "\t" for tab, "\r" for vognretur.
* Vælg tone, der skal konfigureres: Du kan konfigurere parametre for alle
  toner. Vælg en her, og Angiv parametrene i de næste tekstbokse. Når du
  skifter valg, vil NVDA bippe for den aktuelle valgte tone med de aktuelle
  parametre, der er indstillet i dialogen.
* Tonens toneleje: Tonehøjde for den aktuelt valgte tone.
* Tonens længde: Længden for den aktuelt valgte tone.
* Tonens lydstyrke: Lydstyrken for den aktuelt valgte tone.
* Test tone: Denne knap lader dig afspille en lydprøve af parametrene for
  den aktuelt valgte tone.
* Tryk på OK for at gemme indstillingerne eller Annullér for at kassere.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard

[2]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard
