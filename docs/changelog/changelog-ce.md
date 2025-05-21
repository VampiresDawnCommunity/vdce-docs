 
# Changelog der "Community Edition"

## Änderungen in Version 1.2

### Bugfixes
- Einige Stellen in der Hexen-Illusion *(Everlasting Reign)* waren nicht betretbar.
- In manchen Situationen konnte es vorkommen, dass Items aus dem Inventar verschwanden, wenn diese das Maximum von 99 Stk. erreicht haben.
- Die Funktion "Alle umwandeln" der Seelenmaschine funktionierte nicht, wenn die gewählte Seele bzw. der gewählte Seelenstein das Maximum von 99 Stk. erreicht hat.
- Es konnte vorkommen, dass Asgar & Alaine nach Abschluss der Zettelquest weiterhin in Valnars Zimmer sichtbar waren.
- Eine neue Szene in der Tradan-Gruft funktionierte nicht korrekt *(Aysha-Mod)*.
- Beim ersten Verlassen der Stadt Linar war es möglich, dass das Spiel die internen Party-Slots durcheinander brachte *(Valaine-Mod)*.
- Quest Menü: Einige der Quest-Einträge für die Könige verwendeten falsche Variablen & zeigten daher den falschen Text im Questlog an *(Everlasting Reign)*.

### Neue Features

- Zwei neue Bonus-Musikstücke von Zippo wurden hinzugefügt (Kampfmusik & Wolkenmusiker).
- Diverse Faceset-Grafiken wurden ausgetauscht.

### Technische Änderungen

- Das Projekt wurde komplett auf Rm2K3E migriert (verwendet jedoch weiterhin das 2k-Kampfsystem dank EasyRPGs Feature-Switch)
- Der Code für die Party-Follower wurde adaptiert, um Gebrauch von dem neuen *"CloneEvent"*-Kommando des EasyRPG-Players zu machen.
- Der für die Charakter-Grafiken zuständige Event-Code wurde angepasst, um indirekte Adressierung des Ziel-Events über Variablen zu ermöglichen (*neues Maniac-Patch Feature*) & ist somit nun weit weniger komplex.
- Viele Code-Stellen, die zuvor das Standard-Rm2k-Kommando *Wait for all Movement* verwendeten, wurden auf EasyRPGs neues Kommando *WaitForSingleMovement* umgestellt.
- Der für die Anpassung der Player-Geschwindigkeit zuständige Event-Code wurde angepasst, und macht nun nicht mehr von einem experimentellen *EasyRPG*-Feature Gebrauch.
- Das Sprach-Menü wird nun nativ von allen Builds des EasyRPG-Players unterstützt.
- Der Event-Code für die Orts-Anzeigen & Fortschritts-Stati auf der Weltkarte wurde komplett neu geschrieben und verwendet nun EasyRPGs neue *JSON*-Kommandos.
- Das Feature für das Musik-Overlay wurde umgeschrieben und verwendet nun ebenfalls die neuen *JSON*-Kommandos.
- Viele Altlasten im Skript-Code wurden ausgemistet & einige Performance-kritische Stellen in *Parallel Process*-Events wurden angepasst.

## Änderungen in Version 1.1

### Neue Inhalte & Fixes der Valaine-Mod

- **Juli 2024 Updates:** Knapp nach Release der CE brachte *ValnarsZimmerKatze* ein größeres Update für ihre Mod heraus:
	- 2 neue Quests (1 Mini-Quest in Melsan & 1 weitere in Iranis)
	- Neue Szene aus Alaines Vergangenheit (nach Abschluss ihrer Quest, wenn das Medaillon behalten wurde)
	- Neue Skill-Bücher können an diversen Orten in der Welt entdeckt werden.
	- Neuer Samen für den Schlossgarten
	- diverse zusätzliche Dialog-Anpassungen bei niedriger Menschlichkeit
	- kleinere Änderungen bei Quest-EXP
- **Bugfixes:**
	- Mondsichel (halbe Blutkosten) kann nun nicht mehr missbräuchlich verwendet werden, um Blut zu farmen
	- Unzugängliches Geheimnis in Linar angepasst
	- Falsch konfigurierter Event-Trigger in Linar verhinderte Teleport nach erstem Besuch
- **Mod-übergreifende Anpassungen:**
	- Neue Ausrüstungs-Items können nun auch von Aysha getragen werden.
	- Neue Skills können teilweise auch von Aysha erlernt werden.

### Bugfixes

- Bei der Seelenmaschine im Magierzimmer lieferte die Funktion *"Alle Seelen umwandeln"* immer die Meldung, man hätte keine Seelen des gewählten Typs im Inventar.
- Falsche Systemgrafik nach Verwenden der Magie-Apparate
- Das Auswahl-Menü zum Samen-Pflanzen im Schlossgarten *(Valaine-Mod)* funktionierte nicht korrekt.
- Diverse visuelle Fixes bei verschiedenen Animationen (zB. kurzzeitig falscher Sprite sichtbar) wurden behoben.
- Die *"klassische"* Variante des Aussaugen von NPCs verwendete eine falsche Variable, was dazu führte, dass beim Aussaugen der Lady in der Speisekammer gar keine BP aufgefüllt wurden.
- Beim Aufheben von Items wurde unter Umständen der *"Item erhalten"* Sound-Effect mehrmals abgespielt.
- Beim Aufheben von Geheimnissen wurde unter Umständen der Geheimnis-Counter zu oft inkrementiert.
- "Blick der Geister" löste ungewollt ein Reset der Overworld-Mobs aus und versetzte diese in einen verbuggten Zustand.
- Verwandlungen wurden nicht gelöst, wenn man die Harpie (Everlasting-Reign-Mod) nutzte, um sich in eine Stadt fliegen zu lassen.
- Game-Freeze bei einer Variante des guten Aysha-Endes behoben

### Neue Features
- Sämtliche MIDIs, von denen es noch keine MP3-Version gab, wurden von Zippo für die CE remastered.
  Zudem war Zippo so nett und hat alle von ihm abgemischten Stücke im viel effizienteren .opus-Format neu kodiert, was einiges an Download-Größe spart.
- Die "Moonwalk"-Animationen der Follower sind nun optional (standardmäßig aus).
- Bei der Seelenmaschine im Magierzimmer werden nun zusätzliche Icons eingeblendet, die die aktuelle Anzahl an Seelen/Seelensteinen im Inventar widerspiegelt.
- Eine weitere neue Icon-Anzeige informiert beim Gießen von Pflanzen im Garten-Minispiel *(Valaine-Mod)* über die Blutkosten.