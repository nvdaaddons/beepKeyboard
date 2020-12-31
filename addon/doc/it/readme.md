# Beep Keyboard #

* Autore: David CM
* Scarica la [versione stabile][1]
* Scarica la [versione in sviluppo][2]
* Compatibilità con NVDA: dalla versione 2018.2 alla 2019.2

Questo componente aggiuntivo consente all'utente di configurare NVDA per
emettere un segnale acustico alla pressione di alcuni tasti della tastiera.

## Caratteristiche

Segue l'elenco delle caratteristiche di questo componente aggiuntivo:

* Segnale acustico per lettere maiuscole (n.d.t.: premute assieme al tasto
  shift) quando il blocco maiuscole è attivo: se questa funzione è
  abilitata, NVDA emette un segnale acustico quando si digita una maiuscola
  e il blocco maiuscole è attivo. Basta con le maiuscole sbagliate! (n.d.t.:
  se, quando il blocco maiuscole è attivo, si digita una lettera assieme al
  tasto shift, a video viene stampata questa lettera in minuscolo)
* Segnale acustico per i caratteri digitati insieme al tasto shift: con
  questa funzione NVDA emetterà un segnale acustico se si digita un
  carattere in contemporanea con il tasto shift.
* Segnale acustico per modifiche su tasti con funzione di interruttore
  (n.d.t.: blocco maiuscole, blocco numerico, blocco scorrimento): con
  questa funzione, NVDA emetterà un segnale acustico più alto se
  l'interruttore viene attivato e un tono più basso se viene disattivato. Si
  noti che Windows ha una funzione di attivazione / disattivazione dei
  segnali acustici associati a questi tasti integrata nel Centro accesso
  facilitato. Questa funzione nativa lavora bene se non si utilizza il
  layout impostato su laptop.
* Lettura delle modifiche ai tasti interruttore: opzione valida solo se la
  funzione di emissione beep per i tasti interruttore è attiva. Potete
  attivare o disattivare la lettura dello stato degli interruttori da parte
  di NVDA.
* Segnale acustico per caratteri specifici: NVDA emetterà un segnale
  acustico per tutti i caratteri definiti nelle impostazioni avanzate.
* Disattivazione dei segnali acustici nei campi password: questa funzione è
  abilitata per impostazione predefinita per evitare rischi per la
  sicurezza. Disabilitarla se si desidera ascoltare segnali acustici nei
  campi password.

## Requisiti

E' necessario possedere NVDA dalla versione 2018.2 in poi.

## Installazione

Basta installarlo come un normale componente aggiuntivo di NVDA.

## Utilizzo

Per abilitare o disabilitare le funzionalità, accedere alle impostazioni di NVDA e selezionare la categoria Beep Keyboard. In questa categoria potete configurare tutte le funzionalità supportate di questo add-on.

* L'opzione "Beep per lettere con shift quando il blocco maiuscole è
  attivato" è abilitata per impostazione predefinita.

Se avete bisogno di più impostazioni, aprite la finestra di dialogo delle
impostazioni avanzate che contiene le seguenti opzioni:

* Caratteri ignorati con shift premuto: saranno ignorati tutti i caratteri
  digitati insieme al tasto Shift. Sono consentite sequenze di escape, ad
  es. "\t" per tab, "\r" per a capo.
* Emetti sempre un segnale acustico per i seguenti caratteri: imposta qui
  tutti i caratteri per i quali vuoi che venga emesso un segnale acustico da
  NVDA. Sono consentite sequenze di escape, ad es. "\t" per tab, "\r" per a
  capo.
* Seleziona segnale acustico da configurare: è possibile configurare i
  parametri per tutti i segnali acustici. Selezionane uno qui e imposta i
  parametri nelle caselle di testo successive. Quando si modifica la
  selezione, NVDA emetterà un segnale acustico con i parametri appena
  impostati.
* Altezza segnale acustico: tono del segnale acustico selezionato.
* Lunghezza segnale acustico: lunghezza del segnale acustico selezionato.
* Volume segnale acustico: volume del segnale acustico selezionato.
* Prova segnale acustico: questo pulsante consente di eseguire un test con
  il set di parametri corrente.
* Premete il pulsante OK per salvare le impostazioni o annulla per uscire
  senza salvare.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard

[2]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard
