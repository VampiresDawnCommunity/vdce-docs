
# Änderungen zur "Aysha Everlasting Reign Special Edition" (1.1)

## Verbesserungen und neue Features

- Es wurde das Spiel intern grundlegend an allen Ecken überarbeitet. Code-Dubletten wurden zum größten Teil in Common Events ausgelagert. Das Spiel ist somit leichter zu warten, weniger fehleranfällig und steht auf einer soliden Basis für zukünftige Erweiterungen.
   * Einige der überarbeiteten Funktionen sind in der Spieledatenbank ausführlich dokumentiert.
   * MapTree und Datenbankeinträge wurden zur besseren Übersichtlichkeit neu organisiert.
   * -> Modding ausdrücklich erwünscht
- Ein erweitertes Einstellungsmenü ist beim Spielstart verfügbar und erlaubt eine breite Palette an Individualisierbarkeit der einzelnen Features der verschiedenen Editionen.
   * Diese beinhalten:
      * Die Bonus-Inhalte der englischen Übersetzung von *kj150*, auch bekannt als **Aysha Edition**
      * Diverse Mods von *TrunX* & *TrueMG*
      * Die überarbeiteten MP3-Tracks von *Zippo_the_mad_mechanic*
      * Elemente der grafischen Überarbeitung von *Makoto (Atavarias)*
      * Elemente der in der Screenfun-Ausgabe 04/2004 erschienenen, zensierten Version von Vampires Dawn.
      * Die neuen Inhalte der Everlasting Reign Edition von *Yoraiko*
      * Die neuen Inhalte der Valaine-Mod von *ValnarsZimmerKatze* & *SnowyDoe*
      * Einige neue Features von *Spatzenfärber*
   * Möchte man dieses Menü verwenden, darf man zu Beginn nicht “Ich spiele VD zum ersten Mal” wählen. Ansonsten ist es auch bei einem NG+ Durchlauf verfügbar.
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

## Bugfixes allgemein

