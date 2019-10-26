# Erläuterung Eintrittskartenerstellung

Nachfolgend wird beschrieben, wie man zum fertigen druckbaren PDF mit nummerierten Eintrittskarten für eine Veranstaltung kommt.

# Schritt 1 - Grafik der Eintrittskarte erstellen

Mit Gimp ist ein einfaches Layout der Eintrittskarte definiert. Darin ist in einer eigenen Ebene noch das bearbeitbare Textfeld. Dieses kann vom letzten Event einfach angepasst werden.

Der Export kann dann in PNG erfolgen. Die Gimp-Datei für die neue Eintrittskarte ist in das Repository einzuchecken.

# Schritt 2 - Seitenlayout einer Karte erstellen

In der Datei *Eintrittskarten-Layout-Template.odt* ist das Seitenlayout so eingestellt, dass eine Seite exakt die Größe der Eintrittskarte hat.
So kann die exportiere PNG-Grafik als Hintergrundbild gesetzt werden.
Die Nummerierung ist mit der Fußzeilen-Funktion umgesetzt. Diese setzt voraus, dass es keine Überlagerungen mit der Hintergrundgrafik der Eintrittskarte gibt. Werden mehr Eintrittskarten benötogt, müssen einfach weitere Seiten angelegt werden.

Diese Datei ist nicht einzuchecken, da Sie jedes mal nur als Erstellvorlage für die eigentlich druckbare Eintrittskartendatei dient.

# Schritt 3 - Druckbares Layout für alle Eintrittskarten erstellen

Der eigentliche Trick, um auf eine Seite viele Eintrittskarten neben- und untreinandr anzuordnen ist, die PDF-Druckfunktion geschickt zu nutzen:

1. Gehe auf Drucken.
2. Wähle *Drucken in Datei*.
3. Konfiguriere 16 Seiten pro Druckseite.
4. Konfiguriere eine Trennlinie, die als Schnittmerkierung dient.
5. Drucken.

Siehe da, wir haben eine PDF, die x Eintrittskarten pro Seite nummeriert anordnet.
