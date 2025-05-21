
# Features der *Community Edition*

## Allgemeine Infos

Original-Spiel erstellt von: ***Alexander "Marlex" Koch***

- [Offizielle Website](https://vampiresdawn.de)
- [Fan-Website & Discord](https://vampiresdawn.org)

Es wurde das Spiel intern grundlegend an allen Ecken überarbeitet. Code-Dubletten wurden zum größten Teil in Common Events ausgelagert. Das Spiel ist somit leichter zu warten, weniger fehleranfällig und steht auf einer soliden Basis für zukünftige Erweiterungen.

- Einige der überarbeiteten Funktionen sind in der Spieledatenbank ausführlich dokumentiert.
- MapTree und Datenbankeinträge wurden zur besseren Übersichtlichkeit neu organisiert.
- **-> Modding ist ausdrücklich erwünscht**

Basis für dieses Release bildet die Version 1.1 der [“Special Mega Aysha Everlasting Reign” Edition](everlasting-reign.md) von *Yoraiko*.

Weggefallen sind die Features der ursprünglichen [“Special Edition”](special-edition.md) von *Plasquar*.

## Mod-Sammlung

Ein erweitertes Einstellungsmenü ist beim Spielstart verfügbar und erlaubt eine breite Palette an Individualisierbarkeit der einzelnen Features der verschiedenen Editionen.

Diese beinhalten:

- Die Bonus-Inhalte der englischen Übersetzung von *kj150*, auch bekannt als [Aysha Edition](aysha-integration.md)
- [Diverse Mods](mods-other.md) von *TrunX* & *TrueMG*
- Die [überarbeiteten MP3-Tracks](mods-other.md#mp3-upgrades-zippo_the_mad_mechanic)  von *Zippo_the_mad_mechanic*
- Elemente der [grafischen Überarbeitung](mods-other.md#grafische-uberarbeitungen-makotoatavarias) von *Makoto (Atavarias)*
- Elemente der in der [Screenfun-Ausgabe 04/2004](mods-other.md#screenfun-zensur) erschienenen, zensierten Version von Vampires Dawn.
- Die neuen Inhalte der [Everlasting Reign Edition](everlasting-reign.md) von *Yoraiko*
- Die neuen Inhalte der [Valaine-Mod](valaine-integration.md) von *ValnarsZimmerKatze* & *SnowyDoe*
- Einige neue Features von *Spatzenfärber*
  
Möchte man dieses Menü verwenden, darf man zu Beginn nicht *“Ich spiele VD zum ersten Mal”* wählen. Ansonsten ist es auch bei einem NG+ Durchlauf verfügbar.

## Valnar's Nightmare

Beim Wiederbetreten von Alaines Grab lässt sich eine In-Engine-Implementierung des ursprünglich im *Game Maker* implementierten Minispiels **"Valnar's Nightmare"** freischalten.

Die ursprüngliche Version wurde von *TrunX* entworfen & programmiert, und ist auf seiner Website zum Download verfügbar:

- [Info & Download der Original-Version von *Valnar's Nightmare*](http://arthure.bplaced.net/CGL/Valnar.html)

## Neue Features in der *CE*

Folgende Info ist unvollständig & veraltet (Stand Juni 2023)

Weitere Änderungen sind noch nicht ausreichend dokumentiert und können dem GitHub-Profil des Projekts entnommen werden.

- Es kann nun mit einer neuen Option zwischen Overworld Monster-Begegnungen, sowie zwischen den originalen Random Encounters gewählt werden.
   * Diese Option wirkt sich stark auf das Balancing aus. Daher werden standardmäßig passende Multiplikatoren für  erhaltene EXP gesetzt.
   * Random Encounters wurden an den neuen Orten dort, wo es Sinn macht, ergänzt. Im neuen Endgame von Everlasting Reign werden aber weiterhin Overworld Encounter forciert.
- Es kann nun auch gewählt werden, ob man mit randomisierten Loot oder den Original-Inhalten von Truhen und versteckten Geheimnissen spielen möchte.
   * Zusätzlich gibt es eine Option, ob beim Umwandeln von Menschen auch randomisierte Items erhalten werden sollen
- Es ist nun möglich, zwischen Original-RNG und einem fixen RNG-Seed, der bei Spielbeginn berechnet wird, zu wählen. Das bedeutet, dass randomisierte Item-Belohnungen für jeden Spieldurchlauf fixiert sind. Man kann also nicht einfach Speichern & Laden, um so ein anderes Item zu erhalten.
   * Betroffen sind hiervon randomisiertes Loot in Truhen, bei Versteckten Geheimnissen, randomisiertes Loot beim Umwandeln von Menschen, die Belohnungen des Diebes und das Schicksalsspiel im Magierzimmer.
- Es wurden durch Everlasting Reign diverse Dialog-Skip-Optionen hinzugefügt, die gemeinsam hatten, dass die Option zum Überspringen immer als erste Auswahl angeboten und dadurch bei nervösen Fingern aus Versehen ausgelöst werden konnte. Es wurde ein Schalter hinzugefügt, um diese Skips entsprechend zu konfigurieren oder ganz deaktivieren zu können.
- Die Räume der ersten zwei Obergeschosse des Schlosses wurden zu gemeinsamen Maps kombiniert. Es kann nun zwischen dieser neuen Map und den originalen einzelnen Zimmern gewählt werden.
- **NEU**: Für aktive Beschwörungen und Verwandlungen können nun neue, verbesserte Timer eingeblendet werden. Diese funktionieren parallel zueinander
   * Bei Konfrontationen mit Bossen lief während des Dialogs der Beschwörungs-Timer im Hintergrund weiter, was zu einem Despawnen vor dem Kampf führen konnte. Dies wurde korrigiert.
   * Der Timer lief auch weiter, wenn eine Beschwörung in Starre fiel (Im Original “Vanilla” Vampires Dawn konnten die Beschwörungen nicht wiederbelebt werden). Nun wird in diesem Fall eine Beschwörung automatisch wieder gelöst.
- Heil-Items wirken nun nicht mehr für normale Beschwörungen (wie im Original-Spiel)
   * Ausnahme: Die Perma-Beschwörungen der Everlasting Reign Edition
   * Es gibt stattdessen nun eine Option, mit der sich festlegen lässt, ob für alle Beschwörungen Heil-Items verwendbar sein sollen.
- Wieder aktiviert & verbessert: Schiffe lassen sich wieder wie in Vanilla VD versenken. Dies passiert nun nicht mehr automatisch, sondern kann auch verhindert werden. Außerdem muss vorher der Kapitän getötet werden.
- Ergänzt: Einige neue NPCs, die durch die Special Edition und die Everlasting Reign Edition hinzugefügt wurden, konnten nicht ausgesaugt oder umgewandelt werden.
- ***WALnar***
- **NEU**: Level-Anzeige auf Weltkarte: Die Farbe der markierten Orte gibt einen Hinweis auf den zu erwartenden Level eines Ortes (optional)
- **NEU**: Es kann nun eine Uhr eingeblendet werden, die neben der aktuellen Zeit auch anzeigt, ob gerade Tag oder Nacht ist.
   * Der Tag-Nacht-Wechsel verläuft außerdem flüssiger und es kann nun auch die Geschwindigkeit der Uhr modifiziert werden.
- **NEU**: Blick der Geister wurde erweitert. (Optional einschaltbar)
   * Versteckte Orte auf der Weltkarte werden bei Nutzen des Skills markiert
(Aysha Edition)
   * Versteckte Geheimnisse können ebenfalls markiert werden.
   * Eine neue Option ermöglicht es, den Blick der Geister per Map zeitlich unbegrenzt zu nutzen. Erst beim Wechsel der Map wird der Effekt zurückgesetzt.
- **NEU**: Verbessertes Party-Management.
   * Zusätzlich zu dem Team-Management der in Everlasting Reign eingeführten Perma-Beschwörungen kann nun die Reihenfolge der Teammitglieder frei angepasst werden.
   * Experimentell: Optional kann ein “Nachlaufen”-Feature aktiviert werden.
- Man kann den Pfadeschaffer nun wegwerfen
- Verbesserte Spiel-Statistiken-Anzeige