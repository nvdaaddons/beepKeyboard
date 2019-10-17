# Beep Keyboard #

* Tekijä: David CM
* Lataa [vakaa versio][1]
* Lataa [kehitysversio][2]
* Yhteensopivuus: NVDA 2018.2-2019.2

Tämän lisäosan avulla käyttäjä voi määrittää NVDA:n ilmaisemaan piippaamalla
jotkin näppäimistötapahtumat.

## Ominaisuudet

Tämä lisäosa tarjoaa seuraavat ominaisuudet, joita voit käyttää NVDA:n
näppäimistötoiminnallisuuden mukauttamiseen:

* Ilmaise isot kirjaimet äänimerkillä, kun Caps Lock on käytössä: Mikäli
  tämä toiminto otetaan käyttöön, NVDA antaa äänimerkin kirjoittaessasi
  isoja kirjaimia Caps Lockin ollessa käytössä.
* Ilmaise kirjoitetut merkit äänimerkillä Vaihto-näppäintä painettaessa: Kun
  tämä toiminto on käytössä, NVDA antaa äänimerkin, mikäli kirjoitat
  merkkejä painaessasi Vaihto-näppäintä.
* Ilmaise alasjäävien näppäinten muutokset: Kun tämä toiminto on käytössä,
  NVDA antaa korkeamman äänimerkin, kun alasjäävä näppäin otetaan käyttöön
  ja matalamman äänimerkin, kun se poistetaan käytöstä. Huom: Windowsin
  Helppokäyttökeskuksessa  on sisäänrakennettu alasjäävien näppäinten
  äänimerkkitoiminto. Tämä natiivi toiminto toimii hyvin, mikäli et käytä
  kannettavan tietokoneen näppäimistöasettelua.
* Puhu alasjäävien näppäinten muutokset: Kun "Ilmaise alasjäävien näppäinten
  muutokset" on käytössä, voit ottaa käyttöön tai poistaa käytöstä
  alasjäävien näppäinten muutosten puhumisen.
* Mukautetut merkit: NVDA ilmaisee äänimerkillä kaikki lisäasetuksissa
  määrittämäsi merkit.
* Ei äänimerkkiä salasanakentissä: Tämä toiminto on oletusarvoisesti
  käytössä tietoturvariskien välttämiseksi. Poista se käytöstä, mikäli
  haluat kuulla äänimerkkejä salasanakentissä.

## Vaatimukset

Tarvitset NVDA 2018.2:n tai uudemman.

## Asentaminen

Asenna se NVDA-lisäosana.

## Käyttö

To enable or disable features, go to NVDA settings and select beep keyboard category. In that category you can configure all  supported features by this add-on.  

* "Beep for uppercases when caps lock is on" is enabled by default.

If you need more settings, open the advanced settings dialog that contains
the following options:

* Ignored characters with shift pressed: all characters here will be ignored
  to beeping when shift is pressed. Escape Sequences are allowed, e.g. "\t"
  for tab, "\r" for carriage return.
* Beep always for the following characters: set here all characters that you
  want NVDA beeps for. Escape Sequences are allowed, e.g. "\t" for tab, "\r"
  for carriage return.
* Select tone to configure: you can configure parameters for all
  tones. Select one here, and set the parameters in the next text
  boxes. When change selection, NVDA will beep for the current selected tone
  with the current parameters set in the dialog.
* Tone pitch: tone pitch for the current selected tone.
* Tone length: tone length for the current selected tone.
* Tone volume: tone volume for the current selected tone.
* Test tone: this button lets you to play a test with the current set
  parameters.
* Press OK button to save settings or cancel to discard.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard

[2]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard
