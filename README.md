# About my first project on GitHub
 
Dies ist eine einfache grafische Taschenrechner-Anwendung, die mit Python und der Bibliothek Tkinter erstellt wurde. Sie dient zur Durchführung der vier Grundrechenarten in einer übersichtlichen Benutzeroberfläche.

# Funktionen

Der Rechner bietet folgende mathematische Operationen:

Addition (+): Addiert die beiden eingegebenen Zahlen.

Subtraktion (-): Subtrahiert die zweite Zahl von der ersten.

Multiplikation (*): Multipliziert die beiden eingegebenen Zahlen.

Division (/): Dividiert die erste Zahl durch die zweite.

# Voraussetzungen

Um die Anwendung auszuführen, benötigst du:

Python 3.x

Die Bibliothek Tkinter (standardmäßig in Python enthalten).

Das Tool uv (für die Verwaltung der virtuellen Umgebung).

# Starten der Anwendung

Navigiere in deinem Terminal in das Hauptverzeichnis des Projekts und führe folgenden Befehl aus:

Bash

uv run python src/mini_calc/app.py

# Bedienung

Geben Sie die erste Zahl in das linke Eingabefeld ein.

Geben Sie die zweite Zahl in das rechte Eingabefeld ein.

Klicken Sie auf einen der Operator-Buttons (+, -, * oder /).

Das Ergebnis wird sofort in der Zeile unter den Eingabefeldern angezeigt.

# Fehlerbehandlung

Das Programm ist so konzipiert, dass es typische Fehler abfängt:

Ungültige Eingabe: Wenn Buchstaben statt Zahlen eingegeben werden, wird ein entsprechender Hinweis angezeigt.

Division durch Null: Falls versucht wird, durch 0 zu teilen, gibt der Rechner die Meldung "Fehler: ÷0" aus.