- **Allgemein**: Zahllose Rechtschreib-, Tippfehler und Textformatierungen wurden gefixt.
- **Allgemein**: Glossar überarbeitet. Viele im Kampfsystem erscheinenden Nachrichten waren (technisch bedingt durch die damals verwendete *RM2K-Version*) weit entfernt von korrektem Deutsch.
- **Allgemein**: Wenn man Verkäufer, die hinter einer Theke stehen, aussaugte, wurde Valnar in vielen Fällen von dem Theken-Tile überlappt.
- **Intro/Shannar**: Fehlerhafter Dialog-Trigger in Shannar als Asgar: Die Statue im Haus des Bürgermeisters enthält ein Dialog-Event für Asgar, das wegen einer falsch gesetzten Priorität nie ausgelöst werden konnte.
- **Intro/Shannar**: Wenn man als Asgar während der Hinrichtungsszene in Shannar die Wache im Irrenhaus tötete, änderte sich die Position des Kopfes, wenn man die Map verließ und wieder betrat.
- **Intro/Klennar**: Dialog-Wiederholung in Klennar bei Wiederbetreten & Verlassen des Hauses von Dr. Jarn als Menschen-Valnar.
- **Intro/Asgars Schloss**: Einer der Grabsteine besaß einen zusätzlichen Dialog, wenn man ihn als Asgar aktivierte. Dieser wurde wegen eines fehlerhaften Skripts allerdings nie angezeigt.
- **Intro/Melsan/Strandladen**: Beim ersten Betreten von Melsan wird dem Jungvampir Valnar von Asgar das Aussaugen erklärt und ein Zauber zum Umwandeln von Menschen beigebracht. Man konnte zuvor aber bereits südlich den Strand betreten und hier Menschen aussaugen & umwandeln. Nun kann man mit diesen Menschen erst nur normal reden, bis man über seine Vampir-Fähigkeiten aufgeklärt wurde.
- **Intro/Magiegebirge**: Bei der Flucht aus dem Magiegebirge war es möglich, einen der notwendigen Trigger zu umgehen.
- **Weltkarte**: Karten-Anzeige & Wolkeneffekt überdeckten Menü
- **Asgars Schloss**: Verwandelte man sich in der Aussenansicht von Asgars Schloss mittels Schatten des Wolfs, wurden die Leitern unsichtbar. Bei Asgars Wolfsverwandlung blieben sie dagegen unverändert.
- **Asgars Schloss**: Nach dem Sieg über Sir Esthir änderten sich die Positionen seiner Leichenteile, wenn man die Map verließ und wieder betrat.
- **Asgars Schloss/Magierzimmer**: Magierzimmer, nach Wiederbelebung von Aysha: Nachdem Valnar das Overlay für Bossgegner erklärt wurde, wurde das Picture nicht ordentlich gelöscht.
- **Asgars Schloss/Magierzimmer**: Beim Schicksalsspiel bestand eine seltene Chance (~0,8%), dass man zwar ein Item erhielt, aber dennoch eine Nachricht angezeigt wurde, als hätte man verloren.
- **Melsan**: Nicht verwendete Sequenz im Wachturm, die aus Versehen ausgelöst werden konnte (Touch Event).
- **Melsan**: Während man mit Valnar die Feuerprobe absolvierte, konnte man im Wachturm das Zellen-Ereignis auslösen, in dem Asgar den Dieb verhörte, obwohl er eigentlich nicht Teil der Party war.
- **Herlis, 1. Haus**: Wenn man hier die Frau ermordete, reagierte ihr Mann darauf nicht, da falsch geskriptet.
- **Herlis**: Wenn man den Bruder der armen Frau ermordete, anstatt ihn zu ihr zu senden, verblieb die Quest weiterhin im Questlog.
- **Thessa**: Wenn man im Armdrücken-Zelt Karlos umwandelte, wurde dabei fälschlicherweise Willo getötet
- **Thessa/NG+**: Im NG+ blieben zwar die meisten Items, wie auch die Thessa-Punktekarte, erhalten, aber die erspielten Punkte wurden wie sämtliche anderen Variablen zurückgesetzt. Dies wurde korrigiert.
- **Thessa**: Bei manchen Illusionsspielen in Thessa war es möglich, sich via Zuflucht oder Fluchttrank weg zu teleportieren, was beim Spiel "Freier Fall" sogar zu einem Softlock führte.
- **Limm**: Brachte man im Keller eines Hauses eines der 2 Kinder um, war es möglich, den Raum zu verlassen, ohne zuvor das andere (Zeuge!) zu beseitigen.
- **Limm**: Der Alte in Limm hatte ein kleines Stück zusätzlichen Dialog, das wegen eines Skripting-Fehlers nicht ausgelöst werden konnte.
- **Lombar**: Die für Shannar zu rekrutierende Waffenhändlerin war falsch geskriptet und dadurch an die HP-Variable der jungen Frau im Keller in einem der Häuser gebunden. Brachte man die Frau im Keller um, verschwand die Waffenhändlerin und im Gegenzug konnte die Waffenhändlerin, solange sie in Lombar blieb, beliebig oft ausgesaugt und umgewandelt werden.
- **Asdion**: Beim Verlassen des Geheimladens in Asdion wurden aktive Wettereffekte nicht wiederhergestellt.
- **Asdion/Shannar**: Tötete man im Pub die einsame Frau, wurden, wie sonst überall auch üblich, die Menschen im Lokal in Panik versetzt. Redete man aber zuvor mit ihr und löste damit ihre Abreise nach Shannar aus, konnte man sie vor dem Verlassen des Pubs töten, ohne dabei das Pub-Angriffs-Ereignis auszulösen.
- **Asdion**: Ähnliches Problem im Pub: Die einsame Frau fällt wie alle anderen auch in Panik, wenn man einen Menschen tötete.  Löste man aber zuvor ihre Abreise aus, war sie von jedem Mord der in ihrer Nähe passierte, unbeeindruckt.
- **Asdion/KdA**: Wenn man die Gefangene bei den Kindern der Apokalypse in Asdion befreite, konnte man sich mit ihr im Schlepptau mit Zuflucht ins Schloss teleportieren. Erst wenn man das nächste Mal Asdion betrat, wurde ihr Befreiungs-Ereignis ausgelöst.
- **Uruya-Pub**: Tötete man den Barkeeper durch Aussaugen, wurde eine Animation auf eine auf der Map nicht existierende Event-ID angewandt, was bei der Original-RPG_RT.exe zu einem Absturz führte und bei EasyRPG eine Fehler-Warnung auslöste.
- **Uruya-Pub**: Wenn nach einem Angriff die Zeugen in Panik versetzt wurden, konnte man den Pub trotzdem verlassen, da das Ereignis, das den Spieler vom Verlassen hindern sollte, so geskriptet war, nicht per "Touch", sondern per Aktionstaste ausgelöst zu werden.
- **Uruya-Pub**: Wenn man den Barkeeper tötete, waren die Lokalbesucher davon völlig unbeeindruckt.
- **Lombar**: Wenn man den Sonnenschutzmantel-Verkäufer via Aussaugen tötete, starb dabei auch der Questgeber (Sandwurm) im Süden der Stadt.
- **Isthar**: Mann verwendete falsche Variable und konnte mehr als 3 mal ausgesaugt werden.
- **Asdion/Isthar/Shannar**: Überredete man die zwei einsamen Menschen aus Asdion und Isthar, nach Shannar auszuwandern, tötete aber die Frau, bevor man das Pub verließ, dann war der Mann in seinem Haus in Shannar in Panik, als ob man sie direkt neben ihm getötet hätte.
- **Esrik**: Tötete man die Frau, die dem Spieler den Auftrag gibt, den Barkeeper ausserhalb der Stadt zu suchen, ploppte dieser plötzlich aus dem Nichts auf und war in Panik, da er ihren Mord mitbekam.
- **Schloss Tranak**: Die Lagerwache in Schloss Tranak ist so geskriptet, dass sie beim Stöbern durch die Kisten immer wütender werden sollte und am Ende angreift. Aufgrund von Fehlern in diesem Skript wurden diese Nachrichten aber alle auf einmal (beim ersten Anfassen einer Kiste) ausgelöst und der Angriff selbst konnte nicht ausgelöst werden.
- **Tradan**: Überredete man Yuffie aus dem Fass zu kommen, um sie anschließend zu töten, änderte ihre Leiche die Position, wenn man die Map verließ und wieder betrat.
- **Tradan-Gruft**: Hier war es bei der Flucht durch einen Bug im Zähler möglich, in seltenen Fällen den Maximalwert zu überschreiten. Somit war der Timer obsolet und es wurde nie ein Game Over ausgelöst.
- **Abraxas’ Höhle**: Hier waren zahlreiche Geheimgänge falsch geskriptet und lösten bei Klick ein Geheimnis aus (versteckter Vampirstein), das für einen anderen Ort im Magiegebirge vorgesehen war.
- **Allgemein**: Wenn es bei der Tötung eines Menschen Zeugen gab, konnte man bisher mittels Zuflucht und Fluchttrank zurück ins Schloss, was allerdings nicht die Absicht des Entwicklers war. Nun muss man einen Raum voller panischer Menschen auch tatsächlich auslöschen, um fortzufahren.
- **Allgemein**: Es war an vielen Stellen möglich, Leitern in aktiver Wolfsverwandlung zu betreten (entweder als Asgar oder als Valnar), obwohl dies nicht möglich sein sollte. Außerdem konnte man sich, während man sich auf einer Leiter befand, verwandeln.
- **Allgemein**: Es war möglich, Zuflucht einzusetzen, während man sich auf einer Leiter befand. Dabei wurde Valnars Animation verbuggt.
- **Allgemein**: Valnar bewegt nun seine Arme, wenn er auf einer Leiter klettert.
- **Allgemein**: Originalen GameOver-Screen wiederhergestellt und das ROFLLOL-Cringe-Bild weggeworfen.
- **Menü/Power-Ups**: Die im Seelen-Menü per RNG verteilten temporären Power-Ups für Geschick oder für Stärke teilten sich dieselbe interne Variable zusammen mit dem Zauber, um eine zufällige Anzahl Filar zu erhalten. Verwendete man eine der 3 Funktionen, während noch ein Power-Up aktiv war, wurde beim Zurücksetzen der Werte für Stärke/Geschick die veränderte Variable herangenommen. Dadurch konnten die Status-Werte dauerhaft erhöht oder erniedrigt werden.
- **Inventar**: Laut Inventarbeschreibung sollte die Titanrüstung +25 Verteidigung bieten. Diese war allerdings auf +22 konfiguriert.
- Nach dem Sieg über den **Todesclown** wurde die Bossgrafik-Einblendung nicht gelöscht.
- **Items**: Aufgrund eines Skriptfehlers konnte nur Valnar vom Heilungseffekt des antiken Vampirrings profitieren.
- **Endgame**: Wenn man während des Endgames einen Zauber wie Zeitverzerrung oder Beschwörungen wirkte, hatte Valnar dabei noch immer seine Sonnenbrille auf.
- **Endgame**: Wenn man während des Endgames das Punktekarte-Item aktivierte, um seine Punktzahl für die Spiele in Thessa zu überprüfen, hatte Valnar dabei noch immer seine Sonnenbrille auf.
- **Endgame**: Wenn man während des Endgames den verpackten Gegenstand öffnete, wurde weiterhin der Dialog zwischen Valnar, Asgar & Alaine ausgelöst (und Valnar hatte seine Sonnenbrille auf).
- **Enden**: Valnar Solo Ende (Hohe Menschlichkeit): Hier gibt es 2 Varianten, abhängig davon, ob man den Anführer der Kinder der Apokalypse getötet hat, oder nicht. Ein Dialog über das Schicksal von Ronak wurde nur dann ausgelöst, wenn man ihn tötete, obwohl er nicht davon abhängig sein sollte.
- **Enden**: Beim Ende Valnar&Alaine (Böse) wurde in einem Dialog des Jungen das falsche Faceset verwendet.
- **NG+**: Quest Item "Eckiger Schlüssel"wird nun beim Starten eines neuen Spiels aus dem Inventar entfernt.


