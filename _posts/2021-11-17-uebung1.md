---
title: "ArchivesSpace Import / Export Übung"
date: 2021-11-17
---

# ArchivesSpace Import / Export Übung

## Import
Die erste Aufgabe bestand darin, ein EAD-Beispiel herunterzuladen und in ArchivesSpace hochzuladen. Die erste kleinere Hürde stellte der Download der XML-Datei dar. Anders als gewohnt war diese nicht über einen Button downloadbar, sondern direkt als Datei verlinkt. Damit ich diese lokal auf meinem Rechner verwenden konnte, kopierte ich den Code ins Notepad und speicherte die Datei mit dem XML-Suffix. Beim Vergleich fiel auf, dass im Browser die ersten beiden Zeilen nicht angezeigt werden. Darin werden die XML-Version, das Encoding der Doctype und die DTDs beschrieben. Es gab also einen Informationsverlust. Ich wurde diesbezüglich eines Besseren belehrt: Mit Rechtsklick kann das Kontextmenü aufgerufen und anschliessend die Option «Ziel speichern als» gewählt werden kann. Dies ermöglicht eine verlustfreie Übernahme der Daten.

## Export
Die eben eingelesenen Daten sollen nun als MARCXML exportiert und mit dem Eintrag in ArchivesSpace verglichen werden. Um die zu überprüfen, ob es bei der Konvertierung Verlust gab, setzte ich vor allem auf die Browsersuchfunktion (ctrl-f).

### Erkenntnisse:
-	Daten aus dem Abschnitt «Finding Aid Data» ist in MARCXML nicht auffindbar.
-	Vom Abschnitt «Notes» ist nicht alles auffindbar.
-	Fliesstext ist ersichtlich, der Rest ist wahrscheinlich über Indizes, Attributen und Tags codiert.
Selbst wenn im MARCXML-File nicht alles von Auge ersichtlich ist, vermute ich, dass es sich um einen verlustfreien Export handelt. Ein Import der MARCXML-Datei erstellte leider keine neue Ressource. Spannend wäre es, das heruntergeladene File so zu bearbeiten, dass es als neue Ressource in ArchivesSpace eingelesen werden kann. Somit könnte ein direkter Vergleich gemacht werden.
