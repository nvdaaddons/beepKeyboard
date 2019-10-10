# Beep Keyboard #

* Autore: David CM
* Download [stable version][1]
* Download [Development version][2]
* NVDA compatibility: 2018.2 to 2019.2

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
