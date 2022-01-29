---
title: "Tag 2 - Funktion und Aufbau von Archivsystemen Teil 1"
date: 2021-09-30
---

**Liebes Tagebuch,** heute starten wir mit dem Thema Funktion und Aufbau von Bibliothekssystemen ½.
Daher gibt es viel spannendes zu berichten aus diesem Unterricht.
Als kleine Wiederholung haben wir uns nochmals MARC21 angeschaut, diese wurde von der Library of Congress begründet im Jahr 1999. Wieso ist es wichtig MARC21 zu kennen? Koha welches wir hier nutzen werden und auch alle anderen grossen Bibliothekssysteme basieren darauf oder unterstützen es als Austauschformat. Was in den nächsten Jahren jedoch kommen wird ist wahrscheinlich die Ablösung durch BIBFRAME, welches auf RDF basiert.
 
Dieses Modell von BIBFRAME ist als RDF-Ontologie dargestellt. 

Wir haben dann eine Übung gemacht in der wir **MARC21** mit **Dublin Core** verglichen haben. Dublin Core ist noch zu erwähnen, ist ein Standard der als kleinster gemeinsamer Nenner gilt. Über die SRU-Schnittstelle von Swisscovery haben wir die Daten einmal je Format geladen um sie zu vergleichen. Über die SRU-Schnittstelle wurde noch nichts erklärt, das folgt aber noch.
Die Erkenntnisse der Klasse waren:
-	MARC21 hat mehr Elemente und ist ausführlicher
-	Bei Dublin Core haben die einzelnen Felder und ihre Unterfelder jeweils eigene Namen, bei MARC21 wird das über datafield und subfield mit den entsprechenden Codierungen geregelt.
-	Dublin Core erschein kompakter und übersichtlicher
-	MARC21 arbeitet mehr mit Attributen
-	Und weitere
Wichtig bei dieser Aufgabe war auch das wir einmal sehen wie MARC21 aussieht und ein bisschen ein Gefühl dafür bekommen, da wir auch später im Modul noch einige male darauf stossen.

Der Nächste Programmpunkt war nun die Einführung in **Koha**.
Koha ist ein weltweites Open Source Projekt und wurde im Jahr 1999 gegründet, hier kommt man auf die Webseite von Koha,  https://koha-community.org.
Mittlerweile bieten auch grössere Unternehmen Zusatzdienstleistungen zu Koha an, somit ist es dann eine Kombination von Open Source und Dienstleistung. Das ist eine sogenannte Mischform, alle tragen bei auch die Unternehmen, und man bezahlt dann nicht für die Lizenzen sondern die Dienstleistungen. Ich finde das durchaus ein spannender Ansatz, was Koha sicher auch für kleinere Bibliotheken interessant macht die nicht auf ein Produkt angewiesen sind welches von einem Verbund vorgegeben wird. Sondern können sich dort dieser Open Source Variante bedienen und finanzielle Mittel dann eher in die Trainings aus solchen Dienstleistungsangeboten stecken.

Um Koha nutzen zu können, haben wir es auf unseren Virtuellen Maschinen installiert. Die Anleitung dazu ist im Skript des Moduls: https://bain.felixlohmeier.de/#/02_funktion-und-aufbau-von-bibliothekssystemen
Die offizielle Anleitung ist etwas kompliziert aufgebaut und daher für den Kurs etwas übersichtlicher zusammengestellt worden durch die Dozenten. Ebenfalls ist sie auf Ubuntu, welches wir mit unseren Virtuellen Maschinen nutzen, ausgelegt. Ein grossteil der Anleitung besteht aus vielen einzelnen Befehlen die man in die Komandozeile der reihe nach kopiert um zuletzt ein Passwort zu erhalten.
Wenn die Installation erfolgreich war, sollte nun diese Webseite (http://bibliothek-intra.meine-schule.org) im Browser auf der virtuellen Maschine aufrufbar sein sollte.
Für die nächsten Schritte arbeiten wir mit einem Tutorial von Stephan Tetzel, das hier ist der Link auf die Deutsche Version davon:  https://zefanjas.de/wie-man-koha-installiert-und-fuer-schulen-einrichtet-teil-1/
Den ersten Teil der Grundinstallation haben wir jetzt bereits im Unterricht gemacht, wie man Koha aber weiter einrichtet kann man dort übernehmen und zu Hause umsetzen. Das ist dann auch schon die Hausaufgabe auf das nächste Mal, das 1. Kapitel durchmachen, für die weiteren Schritte haben wir am Anfang der nächsten Unterrichtseinheit noch etwas Zeit, da wir heute nicht ganz soweit gekommen sind.

Ich hoffe du fandest es auch so spannend wie ich heute, mach es gut und bis zum nächsten Mal,
Joy