## Integration der englischen “Aysha-Edition”

### Bugfixes

- **Intro**: Bei der Vorstellung von Aysha wurde das alte Charset, anstatt der in der Aysha-Edition angepassten Grafik verwendet.
- **Intro**: An einigen Stellen in Valnars Haus wurde das alte Faceset für Aysha verwendet.
- **Intro**: Bei der Hinrichtung von Aysha durch Abraxas wurde das alte Charset verwendet.
- **Intro**: Bei der Bergspitze wurde das alte Charset für die erhängte Aysha verwendet.
- **Skills**: Aysha kann wie Valnar "Zeitverzerrung" erlernen. Wegen eines fehlenden Skripts war der Zauber jedoch wirkungslos.
- **Skills**: Einige Skills von Aysha waren nicht korrekt übersetzt und sollten eigentlich namentlich mit vielen der bereits erlernbaren Skills der anderen 3 Vampire übereinstimmen.. Das fiel vor allem im Magierzimmer beim Magielernsystem auf, da die eingeblendeten Bilder einen anderen Skill-Namen anzeigten.
- **Items**: Aysha war in der Lage, neben Valnar, ebenfalls das Tranak-Schwert als Waffe zu verwenden. Zugewiesen ist dem Schwert jedoch die Animation von Valnar.
- **Items**: Pandemonium Fix: Wenn eine Beschwörung, der Zeitverzerrungs- oder der Zufluchtszauber fehlschlugen, wurde der Originalwert der BP-Kosten wiederhergestellt, nicht der halbierte.
- **Klennar**: Beim Plündern des Lagers in Klennar wurde zwar der Geheimnis-Counter inkrementiert, aber der Geheimnis-Text dabei nicht ausgelöst.
- **Klennar**: Dialog für Golbar-Quest korrigiert.
- **Klennar**: Sprach man mit dem Golbar-Questgeber, wandte sich Valnar immer wieder der Wand zu, anstatt den korrekten NPC anzusehen.
- **Klennar**: Aysha blieb im Team, wenn ihre Klennar-Quest abgebrochen wurde, obwohl sie angab, die Stadt zu verlassen und draußen zu warten.
- **Thessa**: Der Dialog über den gelben Stoffbär wurde bei jedem Anklicken wiederholt, obwohl dieser nur einmal erscheinen sollte.
- **Thessa**: Brachte man den Jungen in Thessa zu seinem Vater zurück, duplizierte er sich. Einer stand nun neben ihm und schaute dem Clown zu, während der zweite am Originalort verweilte.
- **Thessa**: Mehrere Texte des Thessa-Jungen waren nicht übersetzt.
- **Herlis**: Besucht man Herlis mit Aysha, hat sie mehrere Dialoge, die nach der Konversation mit verschiedenen Einwohnern ausgelöst werden können. Diese waren allerdings so geskriptet, dass man einen guten Teil überspringen kann, wenn man aus Versehen mit der falschen Person zuerst spricht.
- **Herlis**: Falscher, unsichtbarer Trigger im Waffenshop
- **Shannar**: Wenn man in Shannar Reynas Quest abschloss, wurde zwar der Geheimnis-Counter inkrementiert, aber der Geheimnis-Text dabei nicht ausgelöst.
- **Shannar**: (SE) Variablen-Konflikt zwischen Special Edition & Aysha-Edition: Die Anzahl der für Shannar zu rekrutierenden Personen wurden in verschiedenen Variablen gespeichert, die mit der Integration vereint wurden. Dabei wurde nicht berücksichtigt, dass diese Special-Edition-Variable beim Töten der Bewohner auch reduziert wird. Ein Dialog von Aysha kann damit mehrmals getriggert werden, wenn man immer wieder Leute tötet, um Platz für neue zu machen. Außerdem wurde das entsprechende Event bei vielen zu rekrutierenden Personen nicht aufgerufen.
- **Shannar**: (SE) Wenn man die Frau aus Sanos rekrutierte und versuchte, eine Vampirrüstung bei ihr upzugraden, wurde Aysha bei der Prüfung, ob eine Rüstung getragen wird, nicht berücksichtigt.
- **Asgars Schloss/Shannar**: Wenn man mit Aysha während des Schloss-Rundgangs den Thronsaal betrat, konnte ihr Dialog in Shannar nicht mehr ausgelöst werden (Fehlerhafter Switch).
- **Asgars Schloss**: Beim Schloss-Rundgang verliert Aysha eine Bemerkung über die in der Gruft-Speisekammer eingesperrte Frau. Diese konnte mittels Gruft-Mod aber zuvor bereits getötet werden (Umwandeln).
- **Tradan (Aysha-Pfad)**: Bei sämtlichen Geheimnissen im heilen Tradan wurde zwar der Geheimnis-Counter inkrementiert, aber der Geheimnis-Text dabei nicht ausgelöst.
- **Tradan (Aysha-Pfad)**: (SE) 1 verstecktes Geheimnis, das in der Special Edition neu zu Tradan hinzugefügt wurde, war in der heilen Variante der Stadt nicht erhältlich.
- **Tradan (Aysha-Pfad)/Schloss Tranak**: Die Briefe von Frank & Zarah waren nicht wie andere Quest Items hervorgehoben.
- **Tradan-Gruft**: Hier gibt es einen neuen geheimen Raum, der mit Hilfe von Asgar betreten werden kann. Dies war immer möglich, auch wenn er sich nicht im Team befand (Perma-Beschwörung).
- **Tradan-Gruft**: Skriptfehler bei Flucht aus der Gruft: Hier sollte ein geheimer Ort bei der Flucht eigentlich nicht mehr betretbar sein.
- **Lava-Dungeon**: Hier wurde eine der Animationen bei der Konfrontation mit Aysha auf ein falsches Ereignis angewandt.
- **Abraxas' Turm**: Der Sukkubus-Bossfight sollte, falls man Aysha im Team hat und ihn bereits in der Lava-Höhle besiegt hat, eigentlich übersprungen werden.
- **Asran-Dungeon**: Nach dem Sieg über Vincent wurde ein falsches Sprite für Vincent angezeigt, als er von Ayshas Attacke getroffen wurde und es wurde zudem versucht, eine nicht existierende Animation auf ihn anzuwenden.
- **Hyugas Grab**: (SE) Bei der Prüfung, ob die alte Rüstung von einem der Team-Mitglieder getragen wird, wurde Aysha nicht berücksichtigt.
- **Enden**: (Ende 5) Eine der Endsequenzen (Flug über Weltkarte) fehlte, wenn man Ayshas Klennar-Quest abgeschlossen hatte.
- **Enden**: (Ende 5) Falsche Variablen in Ende5: Wenn man die Klennar-Quest mit Aysha nicht abgeschlossen hat, sollten hier eigentlich bereits die Credits ablaufen. Stattdessen frierte das Spiel für mehr als 1 Minute ein.
- **Enden**: (Ende 5) In der Sequenz in Valnars Zimmer war eine falsche Variable für den Thessa-Teddybären definiert, wodurch er mit einer Person in Sanos verbunden war. Hatte man diesen Bewohner zuvor getötet, wurde er angezeigt, unabhängig davon, ob man ihn für Aysha gewonnen hat oder nicht. Ansonsten blieb er unsichtbar, auch wenn man ihn gewonnen hatte.
- **Enden**: Skript-Fehler in Ende6: Hier wurde eine falsche Variable für einen der Tradan-Bewohner verwendet, was eine kurze Dialog-Sequenz verhindern könnte.
- **Enden**: Skriptfehler in Ende6: Flammen-Animationen sollten an einer bestimmten Stelle verschwinden, blieben aber wegen einer falschen Variable über die Dauer der gesamten Sequenz erhalten.
- **Enden**: Ende 3, Spezial-Ende, wenn man Reyna-Quest vervollständigt: Hier wird auch eine Animation wegen einer falschen Variable nicht gecancelt.

