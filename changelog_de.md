## 0.9.45 (30.01.2022)
### Added
- Lobby: Spieleübersicht wurde um eine "Teams"-Spalte erweitert.
- Lobby: Verbessertes Nicknamen Handling in Verbindung mit Discord (in Entwicklung). Nicknamen werden In-Game immer auf den Discord Server Nick gesetzt. Erstmalige Nachfrage bei Siedler III und Siedler IV wenn sich Ubisoft, InGame oder Discordnamen unterscheiden.
- S3: Die Spielgeschwindigkeit lässt sich im Singleplayer oder im Replay mit F1-F3 anpassen.
- S4: Implementiert einen Testbranch für UBO:
```
UBO Alpha 3.0.0 (Testbranch)

Römer:
- Schild schützt nun nur noch 15 Ziele für 30 Sekunden.
- Sanitäter heilen nur noch 8 / 12 / 16 HP pro Heilung.
- Der Umriss des kleinen Tempels wurde präzisiert, sodass er nun einige Felder, die nicht tatsächlich vom Gebäude belegt wurden, nicht mehr blockt. Dadurch wird er auch minimal schneller planiert.

Wikinger:
- Der kleine Turm kostet nun nur noch 3/1.
- Der große Turm kostet nun nur noch 7/4.
- Die Burg kostet nun nur noch 12/6.
- Der Umriss des kleinen Tempels wurde präzisiert. Dadurch wird er auch etwas schneller planiert, ist aber vor allem nicht mehr ganz so sperrig zu platzieren.
- Der Förster macht nun nur noch 3 statt 5 Sekunden Pause zwischen Arbeitsgängen.

Mayas:
- Der große Turm blockt nun nicht mehr Platz für sein gesamtes Obergeschoss, sondern in einem ähnliche Rahmen wie sein ähnlich gebautes Gegenstück bei den Wikingern. Dadurch wird er auch schneller planiert.
- Der Umwandlungszauber kostet nun nur noch 14->56 Mana.
- Der HGHG Start erhält seine 8te Axt zurück (wie beim Klassischen Balancing).

Trojaner:
- Die Bäckerei kostet nun nur noch 6/3 statt 6/4.
- Die Sonnenblumenfarm steigt im Preis von 4/2 auf 6/2.
- Schwefel zu Eisen steigt im Preis von 8->32 auf 10->40.
- Schwefel und Steinminen kosten nun jeweils ein zusätzliches Brett.
- Die Ölpresse blockt nun nicht mehr sinnlos ein abgetrenntes Feld abseits des Gebäudes.
```
### Fixed
- S3: Fehler behoben, dass Siedler III manchmal nicht gefunden wurde, wenn Replays aus Settlers United heraus gestartet wurden.
- S3: Replay Dateien lassen sich jetzt auch im Windows Explorer mit "Öffnet mit Settlers United" korrekt starten.
- S4: Sprachauswahl im Launcher für Französisch und Spanisch korrigiert.

## 0.9.43 (16.01.2022)
### Fixed
- Lobby: Performance Updates, wenn eine große Zahl von Lobbies offen ist.
- S3: Fixt einen Crash beim Spielstart der unter bestimmten Umständen auftreten konnte.
- S3: Replays funktionieren in den meisten Fällen jetzt auch für Spiele, die von einem Save fortgesetzt wurden; in manchen Fällen können noch Desyncs beim Replay anschauen auftreten.

## 0.9.42 (15.01.2022)
### Fixed
- S4: Verbessert die Zuverlässigkeit beim Download, Installation und Deinstallation des HD-Patches. 
- S4: Fehlerhafte HD-Patch Installationen werden zuverlässiger erkannt und eine Neuinstallation durchgeführt.

