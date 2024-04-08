 
# Bugfixes Everlasting Reign

## Neu hinzugefügt

TODO: auf neue Inhalte von Yoraiko eingehen

## Allgemein Technisches, Items & Skills

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


## Neuer Content in Schloss/Basen/neue NPCs

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


## Städte, Quests, etc.

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

## Endgame, Postgame, NG+

- **Endgame**: Bei einer Truppenprüfung im finalen Dungeon lief Valnar im Falle, dass er Asgar und/oder Alaine im Schloss gelassen hat, gegen die Wand. Je nach Feld, wurde das Spiel entweder softgelocked, oder man konnte die Prüfung einfach überspringen und Vincent solo gegenübertreten.
- **Endgame**: Der Fluchtcounter wurde bei der Wahl des erspielten Endes überhaupt nicht mehr berücksichtigt. Es musste nur noch Alaines Zuneigung mindestens 2 betragen. Nun ist die Prüfung davon abhängig, ob man den neuen Everlasting-Reign Content in den Einstellungen aktiviert.
- **Endgame**: Es ist nun wieder möglich, die originalen Endgame-Level zu spielen
- **Enden/Ende 2**: Änderungen an der Thronsaal-Map waren in der Endsequenz nicht sichtbar.
- **Postgame**: Einige Schalter wurden nicht zurückgesetzt, was beim erneuten Erspielen einige Fehler in den Sequenzen auslöste. (zB. Uruya-Puff-Sequenz oder Asgar-Wiederbelebung)
- **Postgame**: Wenn man Jinnall nicht beschworen und Permabeschwörungen nicht aktiviert hatte, gab es keine Möglichkeit mehr, Asgar oder (je nach Ende) Alaine wieder ins Team zu bekommen.
- **Postgame**: Fehlende Bossgrafik bei Jinnais Versteck
- **Postgame**: Fehlende Bossgrafik bei Beas Haus
- **Postgame**: Bei Beas Haus war es möglich, über das Spielmenü zu speichern.