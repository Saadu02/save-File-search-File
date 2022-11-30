# Projekt-Dokumentation


Gruppennamen: Zettelkasten
Mitglieder: Sathana Suganthasri, Nicola Luca.Karrer, Brandon Spaqi und Mohammad Shahir.Bashiri

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |                                                   
|19.10.2022| 2.0.0   |Wir haben uns über Zettelkasten informiert.|
|26.10.2022| 2.0.0   |Wir haben uns über programmieren mit HTML informiert.|
|02.11.2022| 3.0.0   |Wir haben die Planung erstellt und Aufträge verteilt.|
|02.11.2022| 3.0.1   |angefangen mit Programmieren.|
|09.11.2022| 4.0.0   |PAP fertig erstellt.|
|09.11.2022| 4.0.1   |Design-mockup erstellt.|
|09.11.2022| 4.0.2   |Projektdokumentation aktualisiert (Realisierung + Planung + fehlende Funktionen eingefügt).|
|09.11.2022| 4.0.3   |Wir haben uns entschieden statt ein Website zu erstellen, in einem normales Programm zu erstellen. |
| 16.11.2022 | 5.0.0 | Suchoption Erfolgreich programmiert. |
| 23.11.2022 | 6.0.0 | FileUpload Erfolgreich programmiert | 
| 30.11.2022 | 7.0.0 | Programmieren abgeschlossen | 
| 30.11.2022 | 8.0.0 | projektdokumentation fertig erstelltn | 

## 1 Informieren
Ordner Suchen: Man hat verschiedene Text-Dateien in verschiedenen Ordner. Man kann nach diesen Dateien individuell die Such-Option benutzen. Hier kann man dann einen Begriff eingeben, der dann alle Dateien anzeigt, die diesen Begriff haben. 
Ordner Erstellen und Speichern: Man kann den Button Dokument erstellen drücken. Danach kann man den Ordenr auswählen, ein Text schreiben, die wird Automatisch im HTML umgewandelt. Dieses Dokument umbenennen und speichern.  

Ordner erstellen: 
Dateien hineinfügen ->
Ordner erstellen ->
Titel für Ordner ->
Datei&Ordner speichern ->
Begriff eingeben ->
Dateien anzeigen ->


### 1.1 Ihr Projekt

Das Programm soll zeigen, wo unsere Dateien gespeichert sind und man kann auch Ordner/Dokument erstellen.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |  muss               | Funktionalität     | Als ein User möchte ich eine Datei hinzufügen oder erstellen, damit ich mir mehr Wissen behalte. |
| 2    |  muss               | Funktionalität     | Als ein User möchte ich die möglichkeit ein Ordner zu erstellen, damit ich meine Dateien besser organisieren zu kann.|
| 3  |  muss               |  Funktionalität    |  Als ein User möchte ich eine Datei oder ein Ordner löschen, damit ich Sachen löschen kann, die ich nicht benötige.|
| 4  |  muss               |  Funktionalität    |  Als ein User möchte ich dass anzahl gefundene Datei zeigt, damit ich weiss, wie viele es sind.|
| 5  |  muss               |  Funktionalität    |  Als ein User möchte ich meine Dateien in einen Ordner ordnen, damit es Ordnung gibt.|
| 6  | muss                | Qualität     |  Als ein User möchte ich meinen Ordner benennen, damit ich Dateien sortieren kann.                                      |
| 7  | kann                | Funktionalität     |  Als ein User möchte ich, dass meine Dateien automatisch eingeordnet werden, damit ich schneller nach dem betroffenen Ordner suche.                                     |
| 8  | muss                | Funktionalität     |  Als ein User möchte ich einen Begriff eingeben, damit ich die gewünschten Dateien/Ordner finden kann.                                     |
| 9  | muss                | Funktionalität     |  Als ein User möchte ich die Dateien sehen, damit ich auf die gewünschten Dateien zugreifen kann.   |



### 1.21 Anforderungsanalyse
| AA-№ | Typ | Anforderung  |
| ---- | ------------ | ------- |
|1|Funktional|Das Programm soll vom Benutzer die Dateinamen abfragen.|
|2|Funktional|Das Programm soll die Funktion haben, einen neuen Ordner zu erstellen.|
|3|Funktional|Das Programm soll die Funktion haben, Dateien und Ordner zu löschen.|
|4|Funktional|Das Programm soll automatisch die Dateien ordnen.| 
|5|Funktional|Das Programm soll eine Suchoption zur Verfügung haben.|  
|6|Randbedingungen|Das Programm muss in C# geschrieben sein.|   
|7|Funktional|Das Programm soll ein Ergebnis zeigen.|   
|8|Qualität|Das Programm soll Anzahl Ergebnis zeigen.|      
|9|Qualität| Das Programm soll farbig aussehen.  |

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 0.1  | Applikation startet | - | - |
| 1.1  | Applikation zeigt userinterface | Ordner suchen | Such-option interface|
| 1.2  | Applikation zeigt Such-option interface | Speicherort | Dateien von diesem Speicherort |
| 1.3  | Applikation zeigt Such-option interface | Klick auf Datei | Vorschau popt auf |
| 1.4  | Applikation zeigt Such-option interface | Datei wird ausgewählt | Zeigt Datei im Ordner |
| 2.1  | Applikation zeigt userinterface | Datei hinzufügen | Datei-speicher interface |
| 2.2  | Applikation zeigt Hinzufügen interface | Name | Speichert Datei so ab |
| 2.3  | Applikation zeigt Hinzufügen interface | Text | Speichert den Text in der Datei ab |
| 2.4  | Applikation zeigt Hinzufügen interface | Speichern | Fragt wo es gespeichert werden soll |
| 2.5  | Applikation zeigt Datei-speicher interface | Speicherort | Datei wird dort abgespeichert |
| 3.1  | Applikation zeigt Datei-speicher interface | Ordner erstellen| Name vom Ordner abfragen |
| 3.2  | Applikation zeigt Datei-speicher interface | Name eingegeben | Wo Ordner speichern abfragen |


