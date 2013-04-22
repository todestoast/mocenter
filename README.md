mocenter
========

Metal Only Center
Date: 22.04.2013
Author: Sebastian Junger
e-mail: sebi@tuximail.de
Homepage: http://www.tuximail.de
Blog: https://tuxiblog.wordpress.com
Licence: WTFPL (http://www.wtfpl.net/)


Dieses Script ermoeglicht das Abspielen des Radiostreams von metal-only.de, sowie das Anzeigen des Sendeplans.
Homepage von metal-only: http://www.metal-only.de

Abhaengigkeiten: w3m,curl,git,streamripper,mplayer

Hilfe Menü
 Verwendung: metal-only -parameter / --longparameter
Parameter:
 -r / --record * [Aufnahme des streams für festgelgte Zeit *]
'*' ist hierbei durch die Zeit zu ersetzen: *m *s *h [*m = *minuten; *s = *sekunden; *h = *Stunden]
-x / --exit [Beenden des Scripts nach dem Ausführen der vorangegangenen Parameter]
Parameter hinter -x werden nicht mehr Berücksichtigt!
-h / --help [Zeigt dieses Menü an]
-p / --plan [Zeigt den wöchentlichen Sendeplan von Metal Only an]
-pr / --playrecord [Spielt die zuvor mit -r aufgenommene Sendung ab]
Kann nicht verwendet werden, wenn keine Sendung mit -r aufgenommen wurde!
-hp / --homepage [Ruft die Startseite www.metal-only.de im Standardbrowser auf]
-v / --version [Zeigt die Nummer der Version und deren Änderung sowie die Kontaktdaten an]

Weitere Infos findet ihr hier: http://metalonly-forum.de/viewtopic.php?f=11&t=7414
