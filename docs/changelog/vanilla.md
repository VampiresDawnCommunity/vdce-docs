 
# Bugfixes allgemein

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