### 1.4 Diagramme
[Mindmap Suchmaschine.pdf](https://github.com/Saadu02/such-maschine/files/9919148/Mindmap.Suchmaschine.pdf)

![image](https://user-images.githubusercontent.com/111046257/196634771-d5b579d5-d8ba-4b9f-a881-4d9a99a44a5f.png)

<img width="589" alt="MicrosoftTeams-image (1)" src="https://user-images.githubusercontent.com/111046257/196640878-4b1cbf14-d89c-4912-964d-abf97839047c.png">

## 2 Planen
| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1 | 02.11.2022 | Mohammad |Planung| 35 Minuten |
| 2 | 02.11.2022 | Brandon |User-Stories| 30 Minuten |
| 3 | 02.11.2022 | Sathana |Anforderungsanalyse| 25 Minuten |
| 4 | 09.11.2022 | Mohammad |Test-Protokoll (Tabelle erstellen)| 10 Minuten |
| 5 | 09.11.2022 | Nicola |PAP Diagram erstellen| 45 Minuten |
| 6 | 09.11.2022 | Sathana + Nicola|Mockup erstellen| 45 Minuten |
| 7 | 16.11.2022 | Sathana |Entscheidungen aufschreiben| 30 Minuten |
| 8 | 16.11.2022 | Mohammad   |User-Stories + Anforderungsanalyse ergänzen| 45 Minuten |
| 9 | 16.11.2022 | Nicola |Sucheingabe erstellen| 45 Minuten |
| 10| 16.11.2022 | Nicola |automatisches Einordnung| 40 Minuten |
| 11| 16.11.2022 | Nicola + Sathana| Suchfunktion| 50 Minuten |
| 12| 23.11.2022 | Sathana| Dateien beim Suchen anzeigen| 40 Minuten |
| 13| 23.11.2022 | Nicola|  Vorder- und Hintergrund Farben| 30 Minuten |
| 14| 23.11.2022 | Sathana | File-Upload | 60 MInuten |
| 15| 30.11.2022 | Mohammad|  Kontrollieren| 45 Minuten |
| 16| 30.11.2022  | Sathana|  Kontrolle Dokumentieren|45 Minuten |

Total: 620 Minuten



## 3 Entscheiden

Als erstes haben wir entschieden das Programm als Website zuerstellen. Da wir Blazor noch mühe hatten, haben wir entschieden statt website, Winforms zu programmieren. 


## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.1 | 02.11.2022| Mohammad|   35 Minuten| 40 Minuten |
| 2.0 | 02.11.2022| Brandon |  30 Minuten| 45 Minuten   |
| 3.0 | 02.11.2022   | Sathana | 25 Minuten| 25 Minuten     |
| 4.0 | 09.11.2022| Mohammad | 10 Minuten | 5 Minuten|
| 5 | 09.11.2022| Nicola |  45 Minuten| 35 Minuten   |
| 6 | 09.11.2022  | Sathana + Nicola| 45 Minuten| 45 Minuten  |
| 7 | 16.11.2022 | Sathana |  30 Minuten|25 Minuten |
| 8 | 16.11.2022| Mohammad   | 45 Minuten | 30 Minuten|
| 9 | 16.11.2022 | Nicola | 45 Minuten | 40 Minuten |
| 10 | 16.11.2022 |Nicola |  40 Minuten| 30 Minuten|
| 11 | 16.11.2022|Nicola + Sathana|50 Minuten | 50 Minuten |
| 12 | 23.11.2022 |Sathana| 40 Minuten | 35 Minuten|
| 13 | 23.11.2022 | Nicola | 30 Minuten| 30 Minuten |
| 14 | 23.11.2022 | Sathana|60 Minuten |60 Minuten|         
| 15 | 30.11.2022 | Mohammand| 45 Minuten|40 Minuten|      
| 16 | 30.11 2022 | Sathana| 45 Minuten |50 Minuten|     


## 5 Kontrollieren

### 5.1 Testprotokoll


| TC-№ | Datum | Resultat | Überprüfer |
| ---- | ----- | -------- | ---------- |
| 0.1  | 30.11 | Fertig   | Mohammad   |
| 1.1  | 30.11 | Fertig   | Mohammad   |
| 1.2  | 30.11 | Fertig   | Mohammad   |
| 1.3  | 30.11 | Fertig   | Mohammad   |
| 1.4  | 30.11 | Fertig   | Mohammad   |
| 2.1  | 30.11 | Fertig   | Mohammad   |
| 2.2  | 30.11 | Fertig   | Mohammad   |
| 2.3  | 30.11 | Fertig   | Mohammad   |
| 2.4  | 30.11 | Fertig   | Mohammad   |
| 2.5  | 30.11 | Fertig   | Mohammad   |
| 3.1  | 30.11 | Fertig   | Mohammad   |
| 3.2  | 30.11 | Fertig   | Mohammad   |

## Auswerten


[AB_Arbeitsjournal und Lernbericht.docx](https://github.com/Saadu02/save-File-search-File/files/10122376/AB_Arbeitsjournal.und.Lernbericht.docx)



