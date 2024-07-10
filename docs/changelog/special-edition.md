
# Special Edition

## Allgemeine Infos

Die *"Special Edition"* von *Vampires Dawn* wurde ursprünglich von *Plasquar* erstellt und war Teil der [“Special Mega Aysha Everlasting Reign” Edition](everlasting-reign.md), auf welcher die *Community Edition* aufbaut.

Auf dieser Seite werden einige Fixes & Anpassungen, welche die *SE* betreffen, näher erläutert. Diese sind allerdings obsolet, da die *SE*-Inhalte auf Anfrage von *Plasquar* wieder entfernt wurden.

- [Original-Vorstellung & Download-Link auf vampiresdawn.org](https://www.vampiresdawn.org/forum/viewtopic.php?t=41416)
 
## Entfernung der SE-Inhalte

Die zusätzlichen Inhalte der SE sind in diesem Release (obwohl es auf Version 1.1 der *“Special Mega Aysha Everlasting Reign” Edition* aufbaut) nicht mehr inkludiert. Ich (*Spatzenfärber*) hatte die Hoffnung, diese Inhalte unverfälscht und mit denselben technischen Verbesserungen und der erweiterten Customizability, sowie erstmals auch in englischer Übersetzung, inkludieren zu können. Einige aus späteren VD-Teilen bekannte Features wie **Random Loot**, **Overworld Enemy Encounters** und **Orts-Flaggen** auf der Weltkarte wurden aber in verbesserter Form neu implementiert. ([siehe Changelog](../index.md#neue-features))

Da dieses Projekt ursprünglich als reines Bugfixing Release (Version 2.0) der *“Aysha Everlasting Reign” Edition* angedacht war und sich sonst eigentlich nur auf kleinere, neue *“Quality of Life”*-Features beschränkte, hielt ich es nicht für nötig, die ursprünglichen Entwickler außer **Yoraiko** selbst zu kontaktieren. Im Frühjahr 2023 wurde dann der geplante Umfang der Edition noch etwas erweitert, was nach einigen Chats im VD-Discord die Aufmerksamkeit von **Plasquar** auf sich zog. Ihn irritierte, dass seine *Special-Edition*-Inhalte in dieser Version enthalten waren und er bat mich, diese wieder zu entfernen, was ich unter dem Aspekt, dass diese neue Edition nun unter einem neuen Titel und mit neuen Features erscheinen würde, auch bereitwillig tat.

Dass er aber ursprünglich **Yoraiko** die Erlaubnis gab, auf seiner SE-Version aufzusetzen, und diese später nach Release wieder entziehen wollte und ein Offline-Nehmen der *“Aysha-Everlasting-Reign”-Edition* forderte, finde ich nicht in Ordnung. Für mich persönlich als technisch versierten Entwickler, war es nicht viel Aufwand, die betroffenen Inhalte in meinem Code aufzuspüren und zu entfernen. (Ein Großteil davon ließ sich auch automatisiert unter Zuhilfenahme der liblcf-Tools des *EasyRPG-Teams* bewerkstelligen.)

Für *Yoraiko*, der nicht aus der IT-Branche kommt, gleicht so eine Forderung aber einem Todesurteil für sein Projekt.

***~ Spatzenfärber***

## Bugfixes (obsolet)

- **Items**: Die Ausrüstungs-Items Odosrüstung, Odoshelm und Harter Schild schützten zwar vor dem Element Feuer, nicht jedoch von dem in der SE neu eingeführten “Brennen”-Status.
- **Shannar**: Manche Tötungsdelikte in Shannar reduzierten den Zähler der Einwohner nicht.
- **Asran**: Wenn man dem Kind in Asran die Clownsnase zeigte, wurde zwar der Geheimnis-Counter inkrementiert, aber kein Geheimnis-Text angezeigt.
- **Isthar**: Bei einem Geheimnis in einem Haus in Isthar wurde kein Geheimnis-Text ausgelöst.
- **Sanos**: Junge Frau in Sanos falsch geskriptet. Unter bestimmten Umständen wurde keine Animation beim Aussaugen abgespielt und keine Seele erhalten.
- **Sanos**: Nach dem ersten Besuch in Sanos konnte man sich bei jedem erneuten Betreten in der Stadt frei in Fledermaus oder Wolf verwandeln.
- **Sanos**: Überredete man die Frau in Sanos, nach Shannar auszuwandern und tötete daraufhin ihren Mann, konnte man das Haus nicht mehr verlassen, da man alle Zeugen töten musste, aber die Option dazu bei der Frau nicht mehr zur Verfügung stand.
- **Weltkarte**: Das Feuergebirge südlich von Melsan konnte bereits während des Intros entdeckt werden und wurde markiert, obwohl es nur mit Fledermausverwandlung erreichbar ist.
- Die Special Edition bietet einen **zusätzlichen Geist**, der nach Absorption die Heilungsrate erhöht. Allerdings teilte sich dieser den Switch mit einem der Geister aus Vanilla VD, was dazu führte, dass man nur einen der zwei absorbieren konnte.
- Bei einem **Geist in einem Schneewald** wurde kein Geheimnis-Text ausgelöst.
- Bei einem Geheimnis des **Schattenwald-Dungeons** wurde kein Geheimnis-Text augelöst.
- **Endgame**: 2 Truhen im Asran-Dungeon inkrementierten zwar den Geheimnis-Counter, lösten aber den Geheimnis-Text nicht aus
- **Intro/Enden**: In den Cutscenes, in denen die Kirche in Asdion als Schauplatz dient, war die bei der Special Edition hinzugefügte Keller-Treppe nicht sichtbar. Bei den Enden fehlten außerdem die Säulen.
- **Enden**: In den Endsequenzen, die im Magierzimmer stattfanden, war nur ein Pentagramm (Seelenassimilator) sichtbar. Mit der Special-Edition wurde hier allerdings mit dem Magieverlernsystem ein weiteres hinzugefügt.

## Anpassungen (obsolet)
- Diverse neue NPCs, die zuvor kein **Dialog-Menü** hatten, können nun ausgesaugt & getötet werden.
- Für das Meistern der neuen Quests & Herausforderungen wurden eigene **Trophäen** entworfen.
- **Asgars Schloss/Magierzimmer**: Magielernsystem Boosts (Lv50): Konnten bei jedem NG+ erneut erhalten werden, da die entsprechenden Schalter zurückgesetzt wurden.
- **Abraxas-Turm**: Herausforderung (ohne Zufluchtszauber bewältigen) wiederhergestellt. Everlasting Reign entfernte diese Option und machte es verpflichtend, den Turm ohne Zuflucht zu bewältigen.
- **Asran-Dungeon**: Feuerdämon teilte sich dieselbe Charset-Grafik mit dem Feuerdrachen-Boss und mit einem etwas passenderen Sprite ausgetauscht.
- **NG+**: Quest Items *"Linkes Fragment"*, *"Rechtes Fragment"* & *"Metallscheibe"* werden nun beim Starten eines neuen Spiels aus dem Inventar entfernt.