## 0.9.41 (14.01.2022)
### Added
- S3: Implementiert ein Replay-Feature für Siedler 3 Spiele. Diese können in der Lobby unter Statistiken "📈" aufgerufen werden. Du siehst die ganze Karte und kannst auch die gegnerischen Spieler beobachten und das Replay durch Drücken von F12 vorgespulen.
- S4: Implementiert die Open-Beta des HD-Patches für Siedler IV (von @WizzardMaker | Jonas).
```
Was ist der HD-Patch?
Alles Wichtige zum HD-Patch findest du hier https://settlers4-hd.com/
Aktivierung?
Sobald du Siedler IV das nächste mal startest kannst du den HD-Patch in dem sich öffnenden Fenster aktivieren
Du kannst aber jederzeit in Settlers United in die "Einstellungen" gehen und dort auf den Reiter "Grafik". Dort findest du die Option "HD-Patch (Beta)" wo du den HD-Patch aktivieren oder auch wieder deaktivieren kannst.
Download?
Download startet erst wenn Siedler IV gestartet wird und kann einige Zeit dauern! Insbesondere wenn sehr viele den HD-Patch Downloaden kurz nach dem Release.
Vorrausetzungen?
Findest du direkt auf der Webseite - https://settlers4-hd.com/#downloads
Bekannte Probleme?
 Findest du direkt auf der Webseite - https://settlers4-hd.com/changelog.html
```
### Fixed
- S3: Die Game Settings beim Laden eines Saves werden jetzt korrekt angezeigt.
- S3: Behebt einen Fehler, wodurch das Auto-Save deaktiviert wurde, falls der Host das Spiel verlassen hat.
- S4: Das Schwertkämpfer Level 3 Icon des Kasernenmenüs der Maya/Wikinger (zusätzlich zum bereits gefixten Römer-Icon) wurde korrigiert (von MakusieQ).
- S4: Das verschobene "Erstellen" Icon auf dem Mehrspielerscreen wurde korrigiert (von MakusieQ).
- S4: Verbessert die FPS wenn der HD-Patch verwendet wird in den meisten Fällen deutlich (von @WizzardMaker | Jonas). 

## 0.9.40 (10.01.2022)
### Fixed
- S3: Behebt einen Fehler mit Kampangenfreischaltungen.
- S4: Behebt einen Fehler bei der Übertragung von Lobbydaten nachdem ein Save geladen wurde (HG??-Fehler). 
- S4: Behebt einen Fehler bei der Übertragung von Lobbydaten nachdem ein Save geladen wurde (In-Game-Time). 
- S4: Behebt einen Fehler bei der Übertragung der Statistikdaten.
- S4: Verbesserungen beim Installationsprozess der Zoom- und Hotkey-Mods.

## 0.9.39 (08.01.2022)
### Added
- S3 und S4: Verbesserungen an der API für die Matches um auch den zeitlichen Verlauf einer Partie zu analysieren.
### Fixed
- S3: Behebt einen Fehler das die Anzahl der Spieler in einer Siedler III Lobby nicht den tatsächlichen Spieleranzahlen entsprach.
- S3 und S4: Behebt einen Fehler bei der Übertragung der Statistikdaten. 

## 0.9.35 (28.12.2021)
### Added
- S3: Fügt einige Einstellungen für die Einheitensteuerung hinzu, um die Benutzerfreundlichkeit beim Wechsel zwischen den Spielen zu verbessern.
```
Diese Einstellung ist für Spieler interessant, die hauptsächlich Siedler IV spielen und nur hin und wieder Siedler III spielen. Es verändert die Einheitensteuerung, sodass sie ähnlich zu der in Siedler IV verwendeten Steuerung funktioniert. Zum Beispiel wird das Verhalten von 'STRG' und 'ALT' beim Senden von Einheiten vertauscht und Spezialisten fangen am Zielpunkt zu arbeiten an, wenn sie ohne 'ALT' gesendet wurden.
```
- S4: Implementiert UBO (UltimateOverhaul Balancing von @UltimateSpinDash) - Alpha 2.9.2
```
Anpassungen an Römischen Kampfzaubern:
Schildzauber dauert nun nur noch 40 Sekunden statt 60 Sekunden. Außerdem betrifft der Schildzauber nun (wie in 2.9.0) wieder 20 Targets statt 16.
```
### Fixed
- S3: Behebt einen Fehler, durch den Kriegsmaschinen während der Friedenszeit nirgendwo angegriffen werden konnten
- S3: Behebt einen Fehler mit einem Bugfix, die dazu führen konnte, dass Siedler stecken blieben, wenn der Bugfix aktiv war wenn ein Farmer, Winzer, Förster und Reisbauer (unter anderem) nicht aus ihrem Gebäude gekommen wäre, wenn auf dem aktuellen Anpflanzbereich ein Siedler stand.
- S4: Behebt einen Fehler, durch den der Kartenname nicht in die Spielstatistik aufgenommen wurde.
- S4: Behebt einen Fehler wodurch die Sounds nicht in der besten Qualität abgespielt wurden. (Danke an @iTrash für das Melden und Finden der entsprechenden Stelle - wir hoffen das es damit nicht zu Problemen bei der Soundwiedergabe auf einigen Systemen kommt).