### Fehlende Features, die ergänzt wurden

- **Allgemein**: Fehlende Zuneigungs-Änderung in Iranis-Pub-Event
- **Allgemein**: Fehlende Zuneigungs-Änderung in Esrik-Event
- **Allgemein**: Ayshas Barehand-Animation war ihrem Charakter nicht zugewiesen. Stattdessen nutzte sie immer die erste Standard-Animation des Makers "0001:Hit A".
- **Allgemein**: In den Waffen-Shops der Welt können nun Peitschen für Aysha gekauft werden.
- **Skills**: Fehlendes Feature der Aysha-Edition: Blick der Geister hebt nun auch auf der Weltkarte versteckte Orte hervor.
- **Skills**: Fehlendes Feature der Aysha-Edition: Die Dauer von Blick der Geister steigt nun abhängig von Valnars Level.
- **Skills**: Ayshas Lv.1 Start-Skills "Finsterseele", "Schlaf" & "Goldener Segen" (Original: "Heilung") fehlten und es gab keine Möglichkeit, diese nachträglich zu erlernen.
- **Items**: Mantel des Vampirs konnte von Aysha nicht getragen werden.
- **Dialoge**: Herlis mit Aysha: Fehlender Dialog-Trigger beim Waffenhändler
- **Dialoge**: Lombar: Fehlender Dialog-Trigger mit Aysha in einem der Häuser ergänzt.
- **Dialoge**: Melsan: Fehlender Dialog-Trigger mit Aysha bei einer der Personen in der Stadt.
- **Dialoge**: Fehlender Aysha-Dialog bei der Entdeckung des Münzapparats.
- **Dialoge**: Fehlender Aysha-Dialog beim Öffnen des verpackten Gegenstands.
- **Dialoge**: Fehlender Aysha-Dialog beim ersten Betreten der Dschungel-Insel
- **Dialoge**: Fehlender Aysha-Dialog bei dem kleinen Mädchen in Isthar
- **Dialoge**: Mehrere fehlende Aysha-Dialoge in Abraxas' Turm
- **Dialoge**: Fehlender Aysha-Dialog bei der Konfrontation mit Vincent Weynard
- **Dialoge**: Fehlender Dialog, nachdem Aysha von Valnar geköpft wurde (Ende 3)
- **Dialoge**: Fehlende Aysha-Dialoge bei der Rettung des Barkeepers
- **Dialoge**: Fehlender Aysha-Dialog bei Schmetterlingswiese
- **Dialoge**: Fehlender Aysha-Dialog, wenn das Wappen zum Entsperren des Geheimgangs in Schloss Tranak fehlt.
- **Dialoge**: Fehlende Dialoge bei Sukkubus-Bosskampf ergänzt
- **Klennar**: Klennar Inn bei Aysha-Besuch: Gäste im oberen Stockwerk konnten ausgesaugt oder umgewandelt werden, obwohl man von Aysha davon abgehalten werden sollte.
- **Klennar**: Aysha-Pfad sieht eine Gelegenheit vor, mehrere Geheimnisse in Dr. Jarns Haus abzustauben, obwohl Aysha dabei ist und man sie dadurch nicht mehr töten kann.
- **Klennar**: Aysha-Pfad sieht eine Gelegenheit vor, im Haus der Reichen Schnösel in den Keller zu gehen, obwohl Aysha dabei ist und man die Bewohner dadurch nicht mehr töten kann.
- **Asgars Schloss**: Rundgang mit Aysha im Schloss: Fehlende Prüfung beim Betreten des Magierzimmers. Hier sollte die Truppe sich eigentlich vergewissern, dass der Rundgang abgeschlossen wurde (kann übersprungen werden, wodurch man aber ein Zuneigungs+ zu Aysha verpasst).
- **Asran-Dungeon**: Fehlende Aysha-Truhe ergänzt
- **Asran-Dungeon**: Nach dem Sieg über Vincent fehlte der Sprite für Aysha, wenn man sich dem Buch näherte.
- **Endgame/Ende 3**: Hier fehlte zusätzlich zu Asgars Blutgeist, der Blutgeist für Aysha, nachdem man sie besiegt hatte.
- **Questlog**: Fehlender, alternativer Questlog-Eintrag ergänzt, welcher den Spieler nach Tradan verweisen sollte, falls man Aysha in der Truppe hat.
- **Questlog**: Fehlender, alternativer Questlog-Eintrag ergänzt, welcher den Spieler nach Tradan verweisen sollte, falls man Aysha in der Truppe hat.
- **Questlog**: Fehlender, alternativer Questlog-Eintrag ergänzt, der aufscheinen sollte, wenn man im Endgame gegen Asgar & Aysha antreten sollte.
- **Ende**: In den Credits sollte eine Grafik für Aysha auftauchen, falls man die zusätzlichen Inhalte gespielt hatte.


