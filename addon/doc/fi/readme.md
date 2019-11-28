# Näppäimistön äänimerkki #

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

Valitse käytettävät asetukset menemällä NVDA:n asetuksiin ja valitsemalla Näppäimistön äänimerkit. Tästä kategoriasta voit määrittää kaikki tämän lisäosan tukemat toiminnot.

* "Ilmaise isot kirjaimet äänimerkillä, kun Caps Lock on käytössä" on
  oletusarvoisesti käytössä.

Mikäli tarvitset lisää asetuksia, avaa lisäasetusten valintaikkuna, jossa on
valittavissa seuraavat asetukset:

* Ohitettavat merkit Vaihto-näppäintä painettaessa: kaikki tässä luetellut
  merkit eivät anna äänimerkkiä, kun ne kirjoitetaan Vaihto-näppäin
  pohjassa. Escape-koodit ovat sallittuja, esim. "\t" = sarkain, "\r" =
  rivinvaihto.
* Anna aina äänimerkki näille merkeille: Lisää tähän merkit, joista haluat
  NVDA:n antavan äänimerkin. Escape-koodit ovat sallittuja, esim. "\t" =
  sarkain, "\r" = rivinvaihto.
* Valitse määritettävä äänimerkki: Voit muuttaa tässä äänimerkkien
  parametreja. Valitse haluamasi ja aseta parametrit seuraavissa
  tekstiruuduissa. Kun valittua äänimerkkiä on muutettu, NVDA toistaa sen
  tässä valintaikkunassa asetetuilla parametreilla.
* Äänimerkin korkeus: Valitun äänimerkin korkeus.
* Äänimerkin kesto: Valitun äänimerkin kesto.
* Äänimerkin voimakkuus: Valitun äänimerkin voimakkuus.
* Testaa äänimerkkiä: Tällä painikkeella voit toistaa testin nykyisiä
  parametreja käyttäen.
* Tallenna asetukset painamalla OK-painiketta tai hylkää muutokset
  painamalla Peruuta.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard

[2]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard
