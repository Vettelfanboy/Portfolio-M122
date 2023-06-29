# Input-Output M122

Einleitung/Aufgabenstellung:

In diesem Portfolio werde ich Input-Output in PowerShell beschreiben. Als Beispiel habe ich den Auftrag LA_122_1707 gelöst. Hier ging es darum, Benutzerdaten einzulesen und diese formatiert auszugeben.

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

Hier geht man Schritt für Schritt vor. Bei Anforderung 1 kann der Benutzer noch nichts eingeben, hier wird nämlich mittels "Write-Host" und "Get-Date" die Begrüssung und das heutige Datum ausgegeben. Ab Anforderung 2 ist aber alles in eine "try-catch-Schleife" verpackt, um Fehler abzufangen. Zuerst wird man nach einer Zeitverzögerung gefragt und dann kommen schliesslich die Abfragen über die detaillierten Benutzerdaten. Für die Zeitverzögerung ist der Parameter "Start-Sleep" zuständig. Je nachdem wie lange die Zeitverzögerung ist, so lange macht das Skript auch nichts. Ich habe auch noch die Zeitverzögerung so angepasst, dass nur ganze Zahlen akzeptiert werden und somit werden Fehleingaben eingefangen. Die Benutzerdaten wie Nachname, Vorname etc. müssen in einer Variable gespeichert werden und mittels "Read-Host" werden die entsprechenden Sachen abgefragt. Zuletzt kommt natürlich noch der Output, und hier werden die Daten formatiert, indem man alle Variablen miteinander zusammensetzt. Leider konnte ich die Sache mit dem Notepad nicht umsetzen und der catch-Block funktioniert auch nicht.

Bild vom Code:

![Screenshot 2023-06-29 123124](https://github.com/Vettelfanboy/Portfolio-M122/assets/110892495/226d9fbf-c8ed-41ac-8944-93807d7a36dd)

Ausgabe:


![Screenshot 2023-06-29 124632](https://github.com/Vettelfanboy/Portfolio-M122/assets/110892495/51cd8edd-2154-4468-bbf0-f10c37756ab0)

Reflexion:

Dieses Thema war für mich sehr logisch, da ich zu diesem Zeitpunkt immer besser wusste, was diese verschiedenen Variablen auf sich haben und wie die Kontrollstrukturen aufgebaut sind. Die Bildung der Kontrollstrukturen war auch keine grosse Sache, da ich das ja bereits aus dem Modul 319 kannte. Für einige Sachen musste ich zwar ChatGPT fragen, aber auch diese Sachen von der KI habe ich schnell verstanden. Generell fand ich es an dieser Aufgabe spannend zu sehen, dass sich die Kontrollstrukturen in einer Skriptsprache gar nicht so sehr unterscheiden von den Kontrollstrukturen in einer Programmiersprache. Dies war definitiv eine der leichteren Aufgaben in diesem Modul, da dies zum grössten Teil Repetition war. Wie aber oben bereits erwähnt bei der Themenbeschreibung lief auch dies nicht ganz problemlos ab.