## Bugfixes Everlasting Reign

### Allgemein Technisches, Items & Skills

- **Allgemein**: Es wurden sehr viele Texte neu formatiert, da an vielen Stellen der Text zu lang war und dadurch abgeschnitten wurde.
- **Allgemein**: Bei der Nutzung von diversen Teleportern wurden aktive Wettereffekte nicht wiederhergestellt.
- **Allgemein**: Da man mittels Permabeschwörung seine Truppe frei verändern kann, gibt es an mehreren Stellen im Spiel Schranken, die man nur überschreiten kann, wenn man alle anderen Vampire mit im Team hatte. Man konnte allerdings gleich nach dem Passieren dieser Schranken Zuflucht einsetzen, um sein Team zu ändern und zum gespeicherten Ort zurückkehren. Dies wird nun an Stellen, wo es relevant ist, unterbunden.
- **Intro**: Introskip verbessert (Es wurden manche wichtigen Schalter nicht gesetzt, was potentiell Probleme auslösen konnte bzw. beim Mergen mancher Maps auch Probleme auslöste)
- **Intro**: Wenn man den Introskip nutzte, erhielt man automatisch einen Speicherkristall. Dieser sollte aber weiterhin erst mit einem NG+ freigeschalten werden.
- **Geheimnisse**: Es gibt insgesamt 75 Stücke Orichalcus-Staub zu entdecken. Gesammelt werden konnten aufgrund einer Doppelbelegung von Variablen aber nur 74 werden.
- **Geheimnisse**: Von den restlichen 45+ neuen, aufsammelbaren Geheimnissen konnten aufgrund von Doppelbelegungen nur 43 aufgesammelt werden.
- **Items**: Es war möglich, sich von Orten, an denen Zuflucht blockiert ist, mithilfe des Fluchttranks weg zu teleportieren, was in verschiedenen Dungeons zu Problemen führen kann.
- **Items**: Wenn das Nutzen des Fluchttranks durch eine Verwandlung verhindert wurde, wurden Valnar wie bei Zuflucht Blutpunkte wiederhergestellt.
- **Items**: Monsteressenz Fix: Wurde von anderen In-Game-Timern wie zB. von der Fledermausverwandlung beeinflusst.
- **Items**: Das Item "Schreckens-Ankh" war wirkungslos, da im zugehörigen RandomBattle-Skript die Ausrüstung von Valnars menschlicher Form geprüft wurde. Nun wird der korrekte Valnar geprüft und es werden auch alle anderen Vampire berücksichtigt.
- **Items**: Das Party-Management-System konnte missbräuchlich verwendet werden, um permanente Boosts auf Geschick oder Stärke zu erhalten (Mittels Seelen-Menü).
- **Items**: Wenn man die "Atmo-Texte" für Skills und Speichern abschaltete, wurden diese zwar für normale Speichersteine deaktiviert, für den Speicherkristall aber trotzdem weiterhin angezeigt.
- **Skills/Beschwörungen**: Die Zauber "Skelett beschwören" und "Skelett beleben" waren geskriptet, bei aktivem Permabeschwörungs-Feature nicht mehr zu despawnen. Die restlichen Beschwörungen allerdings nicht. Das Feature wurde hier entfernt. Perma-Beschwörungen müssen weiterhin im Schloss erhalten werden.
- **Skills/Beschwörungen**: Asgars "Skelettmagier beleben" landete in einer Endlosschleife.
- **Skills/Beschwörungen**: Bei Ändern der Party werden alle aktiven zeitbasierten Beschwörungen automatisch entfernt, um Probleme zu vermeiden.
- **Skills/Beschwörungen**: Dank Party-Management-Feature können nun Asgar&Alaine aus der Truppe entfernt werden, was dazu führt, dass man mehrere zeitbasierte Beschwörungen casten kann. Hier hat eine Prüfung gefehlt, ob ein Charakter bereits gecastet oder mit der Permabeschwörung ins Team geholt wurde und die verbrauchten Blutpunkte wurden in dem Fall nicht wiederhergestellt.
- **Skills/Beschwörungen**: Es war möglich eine Permabeschwörung ins Team zu holen und danach den Zauber für die entsprechende Beschwörung (Skelett, Magierskelett, Golem oder Dämon) zu zaubern, wodurch der Charakter zu einer zeitbasierten Beschwörung umgewandelt wurde. Dies geht nun auch nicht mehr.
- **Skills/Beschwörungen**: Die Permabeschwörungen “Ronak” & “Drachenfee” konnten einige Status-Items einsetzen, welche für Beschwörungen nicht vorgesehen waren. (zB. Runen, Nektar, …)
- **Skills/Verwandlungen**: Wolfsverwandlung ATK+ Fix: Das Angriffs-Plus für die Wolfsverwandlung wurde nur zurückgenommen, falls die Verwandlung vorzeitig beendet wurde (Entweder durch Beschwörung lösen oder ein Ereignis wie zB. das Betreten einer Stadt). Ließ man den Timer normal auslaufen, blieb der Bonus. So konnte man sich in einigen Minuten schnell hoch-cheaten.