## 0.9.34 (11.12.2021)
### Added
- S3: Nur bei "New Balance" - Behebt einen Fehler das (unter anderem) Farmer, Winzer, Förster und Reisbauer nicht aus ihrem Gebäude kommen wenn auf dem aktuellen Anpflanzbereich ein Siedler steht.
- S3: Nur bei "New Balance" - Geologen arbeiten nun wie Pioniere und sind nicht auf einen kleinen Arbeitsbereich beschränkt.
- S4: Turnierkartensupport für das "The Settlers 4 2v2 Tournament 2022"
```
Unter Einstellungen "⚙️" - Settlers IV - Tool findest du diese Option. Diese Option öffnet die Benutzeroberfläche zum Freischalten der Turnierkarten. 
```
- S4: HD-Patch Support Implementiert
```
Der kommende HD-Patch von WizzardMaker wird hiermit vollständig unterstützt. Der Download kann somit zukünftig auch direkt via Settlers United erfolgen.
```
### Fixed
- S4: Fixt einen Fehler wenn mehr als 9 Gebäude auf Priorität stehen (bekannt als Priobug  - bestehende Spielstände sind weiterhin betroffen).
- S4: Räumt das Installationsverzeichnis von Siedler IV etwas auf (entfernt von Ubisoft unnötig ausgelieferte fehlerhafte Dateien und fügt den Changelog der Settlers IV History Edition hinzu).

## 0.9.33 (07.12.2021)
### Added
- S4: Gleiche Zufallsvölker je Team
```
Jedes Volk erhält die gleichen Zufallsvölker. Zum Beispiel haben beide Teams 2 Römer, 1 Maya oder beide Teams 3 Wikinger. Bei gespiegelten Karten erhält jeweils die gleiche Position im gegnerischen Team das gleiche Zufallsvolk. Werden die Teams so eingestellt, dass es keine gleichen Positionen im Gegner Team gibt, wird diese Funktion nicht unterstützt.
```
- S4: Anzeige der Spielzeit in der Lobby
```
Die Spielzeit eines laufenden Siedler IV Spieles kann durch das Bewegen der Maus auf das Statussymbol "🎮" im Tooltip angezeigt werden.
```
### Fixed
- S3: Fehler beim Anzeigen der "Spieler zerstört" Nachricht behoben
- S3: Verhinderung der Meldung "Spieler zerstört" beim Zuschauerplätzen (beim Spielstart)
- S4: Behebt einen Fehler das die Endstatistik um einige Sekunden von der tatsächlichen Spielzeit abweichen konnte.
- S4: Behebt einen Fehler das der Zufallsgenerator nicht unter Tools verfügbar war.
- S4: Behebt einen Fehler bei den Ingametexten (danke an @UltimateSpinDash)
```
- Produktivität von Munitionsmanufakturen und ihren Gegenstücken ergänzt.
- Tooltip zur Völkerauswahl in der Lobby abgekürzt.
```

## 0.9.30 (05.12.2021)
### Added
- S3: Beobachter Modus: Unterschiedliche Farben für Teams auf der Minimap im Beobachtermodus.
- S3: Die verstrichene In-Game Zeit wird nun als Tooltip in der Lobby Angezeigt.
### Fixed
- S3: Die meisten Verbindungsfehler beim Beitreten und Hosten von S3-Spielen sollten nun behoben sein.
- S3: Behebt einen Fehler das UPnP im Router deaktiviert werden musste um Online zu spielen.
- S3: Behebt einen Fehler bei der Erkennung von S3 GOG-Editionen und Gold-Edition-Installationen ohne Save Ordner.
- S3: Verhinderung der Meldung "Spieler zerstört" beim Zuschauerplätzen (beim Spielstart)
- S4: Mod-API Update auf Version 1.0.0 (API Anpassungen für den kommenden HD-Patch von @WizzardMaker | Jonas)
- S4: Zoom-Mod Update auf Version 2.0.0
- S4: Hotkey-Mod Update auf Version 2.0.0  (von @WizzardMaker | Jonas und @kdsystem1337)
```
- Die Zierobjekte werden nun in der richtigen Reihenfolge durchlaufen wenn diese via Hotkey platziert werden (sowohl vorwärts als auch rückwärts).
- Die Zierobjekte starten nun zu Beginn einer neuen Partie oder nach einem Neustart der Anwendung immer beim ersten Zierobjekt.
```

