# Beep Keyboard #

* Autore: David CM
* Download [stable version][1]
* Download [Development version][2]
* Compatibilità NVDA: da 2018.2 a 2019.2

Questo componente aggiuntivo consente all'utente di configurare NVDA per
emettere un segnale acustico in base ad alcuni eventi della tastiera.

## Caratteristiche

Segue l'elenco delle caratteristiche di questo componente aggiuntivo:

* Segnale acustico per lettere maiuscole quando il blocco maiuscole è
  attivo: se questa funzione è abilitata, NVDA emette un segnale acustico
  quando si digita una maiuscola e il blocco maiuscole è attivo. Basta con
  le maiuscole sbagliate!
* Segnale acustico per i caratteri digitati quando si preme il tasto Maiusc:
  con questa funzione NVDA emetterà un segnale acustico se si digita un
  carattere con il tasto Maiusc premuto.
* Segnale acustico per modifiche su tasti con funzione di interruttore: con
  questa funzione, NVDA emetterà un segnale acustico più alto se
  l'interruttore è su acceso e un tono più basso se spento. Si noti che
  Windows ha una funzione di attivazione / disattivazione dei segnali
  acustici dei tasti integrata nel Centro accesso facilitato. Questa
  funzione nativa lavora bene se non si utilizza il layout impostato su
  laptop.
* Annuncia le modifiche dei tasti interruttore: opzione valida solo se la
  funzione di emissione beep per i tasti interruttore è attiva. NVDA
  annuncerà lo stato degli interruttori quando vengono modificati.
* Segnale acustico per caratteri specifici: NVDA emetterà un segnale
  acustico per tutti i caratteri definiti nelle impostazioni avanzate.
* Disattiva segnali acustici nei campi password: questa funzione è abilitata
  per impostazione predefinita per evitare rischi per la
  sicurezza. Disabilitarla se si desidera ascoltare segnali acustici nei
  campi password.

## Requisiti

è necessario possedere NVDA dalla versione 2018.2 in poi

## Installazione

Basta installarlo come un normale componente aggiuntivo di NVDA.

## Utilizzo

Per abilitare o disabilitare le funzionalità, accedere alle impostazioni di NVDA e selezionare la categoria beep tastiera. 

* "Bip per maiuscole quando il blocco maiuscole è attivato" è abilitato per
  impostazione predefinita.

Se hai bisogno di più impostazioni, apri la finestra di dialogo delle
impostazioni avanzate che contiene le seguenti opzioni:

* Caratteri ignorati con Maiusc premuto: saranno ignorati tutti i caratteri
  digitati con il tasto Shift premuto. Sono consentite sequenze di escape,
  ad es. "\t" per tab, "\r" per a capo.
* Emetti sempre un segnale acustico per i seguenti caratteri: imposta qui
  tutti i caratteri per i quali vuoi che venga emesso un segnale acustico da
  NVDA. Sono consentite sequenze di escape, ad es. "\t" per tab, "\r" per a
  capo.
* Seleziona tono da configurare: è possibile configurare i parametri per
  tutti i toni. Selezionane uno qui e imposta i parametri nelle caselle di
  testo successive. Quando si cambia la selezione, NVDA emetterà un segnale
  acustico per il tono attualmente selezionato con i parametri correnti
  impostati nella finestra di dialogo.
* Altezza tono: pitch del tono per il tono selezionato.
* Lunghezza tono: lunghezza del tono per il tono selezionato.
* Volume tono: volume tono per il tono selezionato.
* Tono di prova: questo pulsante consente di eseguire un test con il set di
  parametri corrente.
* Premere il pulsante OK per salvare le impostazioni o annulla per uscire
  senza salvare.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard

[2]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard
