# Wandoria Story


## Grundsätzliche Anforderungen
- Modular (bzw. Phasen)
- Theme -> Cyberpunk, Fantasy, Starwars
- Orientiert am Bestehen Konzept
	-  Realm System, Raumschiff System, Planeten als Farmwelt etc.
- Angabe von Dialogen, Sprechern etc.
	- Sprecher/Charaktere definieren
	- Dialoge API gerecht angeben

### Modular
Die Story soll in verschiedenen Phasen eingeteilt sein. So das es sich gut erweitern lässt und stück für Stück intigrieren lässt.

 1. **Phase | Einleitung / Turorial**
	  Hier soll der Spieler in die Grunlegenden Spielmechaniken eingeführt werden
	 
 2. **Phase | Hauptstory**
	Hier ist Platz um die Story auszuführen und Detaliert zu werden. Die Story soll so geschriben sein das sie dem Spieler Freiraum gibt selber Entscheidungen zu Treffen und sich nicht zu sehr aufzwingt
	
 3. **Phase | ...**
	Hier Ist Platz für Storyinhalte die auf die vorheringen Phasen aufbauen und mit einem Uodate kommen können.




### Theme
Der Server Spielt im Cyberpunk Style in der Zukunft. Allerdings gibt es auch Mystische Elemet in der Spielwelt. Bitte achte drauf in dem Style zu bleiben. Es dürfen gerne Ähnlichkeiten (Nicht Kopieren!) zu Starwars intigriert werden.

### Orientiert am Bestehen Konzept
Folegende Systeme sollen sowohl in die Main Story als auch in die Einführung sinnvoll intigriert werden.

 - Realm System
 - Raumschiff System
 - Planeten System
 - Dungeons
 - Clan System
 - Level System
 - ...

### Sprecher/Charaktere definieren
Jeder Sprecher/Charaktere soll in einer Liste Definiert werden. 
Die ID muss einfach ein `Integer` (Am besten einfach eine fortlaufende Zahl sein also 1, 2 ,3, etc.).
Der Name ist einfach der Name des Charakteres. Bitte hier auf groß/kleinschrebung achten. Das wird Später der Anzeigename des Charakteres. z.B. `Dodo`
Der MC Skin ist nur wichtig wenn dieser Charaktere als NPC in der Welt stehen soll. Falls dies nicht der Fall ist kann der Link entfallen (Dann bitte Bermekung einfügen). 
In der Bakcstory soll kurz der Hintergrund zu dem Charakter und mögliche ander wichtige fakten erwähnt werden.

Wichtige Infos:
- ID
- Name
- MC Skin z.B. https://namemc.com/skin/b0a99c7e7067603b 
	>Links findest du unter: https://namemc.com/minecraft-skins/tag
	
- Kurze Backstory und Beschreibung


### Dialoge API gerecht angeben
Unsere Hauseigene DialogAPI benötigt einige Daten von dir um die Dialoge vernünftig allen Spielern Anzeigen zu können und diesen das Maximale Spiel Erlebnis zu bieten.
Ein Dialog kann aus mehrer Stages Bestehen jede von denen kann einzelt gestartet werden.
Für jeden Dialog musst du folgende Daten angeben:
- Dialogname (Muss einzigartig sein) z.B. `dialog_dodo_tutorial_1`
- Sprecher (Wer Spricht den Dialog) z.B. `1`
- Die Stages
	- Text z.B. `Hallo ich bin Dodo und zeige dir heute den Server.`
	- Kann man den Dialog Skippen z.B. `TRUE` oder `FALSE`
	- Zeit nach dem man den Dialog Skippen kann in Sejunden z.B. `10`

