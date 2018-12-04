
# Dokumentation
Tuan Binh Tran, 27.11.2018

# Inhaltsverzeichnis
* [Einleitung](#einleitung)
* [Zweck des Dokuments](#zweck-des-dokuments)
* [Installationsanleitung](#installationsanleitung)
* [Funktionen & Bugs](#funktionen--bugs)
  - [Zusätzliche Funktionen](#zusätzliche-funktionen)
  - [Nicht implementierte Funktionen](#nicht-implementierte-funktionen)
  - [Bekannte Bugs](#bekannte-bugs)
* [Use Cases](#use-cases)
* [Aktivitätsdiagram](#aktivitätsdiagram)
* [Testfälle](#testfälle)
* [GUI Mockups](#gui-mockups)
* [Code Guidelines](#code-guidelines)


# Einleitung
Diese ÖV-Applikation alias  wurde als Projekt für das ÜK 318 *"Analysieren und objektbasiert programmieren mit Komponenten"* entwickelt.
Dieses Projekt ist Open-Source und kann von jedem geforkt werden


# Zweck des Dokuments
Dieses Dokument dient für die Projektarbeit des ÜK 318 *"Analysieren und objektbasiert programmieren mit Komponenten"*.
Diese Dokument zeigt alle Funktionen 

# Installationsanleitung
Um die Applikation anzuwenden kann im [Release](https://github.com/tuanbinhtran/modul-318-student/releases) Tab, der Setup heruntergeladen werden. Der Installer führt den Benutzer durch den Wizard.

Alternativ kann dieser Repo geklont und danach selber ein Build erstellt werden.

# Funktionen & Bugs
Folgende Funktionen sind umgesetzt:
 - Auto-Complete bzw. Vorschlag für die eingegebenen Stationen während der Eingabe. 
 - Verbindungen zwischen zwei gültigen Stationen werden angezeigt.
 - Eine Abfahrtstafel einer bestimmten Station kann angezeigt werden.
 - Für die Verbindungen kann ein beliebiger Zeitpunkt gesetzt werden.

## Zusätzliche Funktionen
Diese zusätzliche Funktionen sind nicht in den vorgegebenen Anforderungen zu finden.

Folgende zusätzliche Funktionen sind umgesetzt:
 - Beide Stationen können getauscht werden. 
 - Der Zeitpunkt kann als Abfahrtszeit sowie auch Ankunftszeit angegeben werden. 
 
## Nicht implementierte Funktionen
Folgende Funktionen sind *nicht* umgesetzt:
 - Eine Station kann auf der Karte gesucht werden.
 - Es können alle Stationen in der Nähe der aktuellen Station angezeigt werden.
 - Gefundene Resultate können via Mail weitergeleitet werden.

## Bekannte Bugs
Folgende Bugs sind bekannt:
 - Beim Auto-Complete kann es sein, dass das Programm freezed. 


# Use Cases
![use cases](https://github.com/tuanbinhtran/modul-318-student/blob/master/use_case.png "use cases")

# Aktivitätsdiagram
![Aktivitätsdiagram](https://github.com/tuanbinhtran/modul-318-student/blob/master/Aktivitätsdiagram.png "Aktivitätsdiagram")

# Testfälle
Nr.  | Ausführung | Erwartetes Ergebnis
---- | ---------- | -------------------
1.| Bei beiden Stationen eine gültige Verbindung angeben. z.B. Luzern und Sursee | Die Stationen sollten jeweils vorgeschlagen werden.
2.| Ausführung gemäss 1. Testfall und danach die ENTER-Taste oder den Button Verbindungen suchen tätigen. | Das Fenster sollte sich am unteren Fensterrand vergrössern und die jeweiligen Verbindungen anzeigen.

# GUI Mockups
Diese GUI Mockups zeigen, wie die Vorstellung der Applikation vor Beginn der Arbeit geplant war. 

Nur einiges wurde umgesetzt, da während der Entwicklung bessere/andere Ideen und Vorstellungen entstanden sind.

Start

![Start page](https://github.com/tuanbinhtran/modul-318-student/blob/master/GUI_Mockups/Start.png "Start")

Suggestions

![Suggestions](https://github.com/tuanbinhtran/modul-318-student/blob/master/GUI_Mockups/Suggestions.png "Suggestions")

Connections

![Connections](https://github.com/tuanbinhtran/modul-318-student/blob/master/GUI_Mockups/Connections.png "Connections")



# Code Guidelines
Die Code Guidelines sind [HIER](https://github.com/tuanbinhtran/modul-318-student/blob/master/Code%20Guidelines.md) zu finden.