## 0.9.29 (28.11.2021)
### Added
- Lobby: Es ist nun möglich auch unter älteren 32 Bit Windows Versionen die Settlers United Anwendung zu benutzen.
- Lobby: S3 Einstellungen - Option für Musik deaktivieren oder auf das gespielte Volk einzustellen.
- Lobby: S4 Einstellungen - Alle Optionen findest du nun direkt in Settlers United, dabei musst du einmalig die Einstellungen neu einstellen.
- S3: Kartenszenario - Team vs. Team Positionierung: Bei gespiegelten Random Karten gibt es jetzt die Option die Teams jeweils auf einer Seite der Spiegelachse zusammen zu positionieren.
- S3: Feature Zuschauerteam: Das erste oder letzte Team lässt sich als Zuschauerteam deklarieren. Es kann die ganze Karte sehen und nimmt nicht selbst am Spiel teil. Es müssen hierfür mindestens drei Teams auf der Karte existieren.
### Fixed
- Lobby: Behebt einen Fehler das die Installation von Microsoft Visual C++ 2015-2022 Redistributable bei der Installation nicht richtig angezeigt wurde (Es wird nun ein Fortschrittsbalken angezeigt)
- Lobby: Behebt einen Fehler das ausstehende Windows Updates die Installation verhinderten.
- S3: Bei New Random Balancing erhalten Asiaten jetzt auch auf gespiegelten Karten die Chance auf einen Startsumpf.
- S3: Einstellungen waren unbeabsichtigt nicht verfügbar wenn keine Installation von Siedler IV vorhanden war.
- S4: Editor+ sollte nun wieder funktionieren.
- S4: Neuer Bugfix Autospeichern findet nun automatisch alle 4 Minuten statt (Erinnerung unter Siedler III  wie gewohnt alle 2 Minuten).
- S4: Neuer Bugfix Behebt ein Problem mit dem Trojanischen Marktplatz, dieser forderte die Bauarbeiter außerhalb der Baustelle an was dazu führen konnte das dieser nicht gebaut werden konnte. (Danke an @rob997)

## 0.9.28 (25.11.2021)
### Changed
- Lobby: Neustrukturierung der Einstellungen in Settlers United (Einige weitere Einstellungen folgen mit dem nächsten Update)
### Fixed
- S3: Der neue Chat sollte nun wie gewohnt funktionieren.
- S3: Behebt einen Fehler das S3 GOG und S3 GE nicht gestartet werden können.
- S3: Behebt einen Fehler das S3 Verzeichnisse nicht gespeichert werden konnten.
- S4: Behebt einen Fehler mit Plugins beim Upgraden von einem vorherigem Launcher
- S4: BlueByte Standardkarten sind nun immer sichtbar.
- S4: Der FE "Tiling: Out of Links" sollte nun nicht mehr auftreten.