### Neuer Content in Schloss/Basen/neue NPCs

- **Basis/NPCs**: Häuptling Jizzu stellte sich als "Hauptling Orkanisatorr" vor. (Eigentlich Name des Ork-Königs)
- **Basis/NPCs**: Dialog-Choice-Fehler bei Häuptling Jizzu
- **Basis/NPCs**: Bevor König Orkanisator dem Spieler die benötigten Brau-Zutaten bekannt gibt, wurde man nach dem Warten in Asgars Thronsaal teleportiert; unabhängig davon, ob man ihn in Asgars Schloss oder in einer der anderen Basen anspricht.
- **Basis/NPCs**: König Zack von Zombenstein gibt dem Spieler die Aufgabe, seine Zombies zu besiegen; geskriptet war er allerdings wie König Knochenteich, auf den Sieg über die Skelett-Diener zu reagieren.
- **Basis/NPCs**: König Knochenteichs Minenverstärkung wirkt nun auch für Asgars Mine, sowie die geheime Mine der Special Edition
- **Basis/NPCs**: König Daar war falsch geskriptet, sodass immer eine exakte Anzahl an Siegen notwendig war, um die nächste Belohnung zu erhalten (150, 250 & 500). Überstieg man diese, hatte man Pech. Außerdem gab es hier einen Konflikt mit Schaltern, die er sich mit König Zack teilte.
- **Basis/NPCs**: Bei den nötigen Siegen, die man König Daar vorweisen musste, wurden auch Siege aus vergangenen Spiel-Durchläufen berücksichtigt. Mit jedem NG+ stieg die Anzahl der Siege weiter in die Höhe, ohne zurückgesetzt zu werden, und man erhielt automatisch alle Belohnungen.
- **Basis/NPCs**: Die Item-Belohnungen von König Daar wurden nicht ausgegeben, obwohl dem Spieler eine entsprechende Nachricht angezeigt wurde. (Siegel des Treja, Krone der Tanis & Umhang des Daar)
- **Basis/NPCs**: Fehlerhafte Item-Prüfungen bei Finnik dem Gotteschmied. (Bedingungen konnten ebenfalls mit jeweils 1 Stk. weniger der gefragten Items erfüllt werden.)
- **Basis/NPCs**: Fehlerhafte Item-Prüfungen bei Jinnall (dito)
- **Basis/NPCs**: Fehlerhafte Item-Prüfungen bei König Orkanisator (dito)
- **Basis/NPCs**: Fehlerhafte Item-Prüfungen bei König Zack (dito)
- **Basis/NPCs**: Die Level-Prüfung der neuen Shops von Frederica & Almond war fehlerhaft, wenn man sie in Abraxas Turm oder in Schloss Tranak ansprach. Hier wurde immer der Level des Charakters für Valnars Menschen-Form überprüft.
- **Basis/NPCs**: Wenn man Trasmos nach dem Senden ins Schloss das erste Mal in Schloss Tranak oder in Abraxas’ Turm ansprach, kam derselbe Dialog, als ob er sich in Asgars Schloss befände (Das er mit Schloss Tranak vergleicht). Sein Skript wurde angepasst, sodass man ihn nun erst in Asgars Schloss ansprechen muss, bevor er in einer der Basen erscheint.
- **Asgars Schloss**: Schlossbelagerung Loot-Leichen: Textbox mit "[Item] erhalten" wurden mit Asgars Faceset angezeigt.
- **Asgars Schloss**: Switch-Kollision zwischen Ghoul (südliche Mauer) und Sumpfzombie (Nordosten OG2). Sprach man mit einem, versperrte man sich den Dialog mit dem jeweils anderen.
- **Asgars Schloss**: Switch-Kollision zwischen Skelettgardist (Westliche Mauer), Bira (Südosten OG2, Küche) und einer Dämonin (Östlicher Gang, OG2). Hier versperrte man sich ebenfalls Dialoge der anderen, wenn man mit einer Person sprach.
- **Asgars Schloss**: Weitere Switch-Kollision zwischen dem Feierabend-Elitekrieger (außerhalb des nördlichen Tores) und dem NPC vor dem Magierzimmer.
- **Asgars Schloss**: Der Code, der den Hintergrund des Schlosses anpasst (wählbar bei dem Welle2-Sensenzauberer neben Jinnall) war verbuggt, sodass die vorherigen Auswahlen nie zurückgesetzt wurden und die vorherigen Optionen immer die nachgereihten überschrieben.
- **Asgars Schloss**: Fehlerhafte Item-Prüfung bei Blutherz. Hier benötigte man nur 4 anstatt der gefragten 5 Blutelexiere.
- **Asgars Schloss**: Fehlerhafte Item-Prüfungen beim Ghoul, der die Movement Speed der Fledermausverwandlung erhöhen kann 
- **Asgars Schloss**: Beim Ansprechen eines der Elitekrieger (Welle 2) gibt dieser dem Spieler 3 Monster-Essenzen. Es wurde hier allerdings nur eine Nachricht angezeigt und die Items nicht dem Inventar hinzugefügt.
- **Asgars Schloss**: Nachdem Asgar der pissenden Katze an den Kragen will, sollte Alaine ihn eigentlich davon abhalten, ihr noch einmal näherzukommen. Man konnte sich aber einfach in eine Fledermaus verwandeln und diese Schranke umgehen, worauf die Katze schlicht nicht mehr ansprechbar war.
- **Asgars Schloss**: Wenn man bei Jinnall die zweite Welle beschwörte, war ein verstecktes Geheimnis im Nordosten des Schlosses nicht mehr zugänglich.
- **Asgars Schloss**: Wenn man im Thronsaal als Asgar den Thron aktiviert und eine der Optionen wählt, springt die Schleife fälschlicherweise zu einer Stelle zurück, die für Valnar vorhergesehen war. So wurde anschließend beim "Flexen" Valnars Faceset angezeigt, auch wenn man ihn noch nicht in der Party hat.
- **Asgars Schloss**: “Diabolisch” lachen im Thronsaal zeigte eine Nachricht an, dass man 10 Filar erhalten hat, nahm dem Spieler stattdessen aber 10 Filar weg.
- **Asgars Schloss**: Wenn man im Schloss der Meerjungfrau zuhörte, wurde, damit es nicht regnete, der Tag-Nacht-Wechsel und damit die Uhr des Spiels komplett deaktiviert. Anschließend wurde die Funktion aber nicht mehr wiederhergestellt. Nun wird ausschließlich der Regen deaktiviert und die Spielzeit läuft während des Gesangs sogar etwas beschleunigt weiter.
- **Asgars Schloss**: Ein aus Versehen gelöschtes, verstecktes Geheimnis im Thronsaal wurde wiederhergestellt.
- **Asgars Schloss**: Das Abschalten von Valnars Brille wird nun in sämtlichen seiner Grafiken im Spiel widergespiegelt.
- **Asgars Schloss**: Nutze man das Angebot der Harpyie, um zu einer Stadt zu fliegen, passierte nichts, wenn man “Herlis” auswählte. Außerdem wurde der Dialog verbessert und beschränkt sich nun auf Städte, die man bereits auf normalem Weg entdeckt hat.
- **Asgars Schloss/Magierzimmer**: Magielernsystem Boost (Lv50): Bei dem Boost an Ayshas Maschine wurde fälschlicherweise geprüft, ob Valnars Level auf 50 ist.
- **Asgars Schloss/Gruft**: Die Speisekammer (Mod) konnte während der Zettelsuche bereits betreten werden, obwohl Valnar eigentlich keinen Schlüssel hat.
- **Schloss Tranak**: Dialogfehler: Machte man sich das Schloss Tranak nach dem Sieg über Gerald eigen, erwähnte Asgar Jinnall, auch wenn man diesen nicht beschworen hat.
- **Schloss Tranak**: Nachdem man Schloss Tranak eingenommen hatte, konnte man sich dort weiterhin nicht verwandeln. Fledermaus- und Wolfsverwandlung werden nun in der Tranak-Basis nicht mehr blockiert.
- **Schloss Tranak**: Wenn man das Schloss einnahm und im oberen Stockwerk versuchte, das Lager auszuräumen, wurde man weiterhin von der Wache aufgehalten, wenn man diese zuvor nicht getötet hatte, obwohl sie nicht mehr da war.


