# Oxygen Not Included: Deutsche Übersetzung

Dieses Repository enthält die deutsche Community-Übersetzung für [Oxygen Not Included](https://www.kleientertainment.com/games/oxygen-not-included).

## Hinweis zur Thermal-Beta
Die Übersetzungsdatei für die Beta-Version (_Thermal Update_) befindet sich im Beta-Branch. Dieser ist über das Dropdown oben links bzw. über [diesen Link](https://github.com/ZHecker/Oxygen_Not_Included_German/tree/Beta-) erreichbar.

## Installation
1. Lade die Datei "strings.po" herunter. Die einfachste Möglichkeit, ist über den grünen Button "Clone or Download" oben rechts eine ZIP-Datei herunterzuladen, und die PO-Datei zu extrahieren.
2. Platziere die Datei im Ordner `OxygenNotIncluded_Data\StreamingAssets\Mods` im Spielverzeichnis. Das Spielverzeichnis kann über Steam gefunden werden: Rechtsklick auf Oxygen Not Included, Eigenschaften, Lokale Dateien, und dann auf die Schaltfläche "Lokale Dateien durchsuchen".
3. Das Spiel lädt nun alle Texte aus der heruntergeladenen Datei.

## Mithelfen
Zum Mithelfen oder Melden von Fehler erstelle einfach ein neues Issue oder einen pull request mit deinen Änderungen.

Zum Bearbeiten der PO-Datei kann z.B. [Poedit](https://poedit.net) oder ein einfacher Texteditor wie notepad++ benutzt werden. 
Zu beachten ist, dass das Spiel Probleme mit mehrzeiligen Übersetzungstexten hat, die Poedit standardmäßig erzeugt. 


In dem Fall muss nach der Bearbeitung durch Textersetzung das Format angepasst werden, damit alle Übersetzungen in der Datei folgendermaßen aussehen. Eine Anleitung ist z.B. [hier](http://forums.kleientertainment.com/topic/74765-creatingusing-translation-files/?do=findComment&comment=876638) zu finden.


```
msgctxt "STRINGS.BUILDING.STATUSITEMS.XY.XY"
msgid "Englischer Text\nInklusive\Mögliche Zeilenumbrüche"
msgstr "Deutscher Text\nInklusive\nMögliche Zeilenumbrüche"
```