## 0.9.27 (21.11.2021)
### Added
- S3: Neu  Zoom  (reinzoomen, rauszoomen) (abschaltbar in den Einstellungen)
- S3: Neu neuer Chat  (HD, Scrollfähig) (immer bei Zoom aktiviert, abschaltbar in den Einstellungen)
- S3: Neu Möglichkeit der Positionierung der Spielzeit von unten rechts nach oben rechts (aktivierbar in den Einstellungen)
- S3: Neu  zusätzliche Hotkeys  (analog zu bestehenden Standard-Hotkeys aus S4) (abschaltbar in den Einstellungen)
```
zusätzliche Hotkeys
ESC = Einheiten und Gebäude abwählen oder Spiel speichern/ Beenden-Menü öffnen
POS1 / HOME = Kamera auf den Startpunkt setzen und den Zoom auf Standard zurücksetzen (100%)
H = Kamera auf den Startpunkt setzen
N = Zoom auf Standard zurücksetzen (100%)
F6 = Spielermenü öffnen
SHIFT = Beim platzieren von Gebäuden bleibt das Gebäude ausgewählt (Zusätzlich)
```
### Fixed
- Lobby: Die Installation und Updates sollten in den meisten Fällen nun ohne einen Rechnerneustart funktionieren.
- Lobby: Es werden zuerst offene Spiele angezeigt (erst S3 - dann S4). Es werden anschließend laufende Spiele angezeigt (erst S3 - dann S4). Außerdem werden nun auch Saves bei S4 hervorgehoben durch "Save: Mapname (Settings)"
- Lobby: Die derzeit ausgewählte Statistik wird optisch hervorgehoben. (Lokale) Gespeicherte Statistiken können nun gelöscht werden.
- S3: Behebt einen Fehler der ALT+TAB und die Windows Taste blockierte
- S4: Behebt einen Fehler beim Umwandlungszauber von Waren (bspw. Fisch zu Stein oder Stein zu Eisen)
- S4: Behebt einen Fehler das beliebige Spieleinstellungen in der Save-Lobby angezeigt werden.
- S4: Sprache und Anzeigemodus können in den Einstellungen ausgewählt werden (analog zu Siedler III)

## 0.9.26 (16.11.2021)
### Added
- Lobby: Differenzielle Updates (ab dieser Version sollte das Updaten deutlich schneller gehen, es werden nur noch die geänderten Inhalte heruntergeladen).
- S4: Implementiert UBO (UltimateOverhaul Balancing) - Alpha 2.9.1
```
Römer Anpassungen
- Schildzauber betrifft nur noch 16 targets statt 20
- Barbaren Bekehren kostet nur noch 30->120 statt 35->140, hat aber Reichweite 8 statt 4, sodass man zuverlässig die 6 targets  trifft
- Sanis haben nur noch 12/18/24 heal auf T1 bis T3 statt 18/24/30
```
### Fixed
- S4: Neues Spiel erstellen - Singleplayer "Buttons und Aufbau" angepasst.
- S3 und S4: Firewall Regeln optimiert

## 0.9.25 (15.11.2021)
### Fixed
- S3: funktioniert jetzt korrekt mit unterschiedlichen DPI Einstellungen (bspw. 125%, 150% oder auch 200%) (gemeldet von @Roxy und @v0lt669)
- S3: Beim Hosten einer S3 Setmap lassen sich jetzt Zufallspositionen aktivieren/deaktivieren (gemeldet von @Greg0ree)
- S3: Beim Window-Mode ist Auflösung in den Pre-Game Screen angepasst (Gemeldet von kdsystem1337)
- S3: Startwaren können jetzt im der Lobby ausgewählt werden (HG/MG/LG)
- S3: Weitere Optimierungen für den neuen S3 Netzwerkcode "New Network Code" vorgenommen (ein finaler Test steht noch aus, aber es sieht gut aus!)
- S3: Einzelspielerkarten und Saves ab Version 0.9.25 sollten sich in den meisten Fällen wieder funktionieren. (Bei Problemen bitte alle alten Saves löschen) (Gemeldet von @Hirschilein, @mavmav und weiteren)

## 0.9.24 (09.11.2021)
### Added
- Lobby: Mit dem heutigen Update wird der intrigierte Discord Client ausblendbar! Emfohlen für alle die Discord bereits installiert haben. Hierzu werdet ihr zunächst gefragt: Ob ihr den Discord Chat hier eingebettet haben wollt? Die Option "ICH BENUTZTE DIE DISCORD APP" sorgt dafür, dass das Windows Fenster Feature wieder funktioniert (sowohl verschieben als auch "Maximieren" durch an den Bildschirmrand schieben)
### Fixed
- S3: Es wird nun nach einen Neueinloggen der Server-Nickname verwendet (anstelle des Discord-Accountnamen)
- S3: Es sollte nun nicht mehr zu fehlerhaften S3_Multi.exe Ersetzungen bei der GE / GOG Version kommen.
- S3: Es sollten nun alle S3 Setmaps wieder korrekt enthalten sein.
- S3: Es sollte mithilfe des Window (Fullscreen) Modes eine höhere Stabilität erreicht werden.

