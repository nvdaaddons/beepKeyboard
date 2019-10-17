# Beep Keyboard #

* Autor: David CM
* Download [stable version][1]
* Descărcați [versiunea în dezvoltare][2]
* NVDA compatibility: 2018.2 to 2019.2

Acest supliment îi permite utilizatorului să configureze NVDA să emită
bipuri cu niște evenimente de tastatură.

## Caracteristici

Acest supliment oferă următoarele funcționalități pe care le puteți utiliza
pentru a adapta comportamentul tastaturii NVDA:

* Emite un bip pentru majuscule când caps lock-ul este activat: Dacă această
  funcție este activă, NVDA va emite un bip atunci când scrieți cu litere
  mari, iar tasta caps lock este, la rândul ei, activă. Nu mai faceți
  greșeli de majuscule!
* Emite un bip pentru caracterele tastate când tasta shift e apăsată: cu
  această funcție, NVDA va emite un bip atunci când tastați ceva și ținând
  apăsat pe shift în același timp.
* Emite un bip pentru modificările tastelor de comutare: Cu această funcție,
  NVDA va emite un bip cu o tonalitate mai înaltă dacă o tastă de comutare
  este activată și unul cu o tonalitate mai joasă dacă această este
  dezactivată. Rețineți faptul că și Windows are o astfel de funcție
  implementată în centrul Simplificare Acces. Această caracteristică nativă
  funcționează cum trebuie dacă nu aveți setat aspectul tastaturii la
  laptop.
* Anunță modificările tastelor de comutare: Numai atunci când funcția „Bip
  pentru modificările tastelor de comutare” este activă. Puteți activa sau
  dezactiva anunțarea stării tastelor de comutare de către NVDA.
* Emite un bip pentru caracterele specificate: NVDA va emite un bip pentru
  toate caracterele pe care le-ați setat în panoul setărilor avansate.
* Dezactivează bipul în câmpurile de parolă: Această caracteristică este
  activă în mod implicit pentru ca utilizatorul să nu fie expus la riscuri
  de securitate. Dezactivați-o dacă vreți să auziți bipuri în câmpurile de
  parolă, asumându-vă totodată aceste riscuri.

## Cerințe

Aveți nevoie de NVDA 2018.2 sau mai nou.

## Instalare

Instalați-l ca pe un supliment NVDA.

## Utilizare

Pentru a activa sau dezactiva caracteristici, mergeți în setările NVDA și selectați categoria Bip Keyboard. În acea categorie puteți seta toate funcțiile integrate în acest supliment.

* Emiterea de bipuri pentru majuscule atunci când tasta caps lock este în
  funcțiune este activă în mod implicit.

Dacă aveți nevoie de mai multe setări, deschideți panoul de setări avansate,
care conține  următoarele opțiuni:

* Caractere ignorate cu shift apăsat: toate caracterele de aici vor fi
  ignorate, nu se va emite bip pentru ele, când shift este
  apăsat. Secvențele de evacuare sunt permise, de exemplu "\t" pentru tab,
  "\r" pentru linie nouă.
* Întotdeauna emite un bip pentru următoarele caractere: Setați aici toate
  caracterele pentru care vreți ca NVDA să emită un bip. Secvențele de
  evacuare sunt permise, de exemplu "\t" pentru tab, "\r" pentru linie nouă.
* Selectare ton de configurat: puteți configura parametrii pentru toate
  tonurile. Selectați unul aici și setați parametrii din următoarea casetă
  de text. Când schimbați selecția, NVDA va emite un bip pentru tonul
  selectat cu parametrii pe care i-ați setat în fereastra de dialog.
* Înălțime ton: înălțimea tonului pentru tonul selectat.
* Durată ton: durata tonului pentru tonul selectat.
* Volum ton: Volumul tonului pentru tonul selectat.
* Testare ton: acest buton vă dă posibilitatea să testați setul curent de
  parametrii.
* Apăsați butonul OK pentru a salva setările sau anulare dacă vreți ca
  acestea să nu se aplice.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard

[2]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard
