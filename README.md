# MALIS 19.3 WPMT 9.1
Repository for MALIS 19.3 WPM T9.1

Datenbasierte Aktivitäten in der eigenen Bibliothek

Autor: Noel Konietzny


## Inhaltsverzeichnis

1. Einleitung

2. Library Management System aDis/BMS

3. Katalog

4. Fernleihe

5. Roboter

6. Fazit

7. Quellenverzeichnis
- 7.1 Onlinequellen

- 7.2 Bildquellen


## 1. Einleitung

Innerhalb der [Stadtbüchereien Düsseldorf](https://www.duesseldorf.de/stadtbuechereien/) gibt es verschiedene Arbeitsbereiche die sehr datenintensiv sind. Dabei gibt es in vielen Bereichen Möglichkeiten einer Optimierung. Hier sollen einige kleine Beispiele genannt und erläutert werden. Des Weiteren werden hier nur kurz andere Bereiche erwähnt, die ebenfalls von Software und Umstrukturierungsprozessen erheblich profitieren würden.


## 2. Library Management System aDis/BMS

Das von den Stadtbüchereien Düsseldorf verwendete Bibliotheksmanagement System ist das von der Firma [aStec](https://www.astec.de/) angebotene aDis/BMS. Die Landeshauptstadt Düsseldorf befindet sich dabei in einem Verbund mit den Städten Neuss, Dormagen, Grevenbroich und Meerbusch.  Die [ITK-Rheinland](https://www.itk-rheinland.de/) steht dabei als externer kommunaler IT-Dienstleister im Second-Level-Support, sowohl zusätzlich mit Beratung, Betreuung und der Umsetzung neuer Softwareprogramme unterstützend zur Seite. Dabei werden eigene zentrale Server genutzt. Das BMS aDis wird u.a. auch von den öffentlichen Großstadtbibliotheken Dortmund, Berlin, Stuttgart und München verwendet.
Es bietet die Möglichkeit der Verwaltung von Katalogisierung, Benutzung, Statistik, Normdaten, E-Medien, Erwerbung und der Periodika. Des Weiteren ist es direkt mit dem jeweiligen OPAC der Bibliothek gekoppelt und Änderungen im jeweiligen Programm werden (beidseitig) direkt wirksam.


## 3. Katalog

Die Katalogisierung des gesamten haptischen Medienbestands (ohne Periodika etc.) erfolgt bei den Stadtbüchereien Düsseldorf händisch durch die Mitarbeiterinnen aus der Fachabteilung des Katalogs. Dabei wird jedes Medium einzeln nach den Richtlinien des bibliothekarischen Regelwerks [*„Ressource Description and Access"* (RDA)](https://www.rdatoolkit.org/about) katalogisiert. Trotz der durch aDis gegebenen Möglichkeiten einer Fremddatenübernahme aus z.B. der [Deutsche(n) Nationalbibliothek (DNB)](https://www.dnb.de/DE/Home/home_node.html) oder dem zuvor in Punkt 2 genannten Verbund des Rhein Kreis Neuss erfordert jedes einzelne Medium noch viele sich wiederholende Arbeitsschritte. Durch diese Tätigkeit sind Menschen besonders gefordert, was auch zu Fehlern führt. Dabei findet man diese vereinzelt sowohl im eigenen Katalog als auch in einigen Metadatensätzen der DNB sowie im eigenen Verbund. Dabei ist eine Fehlerkorrektur im laufenden Betrieb oft zeitlich schwer umsetzbar, da andere Belange wie die Kundenbetreuung etc. Vorrang haben. Auch der menschliche Aspekt Kolleginnen auf Fehler hinzuweisen kann das zwischenmenschliche Verhältnis schädigen. Dabei würde evtl. eine für Superuser im OPAC verwendbare Meldefunktion helfen, um dies schnell, (anonym) und unkompliziert ähnlich wie eine Ticket Funktion mit Prüfung, um Nachbearbeitung zu ermöglichen. Menschliche Fehler werden sich nie vermeiden lassen und hier könnte eine zusätzliche Software Implementierung zur Verbesserung der Katalogisate und somit auch der Verwendbarkeit und Auffindbarkeit für die Nutzerinnen im OPAC dienen. Des Weiteren ist es im OPAC bei der Bestellung und Vormerkung von Medien derzeit nicht möglich mehr als ein Medium zur gleichen Zeit zu bestellen. Eine Sammelfunktion ähnlich eines „Einkaufswagens“ wie von Online Handelsplattformen allgemein bekannt würde hier sowohl aus Mitarbeiter und Kundensicht helfen. 
Zusätzlich ist bei den vielen unterschiedlichen Programmen, bei denen man sich als Mitarbeiter einloggen muss, wie z.B. PC, BMS, Arbeitszeitverwaltung oder auch als Superuser im OPAC ein [Single Sign-on System](https://www.computerwoche.de/a/wunderwaffe-sso,3545560) von Vorteil, dass derzeit nicht existiert. Mit dieser einmaligen Authentifizierung wäre ein zeitsparender Arbeitsablauf in vielen Bereichen möglich. Eine Umstellung der dabei betreffenden Softwareprogramme wäre dabei zwingend notwendig.


## 4. Fernleihe

Die Stadtbüchereien Düsseldorf nehmen des Weiteren an der aktiven und passiven Fernleihe teil. Außer dem obligatorischen Bibliothekskonto der DigiBib bzw. dem hbz müssen bei der Bearbeitung der aktiven & passiven Fernleihen Begleitschreiben beigefügt werden die alle wesentlichen Informationen über das Medium, wie z.B. Titel, Autor, Leihfrist etc. haben. Diese Daten werden über das Fernleihe-Tool in aDis automatisch generiert. Und auch einige Details zu den Leihmodalitäten können über drop down Menüs relativ schnell ausgewählt und eingestellt werden. Dabei sind weitere drop down Menüs nicht aktiv bzw. nur reine Schreibfelder vorhanden. Hier müssen extra vorgefertigte Sätze z.B. über Beschädigungen oder Besonderheiten über die Leihfristen oder die Art der Ausleihe aus einem parallel geführten Word Dokument herauskopiert und in die aDis Maske eingefügt werden. Dies ist nicht nur sehr umständlich, sondern könnte durch die bereits vorhandenen inaktivierten drop down Menüs softwaretechnisch optimiert werden. Aufgrund der nicht sehr hohen Priorität der Fernleihe in einer öffentlichen Bibliothek z.B. im Vergleich zu einer wissenschaftlichen, stehen hier solche Verbesserungen nicht auf der Hauptagenda und im Fokus der Optimierung.

Im Weiteren ist es so, dass passive Fernleihen nur händisch über die Verbuchungstheke durch Mitarbeiter auf die Benutzerkonten gebucht bzw. auch nur so zurückgegeben werden können. Dies liegt an den verschiedenen Sicherungssystemen, wie z.B. Magnetstreifen und FRID-Tags. Durch die des Weiteren in den Bibliotheken unterschiedlichen Systematiken und Bibliotheksmanagementsysteme ist eine maschinelle Rückgabe sehr Fehler lastig und kann die Sicherungssysteme der gebenden Bibliotheken beschädigen, was unbedingt vermieden werden soll. Des Weiteren wäre eine Selbstabholung durch Kunden auch für die zu erweiternden Open Library Zeiten und ggf. Sonntagsöffnungen ohne Fachpersonal wichtig, auch wenn dies nur einen kleinen Teil des Gesamtausleihen ausmacht. Zur Lösung dieses Problems könnte, das in der ULB Düsseldorf seit Jahren bewährte System der RFID-Verbuchung übernommen werden. In der Regel werden alle hauseigenen Medien der ULB Düsseldorf mit Magnetstreifen gesichert und können so in Einzelverbuchung ausgeliehen und über einen Rückgabeautomaten zurückgegeben werden. Für die dort im hohen Maße aufkommenden Fernleihen konnte dies bei Open Library Zeiten ohne Fachpersonal so nicht umgesetzt werden und auch keine Hauseigene Magnetstreifen Sicherung genutzt werden, um die Bücher nicht zu beschädigen. Hier wurde ein Selbstabholbereich auf RFID-Basis zusätzlich eingerichtet. Des Weiteren wurde einer der zwei in der ULB stehenden Rückgabeautomaten auch auf die Annahme von RFID basierten Sicherungen erweitert. Zur praktischen Handhabung werden in die Fernleihmedien [*„reversible“* RFID-Tags nach dänischem Modell](https://publiscologne.th-koeln.de/frontdoor/deliver/index/docId/375/file/PB2013_Reymer_RFID.pdf) eingeklebt. Dabei handelt es sich um Tags, die jederzeit ganz einfach in Medien rein und raus geklebt werden können, ohne diese zu beschädigen bzw. sonst wie zu verändern. Des Weiteren ist die Beschreibung dieser Tags auch dominant gegenüber anderen RFID-Tags, sodass dieses System eine optimale Selbstverbuchung für Kunden in den Servicefreien Zeiten kostengünstig – auch für die Stadtbüchereien Düsseldorf – realisierbar macht, da hier schon von Grund auf RFID verwendet wird und die technischen Infrastruktur schon vorhanden ist. Lediglich die reversiblen RFID-Tags müssten organsiert werden, sowie einige Abläufe in der Fernleihabteilung. Zusätzlich müssten hier dann auch noch softwareoptimierte Prozesse initiiert werden, um eine reibungslose Funktion zu ermöglichen. So könnte in Zukunft auch über Open Library hinaus über *„Buchstationen“* im Sinne einer [DHL Packstation](https://www.dhl.de/de/privatkunden/pakete-empfangen/an-einem-abholort-empfangen/packstation-empfang.html?iaid=20200512210646572522f6cc25bd1e) im Außenbereich der Bibliotheken nachgedacht werden. Diese könnten über die bereits vorhandenen auf [NFC](https://www.netzwelt.de/nfc/index.html) basierten Bibliothekskarten mit zusätzlichem Tan-Verfahren eine 24/7 Rückgabe ermöglichen, oder mit Vorlauf auch eine Abholung von Medien nach Bibliotheksschließung aus der *„Buch-Packstation“* ermöglichen. Auch während einer Pandemie wie Covid-19 könnten so Medien unter Einhaltung der Kontaktbeschränkungen realisiert werden.


## 5. Roboter

![Pepper-Bot](https://www.duesseldorf.de/fileadmin/_processed_/7/4/csm_191010pepper_55f6cb49f6.jpg) ![Hase & Igel](https://www.esz.hu-berlin.de/de/bilder/hase-und-igel/ZwB%20Nawi%20Hase%20an%20einer%20Station.JPG/image_preview)

Seit dem 07. November 2019, befindet sich des Weiteren ein [Pepper-Bot](https://www.duesseldorf.de/medienportal/pressedienst-einzelansicht/pld/pepper-hilft-in-der-zentralbibliothek.html) der Firma [SoftBank Robotics](https://softbankrobotics.com/) im                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  Bestand der Stadtbüchereien Düsseldorf. Pixi Pepper wurde durch die Firma [Humanizing Technologies](https://www.humanizing.com/de/startseite/) vertrieben und mit Softwareapplikationen versehen. Dieser als Assistent gedachte Roboter bedarf einer großen Menge an Daten, sowie Zeit zur Einpflegung und Programmierung. Das auf [NAOqi OS](https://technik.lpeshop.de/img/cms/SOFTBANK%20Pepper%20Depliant%20ENG%20num.pdf) laufende System kann mithilfe von Programmiersprachen wie z.B. C++, Java, Python, Libqi C++ & Python sowie ROS bridge frei programmiert werden. Da es sich hierbei um ein nicht proprietäres System handelt, ist dies somit von großem Vorteil für eigene spezifische Applikationsupgrades. Pixi Pepper dient primär als Informations und Orientierungshelfer für Besucher und bietet gleichzeitig den ersten niederschwelligen Kontakt zu humanoiden Robotern für eine breite Bevölkerungsschicht.

Einen anderen Aspekt verfolgt die Zweigbibliothek Naturwissenschaften der Humboldt-Universität am Adlershof im Erwin-Schrödinger-Zentrum Berlin. Hier wird auf ein *„Fahrerloses Transportsystem“* gesetzt. Durch ein an den Wänden verbautes Leitsystem können die beiden Bibliotheksroboter [*„Hase & Igel“*](https://www.morgenpost.de/printarchiv/biz/article104899720/Hase-und-Igel-in-Adlershof.html) Medienkisten zur Unterstützung der Mitarbeiterinnen innerhalb der Bibliothek - auch über Aufzüge Etagenweit - transportieren.


## 6. Fazit


## 7. Quellenverzeichnis

### 7.1 Onlinequellen

Zuletzt abgerufen am: 12.05.2020

- [Stadtbüchereien Düsseldorf](https://www.duesseldorf.de/stadtbuechereien/)

- [aStec](https://www.astec.de/)

- [ITK-Rheinland](https://www.itk-rheinland.de/)

- [*„Ressource Description and Access"* (RDA)](https://www.rdatoolkit.org/about)

- [Deutsche(n) Nationalbibliothek (DNB)](https://www.dnb.de/DE/Home/home_node.html)

- [Single Sign-on System](https://www.computerwoche.de/a/wunderwaffe-sso,3545560)

- [*„reversible“* RFID-Tags nach dänischem Modell](https://publiscologne.th-koeln.de/frontdoor/deliver/index/docId/375/file/PB2013_Reymer_RFID.pdf)

- [DHL Packstation](https://www.dhl.de/de/privatkunden/pakete-empfangen/an-einem-abholort-empfangen/packstation-empfang.html?iaid=20200512210646572522f6cc25bd1e)

- [NFC](https://www.netzwelt.de/nfc/index.html)

- [Pepper-Bot](https://www.duesseldorf.de/medienportal/pressedienst-einzelansicht/pld/pepper-hilft-in-der-zentralbibliothek.html)

- [SoftBank Robotics](https://softbankrobotics.com/)

- [Humanizing Technologies](https://www.humanizing.com/de/startseite/)

- [NAOqi OS](https://technik.lpeshop.de/img/cms/SOFTBANK%20Pepper%20Depliant%20ENG%20num.pdf)

- [*„Hase & Igel“*](https://www.morgenpost.de/printarchiv/biz/article104899720/Hase-und-Igel-in-Adlershof.html) 


### 7.2 Bildquellen

- [Pepper-Bot](https://www.duesseldorf.de/fileadmin/_processed_/7/4/csm_191010pepper_55f6cb49f6.jpg)

- [Hase & Igel](https://www.esz.hu-berlin.de/de/bilder/hase-und-igel/ZwB%20Nawi%20Hase%20an%20einer%20Station.JPG/image_preview)

