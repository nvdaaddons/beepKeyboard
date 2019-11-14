# Piepton-Tastatur #

* Autor: David CM
* [Stabile Version herunterladen][1]
* [Entwicklerversion herunterladen][2]
* NVDA-Kompatibilität: 2018.2 bis 2019.2

Diese Erweiterung ermöglicht es, NVDA so zu konfigurieren, dass bei einigen
Tastaturereignissen Pieptöne ausgegeben werden.

## Funktionen

Diese Erweiterung bietet die folgenden Funktionen, mit denen Sie das
Verhalten von NVDA mit der Tastatur anpassen können:

* Piepton für Großbuchstaben, wenn die Feststelltaste dauerhaft
  eingeschaltet ist: Wenn diese Funktion aktiviert ist, gibt NVDA einen
  Piepton aus, wenn Sie einen Großbuchstaben eingeben und die Feststelltaste
  dauerhaft eingeschaltet ist. Somit machen Sie keine Rechtschreibfehler
  mehr mit Großbuchstaben!
* Piepton für eingegebene Zeichen beim Drücken der Umschalttaste: Mit dieser
  Funktion gibt NVDA einen Piepton aus, wenn Sie ein Zeichen mit gedrückter
  Umschalttaste eingeben.
* Piepton für Änderungen an den Umschaltelementen wie z.B. Kontrollfelder,
  Auswahlschalter etc.: Mit dieser Funktion gibt NVDA einen höheren Piepton
  aus, wenn eine Option eingeschaltet / aktiviert ist, und einen niedrigeren
  Piepton, wenn sie ausgeschaltet / deaktiviert ist. Bitte beachten Sie,
  dass Windows standardmäßig über eine Signaltonfunktion für
  Umschaltelemente verfügt, die in das Center für erleichterte Bedienung zu
  finden ist. Dies funktioniert besonders gut, wenn Sie die Tastaturschema
  "PC" Einstellung. Mit Tastaturschema "Laptop" ist diese Funktion nicht
  perfekt.
* Änderungen an Umschaltelementen ankündigen: nur wenn "Pieptöne für
  Änderungen an Umschaltelementen" eingeschaltet ist. Sie können diese
  Ankündigung in NVDA aktivieren oder deaktivieren.
* Piepton für bestimmte Zeichen: NVDA gibt einen Signalton für alle Zeichen
  aus, die Sie in den erweiterten Einstellungen festgelegt haben.
* Pieptöne in Passwortfeldern deaktivieren: Diese Funktion ist standardmäßig
  aktiviert, um Sicherheitsrisiken vorzubeugen. Deaktivieren Sie es, wenn
  Sie Pieptöne in Passwortfeldern hören möchten.

## Anforderungen

Sie benötigen NVDA 2018.2 oder neuer.

## Installation

Installieren Sie es einfach wie eine NVDA-Erweiterung.

## Verwendung

Um Funktionen zu aktivieren oder zu deaktivieren, gehen Sie zu den NVDA-Einstellungen und wählen Sie die Kategorie Piepton-Tastatur. In dieser Kategorie können Sie alle mit dieser Erweiterung unterstützten Funktionen konfigurieren.  

* "Piepton für Großbuchstaben bei aktivierter Feststelltaste" ist
  standardmäßig aktiviert.

Wenn Sie weitere Einstellungen benötigen, öffnen Sie den Dialog für
erweiterte Einstellungen, der die folgenden Optionen enthält:

* Ignorierte Zeichen bei gedrückter Shift-Taste: Alle Zeichen, welche hier
  eingegeben sind, werden ignoriert, sodass beim Drücken der Shift-Taste
  kein Piepton ausgegeben wird. Escape-Sequenzen sind erlaubt, z.B. "\t" für
  tab, "\r" für Zeilenumbruch.
* Piepton immer für die folgenden Zeichen: geben Sie hier alle Zeichen ein,
  für die Sie Pieptöne wünschen. Escape-Sequenzen sind erlaubt, z.B. "\t"
  für tab, "\r" für Zeilenumbruch.
* Piepton auswählen: Sie können Parameter für alle Töne
  konfigurieren. Wählen Sie hier einen Ton aus und stellen Sie die Parameter
  in den darauf folgenden Textfeldern ein. Wenn Sie die Auswahl ändern, gibt
  NVDA den aktuell ausgewählten Ton aus mit den im Dialogfeld eingestellten
  aktuellen Parametern.
* Tonhöhe: Tonhöhe für den aktuell ausgewählten Ton.
* Tonlänge: Tonlänge für den aktuell ausgewählten Ton.
* Tonlautstärke: Tonlautstärke für den aktuell ausgewählten Ton.
* Test-Ton: Mit diesem Schalter können Sie einen Test mit den aktuellen
  eingestellten Parametern abspielen.
* Klicken Sie auf "OK", um Einstellungen zu speichern, oder auf abbrechen,
  um keine Veränderungen vorzunehmen.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard

[2]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard
