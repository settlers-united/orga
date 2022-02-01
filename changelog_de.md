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
-S3: Behebt einen Fehler mit Kampangenfreischaltungen.
-S4: Behebt einen Fehler bei der Übertragung von Lobbydaten nachdem ein Save geladen wurde (HG??-Fehler). 
-S4: Behebt einen Fehler bei der Übertragung von Lobbydaten nachdem ein Save geladen wurde (In-Game-Time). 
-S4: Behebt einen Fehler bei der Übertragung der Statistikdaten.
-S4: Verbesserungen beim Installationsprozess der Zoom- und Hotkey-Mods.

## 0.9.39 (08.01.2022)
### Added
- S3 und S4: Verbesserungen an der API für die Matches um auch den zeitlichen Verlauf einer Partie zu analysieren.
### Fixed
-S3: Behebt einen Fehler das die Anzahl der Spieler in einer Siedler III Lobby nicht den tatsächlichen Spieleranzahlen entsprach.
-S3 und S4: Behebt einen Fehler bei der Übertragung der Statistikdaten. 

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
-S3: Behebt einen Fehler, durch den Kriegsmaschinen während der Friedenszeit nirgendwo angegriffen werden konnten
-S3: Behebt einen Fehler mit einem Bugfix, die dazu führen konnte, dass Siedler stecken blieben, wenn der Bugfix aktiv war wenn ein Farmer, Winzer, Förster und Reisbauer (unter anderem) nicht aus ihrem Gebäude gekommen wäre, wenn auf dem aktuellen Anpflanzbereich ein Siedler stand.
-S4: Behebt einen Fehler, durch den der Kartenname nicht in die Spielstatistik aufgenommen wurde.
-S4: Behebt einen Fehler wodurch die Sounds nicht in der besten Qualität abgespielt wurden. (Danke an @iTrash für das Melden und Finden der entsprechenden Stelle - wir hoffen das es damit nicht zu Problemen bei der Soundwiedergabe auf einigen Systemen kommt).

## 0.9.34 (11.12.2021)
### Added
-S3: Nur bei "New Balance" - Behebt einen Fehler das (unter anderem) Farmer, Winzer, Förster und Reisbauer nicht aus ihrem Gebäude kommen wenn auf dem aktuellen Anpflanzbereich ein Siedler steht.
-S3: Nur bei "New Balance" - Geologen arbeiten nun wie Pioniere und sind nicht auf einen kleinen Arbeitsbereich beschränkt.
-S4: Turnierkartensupport für das "The Settlers 4 2v2 Tournament 2022"
```
Unter Einstellungen "⚙️" - Settlers IV - Tool findest du diese Option. Diese Option öffnet die Benutzeroberfläche zum Freischalten der Turnierkarten. 
```
-S4: HD-Patch Support Implementiert
```
Der kommende HD-Patch von WizzardMaker wird hiermit vollständig unterstützt. Der Download kann somit zukünftig auch direkt via Settlers United erfolgen.
```
### Fixed
-S4: Fixt einen Fehler wenn mehr als 9 Gebäude auf Priorität stehen (bekannt als Priobug  - bestehende Spielstände sind weiterhin betroffen).
-S4: Räumt das Installationsverzeichnis von Siedler IV etwas auf (entfernt von Ubisoft unnötig ausgelieferte fehlerhafte Dateien und fügt den Changelog der Settlers IV History Edition hinzu).