### Städte, Quests, etc.

- **Magiegebirge**: Wenn man das Djinnbuch im Magiegebirge entdeckte, nannten Valnar und Alaine Abraxas’ bei seinem Namen, auch wenn man den Kommunikationsapparat noch nicht bedient hatte. (Wodurch die zwei eigentlich zum ersten Mal seinen Namen erfahren. Davor weiß es nur der Spieler, über Opas Erzählung)
- **Shannar**: Erster Encounter mit Clare war falsch geskriptet, sodass sie nie in Shannar nach der Hinrichtung auftauchte, außer man verwendete den Introskip.
- **Melsan**: Kondition für speziellen Boss-Encounter angepasst: Wenn man nach dem Absuchen des Magiegebirges mit Asgar und Alaine zurück beim Schloss ankommt, kann man vor dem Betreten noch auf die Weltkarte zurück und Melsan besuchen (unverändert). Hier gab es allerdings nach der Feuertaufe einen speziellen Encounter, der, nachdem die Truppe wieder vollständig war, verfügbar sein sollte. Versuchte man diesen vor dem Sieg über Sir Esthir zu erreichen, bekam man allerdings weiterhin die Meldung von Valnar, dass er zurück zum Schloss müsse.
- **Melsan**: Eine Dialog-Skip-Möglichkeit übersprang hier zwei Stellen, an denen man seine Mensch- oder Unmenschlichkeit beweisen konnte.
- **Asran**: In der Kirche in Asran wurden Verfluchungen für die neuen möglichen Partymitglieder nicht aufgehoben.
- **Asran**: Beim Aussaugen des Peitschenhändlers in Asran wurde die Animation auf das falsche Event-Ziel angewendet.
- **Tradan (Aysha-Pfad)**: Beim Aussaugen des Peitschenhändlers in Tradan wurde die Animation auf das falsche Event-Ziel angewendet.
- **Herlis**: Wenn man die Frau in Herlis, die die Bruder-Holen-Quest vergibt, tötete, tauchte plötzlich neben ihr ihr Bruder auf, wenn man ihn noch nicht geholt oder wenn man die Quest abgelehnt hatte.
- **Abraxas’ Turm**: Wählte man den Vanilla-Pfad, in dem Aysha vernichtet wird, wurde man nach dem Sieg über Abraxas und der anschließenden Opa-Simon-Sequenz wieder direkt in den Turm zurück teleportiert, den man eigentlich gerade verlassen hatte.
- **Abraxas’ Turm**: Wählte man den Aysha-Pfad, wurde man nach dem Sieg über Abraxas und der anschließenden Opa-Simon-Sequenz, erst in Valnars Zimmer im Schloss und anschließend aber wieder zurück in den Turm, den man gerade verlassen hatte, teleportiert.
- **Abraxas’ Turm**: Unabhängig davon, welchen der Pfade man wählt, konnte man sich direkt nach Verlassen von Abraxas' Turm mit Zuflucht in Asgars Schloss teleportieren und so die Sequenz mit Simon & Opa überspringen.
- **Abraxas’ Turm**: Es gab beim Aysha-Pfad außerdem einen Fall, bei dem das Spiel nach dem Teleport ins Schloss schwarz blieb, wenn man Ayshas Klennar-Quest nicht vollendet hatte.
- **Asran Fluss**: Monster wurden nicht resettet.