## Erster Release
### Lobby (von Knogger, JHNP,  WizzardMaker & kdsystem1337)
- Webseite mit Twitch Streams (von Knogger)
- Mapbase mit automatischem Map-Download für S3 & S4 für den Host und Mitspieler (von Knogger & kdsystem1337)
- Game Integration (von JHNP)
- Statistiken Anzeigen und Posten (auch im Spiel möglich)  (von Knogger, JHNP & kdsystem1337)
- Icon/Logo (von WizzardMaker)
- Einstellungen "⚙️" (von kdsystem1337)

### Siedler III (Version 3.20)
#### Generelle Verbesserungen (von JHNP)
- Unterstützung für die S3:Gold Edition, S3:Ultimate Collection (GOG.com) und die S3:History Edition 
- Rendering im "Vollbild (Fenstermodus)" und "Fenstermodus" möglich
- Rendering Performance verbessert und Netzwerk-Verzögerung signifikant reduziert
- Fügt Zoom hinzu
#### Überarbeitungen (von JHNP)
- Neuer Statistikdialog mit HD Grafiken, zusätzlichen Informationen und Team Statistiken
- Neuer Chat mit Scrolling
- Zusätzliche Hotkeys
#### Bug Fixes (von JHNP)
- Fixt einen Bug, wodurch Objekte ab einer gewissen Höhe nicht mehr dargestellt wurden
- Fixt einige Game Crashes (Rendering bezogen)
- Fixt einige Amazon Gebäudebugs, bei denen Bauarbeiter feststeckten und neues Baumaterial nicht mehr angeliefert werden konnte (Fischerhütte & großer Turm)
- Fixt einen Bug, wodurch das Spiel beim Drücken von ALT+F4 weiterhin im Hintergrund aktiv war
-  Nur bei GameMode "New Random Balancing" aktiv
```
Behebt einen Fehler das (unter anderem) Farmer, Winzer, Förster und Reisbauer nicht aus ihrem Gebäude kommen wenn auf dem aktuellen Anpflanzbereich ein Siedler steht.
Geologen arbeiten nun wie Pioniere und sind nicht auf einen kleinen Arbeitsbereich beschränkt.
```
#### Game Modes
Zur Erinnerung  die Optionen sind Optional und können vom Lobby Host im Spiel ausgewählt werden.
"Transportlimit erhöhen": Dies erhöht das Transportlimit deutlich. 
"Geschwindigkeit": Anpassung der Spielgeschwindigkeit
"New Random Balancing" (von Suma & Senna)
```
Allgemeines:
- Wahrscheinlichkeit für Teiche und Seen nahe der Kartenmitte erhöht. Die Größe der Seen variiert stark und nicht alle Seen werden über Flüsse verfügen
Asiaten:
- Minen sind verbessert: 20% weniger Wartezeit vor einem Minengang, 40% für Goldminen; Minenarbeiter verrichten einen zusätzlichen Minengang je verspeister Nahrung
- Schildzauber macht nun immun gegen andere Kampfzauber (Bekehren, Bann, Bögen bestrafen, Einfrieren, Ängstigen) und hebt negative Effekte auf (Einfrieren, Ängstigen) und die Kosten sind reduziert von 20 auf 15 Mana
- Fischzauber hat reduzierte Kosten (von 10 auf 4 Mana)
- haben eine sehr hohe Wahrscheinlichkeit auf ein wenig Sumpf nahe ihrer Startposition
- Kosten des kleinen Turmes sind reduziert von 3 auf 2 Bretter
Ägypter:
- Soldatenaufwertung der erfordert weniger Mana (L3 nach 80 statt 110 Mana)
- Leicht erhöhte fangrate für Fischer

Für weitere Details, siehe https://bit.ly/3wi9I5E
```
#### Kartenszenario
"Gleiche Zufallsvölker je Team": Zufallsvölker werden so ausgelost, das jedes Team die gleichen Völker erhält.
"Team vs. Team Positionierung": Bei gespiegelten Random Karten gibt es jetzt die Option die Teams jeweils auf einer Seite der Spiegelachse zu positionieren.
#### Regeln
Friedenszeit einstellen (L2 oder 35/60/90/100min)
Diebe einstellen (ob und wenn ja wie gestohlen werden darf)
Kriegsmaschinen deaktivieren
#### Zuschauer
"Zuschauerteam": Das erste oder letzte Team lässt sich als Zuschauerteam deklarieren. Es kann die ganze Karte sehen und nimmt nicht selbst am Spiel teil. Es müssen hierfür mindestens drei Teams auf der Karte existieren.
### Siedler IV (Version 3.10)
#### Bug Fixes (von JHNP)
- Fixt einen Bug, bei dem die Baustelle nicht fertiggestellt wurde ("Pflöcke" Bug), oder keine Bauarbeiter zur Baustelle kamen
- Fixt einen Bug, bei dem Planierer die Arbeit an der Baustelle nicht beendeten und somit die Bauarbeiten aufhielten
- Fixt einen Bug, bei dem Waren manchmal nicht von gestoppten Gebäuden abtransportiert wurden
- Fixt einen Bug, wodurch Lagerstapel unbenutzbar wurden, nachdem ein Güterumwandlungszauber verwendet wurde.
- Fixt einen Bug, das der trojanische Marktplatz nicht zuverlässig gebaut werden konnte.
- Fixt einen Bug, wenn mehr als 9 Gebäude auf Priorität stehen (bekannt als Priobug).
- Fixt einen Bug, wodurch das Spiel des Hosts in der Spiellobby zum Absturz gebracht werden konnte.
- Fixt einen Bug, der einen Fatal Error: Tiling: Out of Links produziert hat.
- Fügt Desync-Schutz hinzu: Spieler, die nicht die gleiche S4 Version wie der Host verwenden, können sich nicht mehr auf "Bereit" setzen und erhalten einen Warnhinweis
#### Game Integration (von JHNP)
- Spiele werden in der Lobby angezeigt und  können von dort aus beigetreten werden.
- Es kann Spielen, die mit der S4:History Edition erstellt wurden, beigetreten werden. In diesem Fall sind jedoch alle Bug-Fixes und sonstige Spieländerungen (Game-Modi) nicht aktiv.
- Wenn ein Spiel mit der Settlers United Version erstellt wurde, erhalten alle S4:History Edition Nutzer einen Warnhinweis.
#### Neue Spiel UI (von kdsystem1337)
- Der Statistik Dialog wurde neu erstellt mit HD Grafiken, ist nun sortiert nach Punkten und enthält zusätzliche Informationen wie die Soldatenverteilung Nach Leveln oder viele weitere Wirtschaftsstatistiken.
#### Game Modi "⚖️"
Game Modi können vom Lobby Host im Spiel angeschaltet werden. Standardmäßig, sind keine Game-Modi aktiv, nur Bug-Fixes sind immer aktiv.
- Anpassung des Siedlerlimits unabhängig von der Spieleranzahl (von Sc0uty)
- Erhöhung des Transportlimits (von nyfrk & kdsystem1337)
- Gleiche Zufallsvölker je Team (Jedes Team erhält die gleichen Zufallsvölker) (von JHNP)
- Anpassung der Spielgeschwindigkeit (von Sc0uty)
- Balancing: Community Patch (vom CP-Team) & Ultimate Overhaul Balancing (von UltimateSpinDash) - siehe angepinnte Nachrichten
### Neue Spielsteuerungseinstellungen (von JHNP)
Fügt zwei neue Spielsteuerungseinstellungen für Priester hinzu, die jeder für sich aktivieren kann, um die Einheitensteuerung feizujustiern.
- Ausschalten der Auswahl von Priestern als Teil von militärischen Einheitengruppen: Wenn Soldaten ausgewählt werden, werden Priester nicht mehr automatisch mit ausgewählt. Stattdessen müssen diese explizit einzeln angeklickt werden oder über eine Einheitengruppe (1-9) angesprochen werden.
- Automatische Zauberabwahl nach dem Wirken: Wurde ein Zauber gewirkt, wird der Zauber automatisch abgewählt, so dass er nicht versehentlich mehrfach gewirkt wird.
#### Verschiedenes
- Der Hinweiston wurde ersetzt mit dem "BING" Ton der Gold Edition (von King Jo und Adrian | akulisch)
- Der Maya Musik Bug wurde gefixt (von UltimateSpinDash)
- Verbesserte Tooltips (von UltimateSpinDash)
- Das Schwertkämpfer Level 3 Icon des Kasernenmenüs der Römer/Maya/Wikinger wurde korrigiert (von MakusieQ)
