 
# Integration der englischen “Aysha-Edition”

## Allgemeine Infos

Ursprünglich für ein Übersetzungs-Update erstellt von *kj150*, welcher sich bereits zuvor für die englische Übersetzung von *Vampires Dawn* verantwortlich zeichnete.

Für die [“Special Mega Aysha Everlasting Reign” Edition](everlasting-reign.md) von *Yoraiko* ins Deutsche übersetzt.

Zwar wurde dieser Übersetzung, inkl. ihrer Änderungen, nie eine offizielle Versions-Nr. zugewiesen -da diese Inhalte aber mit dem zweiten **"Major Update"** der Übersetzung veröffentlicht wurden, werden sie als ***Version 3.0*** der Übersetzung dokumentiert.

- Ursprüngliche *"Version 1"* der engl. Übersetzung: **2012**
- Erstes größeres Update (*"Version 2"*) der engl. Übersetzung: **2016**
- Release des gemeinhin als *"Aysha Edition"* (*Version 3*) bekannten Updates: **2021**

Links: 

- [Original-Vorstellung der aktualisierten englischen Übersetzung in der *Steam Community*](https://steamcommunity.com/app/1361010/discussions/0/3057364366986799973/)
- [Backup des englischen Releases in der Datenbank von *rmachiv.de*](https://rmarchiv.de/games/70)

## Bugfixes (vgl. mit ER-Version)

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

## Fehlende Features in ER, die ergänzt wurden

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

