
# Exposé Aufgabe MALIS 21.3 WPM_T9.2: Data Science / Data Librarianship / IT-Praxis
# Hendrik Platte-Burghardt

## Lösung (wahrscheinlich) mit Option 1: Python

### Problemstellung: 
Verbesserte und vereinfachte Auswertung der E-Book-Nutzungsstatistiken der UB Mannheim (siehe Aufgabe 1). Die Nutzungsdaten kommen von den Verlagen/Anbietern und liegen in zahlreichen Einzeltabellen in unterschiedlicher Strukturierung vor.

### Ziel:
Ziel des Projekts ist es, die Auswertung der Statistiken zu vereinfachen und die Vergleichbarkeit zu erhöhen. Im Idealfall sollten am Ende für einzelne E-Book-Pakete vergleichbare Kennzahlen stehen wie z. B. Zugriffszahlen insgesamt oder pro Monat, Zugriffszahlen pro Titel, Preis pro Zugriff, Anteil mindestens x-mal genutzter Titel etc. Diese Kennzahlen könnten auch grafisch präsentiert oder durch Grafiken ergänzt werden. Ob eine Kennzahl wie 'Preis pro Zugriff' erstellt werden kann hängt davon ab, ob die Zugriffszahlen auf einzelne Pakete zurückführbar sind. Teilweise liegen nur Gesamtlisten für einen Verlag vor.

### Angedachter Lösungsweg und abzusehende Problemstellungen:

Zunächst sollen hilfreiche Kennzahlen für mindestens einen Verlag/Anbieter generiert werden. Ausgehend von einer möglichst einfach strukturierten Excel-Tabelle sollen möglichst viele der oben genannten Kennzahlen berechnet werden. Für die E-Books des Verlags Duncker & Humblot liegen die Zahlen beispielsweise in einfacher Form vor: Die einzelnen Titel sind mit ihren Nutzungszahlen pro Monat gelistet. Diese Zahlen sollten sich mithilfe von Python relativ einfach zusammenfassen und aufbereiten lassen. Das Skript kann dann auf ähnlich strukturierte Tabellen angewendet und ggf. angepasst werden. Basierend auf solchen 'einfachen' Fällen lassen sich ggf. Erkenntnisse gewinnen, die bei der Lösung schwierigerer Fälle helfen können.

Neben einigen anderen Anbietern stellt der Verlag DeGruyter beispielsweise verschiedene Nutzungszahlen für einzelne Titel in einzelnen Tabellenzeilen zur Verfügung: Total_Item_Investigations, Unique_Item_Investigations, Unique_Title_Investigations, Total_Item_Requests, Unique_Item_Requests und Unique_Title_Requests. In solchen Fällen muss entsprechend gefiltert, zusammengefasst oder getrennt ausgewertet werden.

Teilweise liegen einzelne Tabellen oder Tabellenblätter z. B. für Quartale vor, die in irgendeiner Form zusammengeführt bzw. zusammengefasst werden müssen. Teilweise werden nicht vorhandene Zugriffe mit einer leeren Zelle, teilweise mit einer Null gekennzeichnet.

In jedem Fall sollte das Ziel sein, möglichst große Teile der Aufbereitung mit Python zu automatisieren und jenseits der Sichtung der Tabellen und der Anpassung des Skripts wenig 'Handarbeit' wie die Vorbearbeitung von Tabelle, das manuelle Eintragen von Zahlen o. Ä. zu verrichten. Perspektivisch gesehen kommt es dann auf das Feedback derjenigen an, die die Zahlen nutzen werden: hier werden aller Wahrscheinlichkeit noch einmal andere Kennzahlen gewünscht werden, während sich bereits erstellte Kennzahlen als weniger gefragt erweisen.

Zum aktuellen Zeitpunkt ist mein Wissen zu Python und seinen Funktionen noch sehr eingeschränkt, deshalb beschränkt sich dieses Exposé auch auf eine sehr oberflächliche Beschreibung des Projekts. Die Bereitstellung von einigen der oben genannten Kennzahlen für mindestens ein paar der Anbieter/Verlage wäre bereits eine Verbesserung des Status Quo, mit einer größeren Abdeckung und einer nutzerfreundlichen Aufbereitung der Ergebnisse steigt der Nutzen dann entsprechend weiter an. 