### Endgame, Postgame, NG+

- **Endgame**: Bei einer Truppenprüfung im finalen Dungeon lief Valnar im Falle, dass er Asgar und/oder Alaine im Schloss gelassen hat, gegen die Wand. Je nach Feld, wurde das Spiel entweder softgelocked, oder man konnte die Prüfung einfach überspringen und Vincent solo gegenübertreten.
- **Endgame**: Der Fluchtcounter wurde bei der Wahl des erspielten Endes überhaupt nicht mehr berücksichtigt. Es musste nur noch Alaines Zuneigung mindestens 2 betragen. Nun ist die Prüfung davon abhängig, ob man den neuen Everlasting-Reign Content in den Einstellungen aktiviert.
- **Endgame**: Es ist nun wieder möglich, die originalen Endgame-Level zu spielen
- **Enden/Ende 2**: Änderungen an der Thronsaal-Map waren in der Endsequenz nicht sichtbar.
- **Postgame**: Einige Schalter wurden nicht zurückgesetzt, was beim erneuten Erspielen einige Fehler in den Sequenzen auslöste. (zB. Uruya-Puff-Sequenz oder Asgar-Wiederbelebung)
- **Postgame**: Wenn man Jinnall nicht beschworen und Permabeschwörungen nicht aktiviert hatte, gab es keine Möglichkeit mehr, Asgar oder (je nach Ende) Alaine wieder ins Team zu bekommen.
- **Postgame**: Fehlende Bossgrafik bei Jinnais Versteck
- **Postgame**: Fehlende Bossgrafik bei Beas Haus
- **Postgame**: Bei Beas Haus war es möglich, über das Spielmenü zu speichern.