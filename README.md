Programmiervorkurs
==================

Dieses Repository enthält das Skript, die Begrüßungs- und Abschiedsfolien und
die nötigen C++-Dateien für den C++-Vorkurs der Fachschaften Mathematik und
Informatik der Universität Heidelberg.

Makefile
--------

Das Makefile stellt die folgenden Befehle bereit:

    make all - Erstellt das Skript und räumt die temporären Dateien auf
    make script - Erstellt das Skript  
    make folien - Erstellt die Folien für den Anfang und Ende des Kurses
    make clean - räumt mit allen temporären Dateien auf  
    make dir - erstellt das Vorkurs-Verzeichnis  (Skript wird gegebenenfalls vorher erstellt)
    make nodir - löscht das Vorkurs-Verzeichnis  
    make zip - erstellt ein zip-file um es online zu stellen  

Skript
------
Die Datei `vorkurs.tex` enthält die grundlegenden Paket- und
Befehlsdefinitionen sowie das Vorwort des Skripts. Die Datei `vorkurs.cls`
enthält die zugrundeliegende Klasse für das Dokument.

Im Ordner `kapitel` liegen die Texte für die einzelnen Lektionen aufgeteilt in die jeweiligen Kapitel `basics`und `classes`.
Diese werden jeweils in den Dateien `intro.tex` eingebunden.

Im Ordner `files` liegen die cpp-Dateien ebenfalls auch in die beiden Kapitel aufgeteilt.
Die Dateien werden zum einen ins Skript eingebunden und zum anderen genutzt werden um den `vorkurs`-Ordner anzulegen.

Folien
------
Um die Folien für den Begrüßungsvorschlag zu bauen müssen im Ordner `folien`
die beiden Dateien `accounts.tex` und `passwort.tex` angelegt werden, die genau
die Accountnamen sowie das Passwort enthalten sollten.

Vorkurs
-------
Für den Vorkurs werden die folgenden Dinge benötigt:
* Genügend Rechner mit beliebiger Linux-Distribution für alle Teilnehmenden
* Der Ordner `vorkurs` auf sämtlichen diesen Rechnern
* Die aktualisierten Folien für den Begrüßungs- und Abschiedsvortrag

Lizenz
------
Dieses Skript ist lizensiert unter einer Creative Commons
Namensnenung - Weitergabe unter gleichen Bedingungen 4.0 International
Lizenz. Der Lizenztext findet sich in der [LICENSE](https://github.com/FachschaftMathPhys/Programmiervorkurs/blob/master/LICENSE.md)-Datei.
