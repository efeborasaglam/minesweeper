# Minesweeper
 
## Vision
 
Für alle, die sich nach einer unterhaltsamen Herausforderung sehnen, erstellen wir ein beeindruckenden Minesweeper-Spiel.
Dieses Spiel, basierend auf einer Konsolenanwendung, bietet eine benutzerfreundliche Oberfläche und verschiedene Schwierigkeitsstufen. Unser Ziel ist es, ein Minesweeper zu schaffen, das von jedem verstanden wird unfd gut spielbar ist.


## Reflexion

### Wie haben Sie das Lösen des Auftrags erlebt:

Wir sind sehr systematisch vorgegangen, indem wir uns die Aufgaben geteilt haben. Glücklicherweise konnten wir nie zur selben Zeit arbeiten. Ja, glücklicherweise, denn so konnten wir immer mit dem aktuellen Code arbeiten, und die Person, die zuvor gearbeitet hat, konnte ihren Code immer ins Repository pushen. Da Daniel und ich schon mehrmals zusammen gearbeitet haben, konnten wir die Aufgaben gut untereinander aufteilen. Schon bei den ersten Aufgaben, also den User Stories, konnten wir uns gut verstehen und aufeinander verlassen. Daniel bearbeitete 5, ich bearbeitete 5 User Stories. Wenn es Konflikte gab, führten wir ein kurzes Gespräch und suchten nach einem Kompromiss. Bei den Klassendiagrammen und den Sequenzdiagrammen haben wir die Aufgaben wieder geteilt und problemlos gelöst. Wir trugen sie gegenseitig vor und lösten auftretende Konflikte. Bei der Implementierung sind wir wieder gleich vorgegangen: Daniel erstellte das Modell und die anderen Klassen, und ich hatte den Auftrag, das Skelett mit Leben zu füllen, indem ich alles sichtbar machte. Wenn wir irgendwelche Probleme hatten, haben wir uns immer gegenseitig benachrichtigt, und der andere konnte sich eine Pause gönnen. Schlussendlich haben wir eine gute Leistung erbracht und sind stolz darauf.


### Inwieweit haben Ihnen die vermittelten Methoden bei der Lösung des Auftrags geholfen? Wo haben Sie die Methoden behindert? Begründen Sie!

Da wir während des Unterrichts immer wieder Aufgaben lösen mussten, haben wir einiges daraus gelernt. Die Hausaufgaben waren auch stark von Minesweeper beeinflusst, da wir immer ähnlich vorgehen wollten wie bei den Aufgaben. Bei der Implementierungsaufgabe hatten wir geübt, wie wir Methoden aus verschiedenen Klassen aufrufen können. Mit dem Klassendiagramm für das Smarthome haben wir gelernt, wie man Klassendiagramme erstellt, allerdings haben wir dies etwas vernachlässigt und ein kleineres erstellt. Bei der Implementierung wollten wir möglichst ähnlich wie beim Strategy Pattern vorgehen, mussten jedoch einige kleine Hindernisse überwinden. Dank des Minesweeper-Projekts konnte ich auch zusätzliches Lernen, was ich während der Aufgaben nicht gut umgesetzt hatte, wie beispielsweise beim Sequenzdiagramm. Zusätzlich wollten wir auch das Wissen aus vorherigen Aufgaben umsetzen, wie zum Beispiel bei den User Stories


### Was nehmen Sie aus dem Modul mit für die Zukunft?

In diesem Modul haben wir eine gute Gelegenheit erhalten, eine Vertiefung des Moduls M320 vorzunehmen und unser Wissen für die Zukunft zu erweitern. Wenn wir ins Detail gehen müssen, fand ich es gut, dass wir immer beim Thema geblieben sind und die objektorientierte Programmierung effektiv behandelt haben. Die objektorientierte Programmierung ist ein wichtiges Grundgerüst für die Zukunft, da heutzutage die beliebtesten und am häufigsten verwendeten Programmiersprachen die objektorientierte Programmierung verwenden. Diese Fähigkeiten sind von unschätzbarem Wert, da sie uns ermöglichen, komplexe Probleme auf strukturierte und effiziente Weise anzugehen und Lösungen zu entwickeln, die den Anforderungen moderner Softwareentwicklung gerecht werden

## Testkonzept für die Minesweeper-Logik
### Ziel
Sicherstellen, dass die Minesweeper-Logik korrekt implementiert ist und alle Funktionen ordnungsgemäß funktionieren.

## Testfälle

1. PlaceMinesTest
Überprüft, ob Minen gemäß den Spielregeln platziert werden.
Erwartetes Ergebnis: Die Anzahl der platzierten Minen entspricht der im Level festgelegten Anzahl.

2. MakeMove_NoBombTest
Überprüft, ob das Spiel korrekt auf einen Zug reagiert, der keine Mine trifft.
Erwartetes Ergebnis: Das Feld, auf das der Zug gemacht wurde, enthält keine Mine.

3. MakeMove_FieldUncoveredAfterMoveTest
Überprüft, ob das Feld nach dem Zug aufgedeckt ist.
Erwartetes Ergebnis: Das Feld, auf das der Zug gemacht wurde, ist aufgedeckt.

4. UndoTest
Überprüft, ob der letzte Zug erfolgreich rückgängig gemacht wird.
Erwartetes Ergebnis: Das Feld, das zuvor aufgedeckt wurde, wird wieder verdeckt.

5. Undo_RestorePreviousGameStateTest
Überprüft, ob der vorherige Spielzustand nach dem Rückgängigmachen eines Zuges wiederhergestellt wird.
Erwartetes Ergebnis: Das Feld, das zuvor aufgedeckt wurde, ist wieder verdeckt, und die Anzahl der benachbarten Minen ist dieselbe wie zuvor.

6. ResetTest
Überprüft, ob das Zurücksetzen des Spiels den Spielzustand korrekt zurücksetzt.
Erwartetes Ergebnis: Nach dem Zurücksetzen sind alle Felder verdeckt und es gibt keine Minen auf dem Spielfeld.
