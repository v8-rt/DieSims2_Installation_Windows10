# DieSims2_Installation_Windows10
Anleitung Die Sims 2 installieren

___Vorbereitungen___

Rechtsklick auf Windows -> Windows PowerShell (Administrator) -> Fenster mit "Ja" bestätigen.
net user administrator /active:yes   eingeben, mit return bestätigen, PowerShell Fenster schließen.
Linksklick auf Windows -> Linksklick auf Benutzernamensymbol -> Linksklick auf Administrator.
Als Administrator anmelden.***


___Die Sims 2 installieren___

CD1 einlegen und warten bis CD erkannt wurde.
"Win" + "E" -> Dieser PC -> Rechtsklick auf CD-Laufwerk (mit Sims CD) -> Öffnen.
Rechtsklick auf AutoRun.exe -> "Als Administrator ausführen"
Installationsprozess (inkl. CD-Wechsel*) durchführen  -  *dabei, vor dem Bestätigen des CD-Wechsels, immer prüfen ob CD vom PC erkannt wurde (Dieser PC)
Das Hauptspiel sollte jetzt spielbar sein.


___Update durchführen // Patch installieren (notwendig für Erweiterungen)___

Nach der Installation des Hauptspiels:
http://www.mediafire.com/file/lzbxtj51r6b6e6r/TS2_update.zip/file (herunterladen)
Dateien entpacken und nach "C:\Program Files (x86)\EA GAMES\Die Sims 2" kopieren/verschieben -> bereits existierende Dateien ERSETZEN!!


___Erweiterungen installieren___

siehe "_Die Sims 2 installieren_"
falls am Ende die Meldungen CD 4 des Hauptspiels einlegen kommt, ist der Patch fehlgeschlagen (evtl ausweichen auf: 130111161557-thesims2_update.exe)
im Normalfall sollte das Spiel mit der HauptCD der zuletzt installierten Erweiterung jetzt spielbar sein.


___Administrator abmelden___
Zu normalem Benutzer wechseln, Windows PowerShell (Administrator), net user administrator /active:no


___Graphics Rules.sgr___

Falls als Grafikauflösung nur 800x600 zur Verfügung steht muss die "Graphics Rules.sgr" Datei umgeschrieben werden.
Beim Installieren jeder Erweiterung werden neue, Graphics Rules.sgr-Dateien erstellt.
Im Hauptordner der ZULETZT INSTALLIERTEN ERWEITERUNG nach "Graphics Rules" suchen.
Den Ordner mit der neuesten Graphics Rules.sgr öffnen und Graphics Rules.sgr auf den Desktop verschieben - Bsp: C:\Program Files (x86)\EA GAMES\Die Sims 2 Haustiere Fun-Collection\SP9\TSData\Res\Config
Rechtsklick -> Öffnen mit... -> Editor

-> ab Zeile 696 folgende Änderungen vornehmen:

option ScreenModeResolution
   setting $Low
      uintProp maxResWidth      1920
      uintProp maxResHeight     1080
      uintProp defaultResWidth  1920
      uintProp defaultResHeight 1080

   setting $Medium
      uintProp maxResWidth      1920
      uintProp maxResHeight     1080
      uintProp defaultResWidth  1920
      uintProp defaultResHeight 1080

   setting $High
      uintProp maxResWidth      1920
      uintProp maxResHeight     1080
      uintProp defaultResWidth  1920
      uintProp defaultResHeight 1080
end

Datei speichern und zurück in den Ordner schieben - am Bsp: C:\Program Files (x86)\EA GAMES\Die Sims 2 Haustiere Fun-Collection\SP9\TSData\Res\Config

Falls sich die Auflösung noch immer nicht ändern lässt, weitere Graphics Rules.sgr anpassen.


___Spielen___

Spiel starten, fertig. ;)

____ENDE____

.

.

.

.

.

.

.

Müll:


alle Sims deinstalliert, Ordner EAGAMES gelöscht
Neustart
Sims installiert
test
GeForce Treiber installiert
Neustart
test -> CD nicht erkannt -> neu eingelegt -> test -> ok
immernoch 800x600 -> Graphics Rules.sgr geändert (alles auf 1920x1080) -> danach ok

>>thesims2_update installiert (immer warten bis PC CD erkannt hat!)
(schließt sich automatisch??) -> Neutstart
//test->CD1->

wilde campus jahre
cd2 (1.mal nicht erkannt),2.mal,3.mal,4.mal->endlich...
"Bitte CD4" (warten bis erkannt) -> Ok -> Der Aktualisierungsprozess...bla
-> Ordner kopiert->XX

>>thesims2_update installiert 

Autorun.exe (campuslife) als Administrator (nicht 
gescheitert

->TS2 updatepack installiert (dateien überschrieben)
nochmal==>> "Die Sims 2 wurde beriets aktualisiert"
nachher test: über cmd(Admin)


https://www.youtube.com/watch?v=V2S6hudlTcw
