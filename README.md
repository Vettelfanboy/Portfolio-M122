# Input-Output M122

Einleitung/Aufgabenstellung:

In diesem Portfolio werde ich Input-Output in PowerShell beschreiben. Als Beispiel habe ich dne Auftrag LA_122_1707 gelöst. Hier ging es darum, Benutzerdaten einzulesen und diese formatiert auszugeben.

Thema/Produkt:

Die Anforderungen waren folgende:
1.	Das Skript begrüsst den Benutzer und gibt das aktuelle Datum aus.
2.	Das Skript fragt den Benutzer nach einer Zeitverzögerung in Sekunden
3.	Danach wartet das Skript so lange.
4.	Anschliessend startet Notepad.
5.	Anschliessend liest das Programm folgende Werte vom Benutzer ein:
a.	Nachname
b.	Vorname
c.	Strasse
d.	Nummer
e.	PLZ
f.	Ort

Hier geht man Schritt für Schritt vor. Bei Anforderung 1 kann der Benutzer noch nichts eingeben, hier wird nämlich mittels "Write-Host" und "Get-Date" die Begrüssung und das heutige Datum ausgegeben. Ab Anforderung 2 ist aber alles in eine "try-catch-Schleife" verpackt um Fehler abzufangen. Zuerst wird man nach einer Zeitverzögerung gefragt und dann kommen schliesslich die Abfragen über die detaillierten Benutzerdaten. Für die Zeitverzögerung ist der Parameter "Start-Sleep" zuständig. Je nach dem wie lange die Zeitverzögerung ist, so lange macht das Skript auch nichts. Die Benutzerdaten wie Nachname, Vorname etc. müssen in einer Variable gespeichert werden und mittels "Read-Host" werden die entsprechenden Sachen abgefragt.  
