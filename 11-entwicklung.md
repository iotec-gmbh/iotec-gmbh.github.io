---
layout: page
title: Entwicklung
sitemap:
  include: true
---

Ganz nach unserem Motto *Wir machen Sensoren intelligent* liegt der Fokus unserer Entwicklung auf industriellen Messsystemen.
Wir haben uns dabei als Ziel gesetzt, unsere Kunden in den ersten Schritten ihrer Entwicklung in allen Bereichen zu unterstützen,
um so die initiale Hürde für innovative und neue Ideen so gering wie möglich zu halten.
So können wir erste Prototypen schnell, einfach und *aus einer Hand* anbieten und dadurch sehr früh in der Entwicklung einen Mehrwert schaffen.
Dies bietet auch bei Projekten mit neuester Technologie und hohem Risiko eine große Planungssicherheit.

Diese Philosophie spiegelt sich auch in unserer **agilen Arbeitsweise** und **technischen Expertise** wider.

## Konzepterstellung

Zum Einstieg in ein Entwicklungsprojekt klären wir in einem kurzen Vorgespräch, ob wir der richtige Ansprechpartner für die Problemstellung des Kunden sind und ob unsere Arbeitsweise zu dem Unternehmen des Kunden passt.
Nach einem positiven Vorgespräch erstellen wir ein Angebot über die Erarbeitung eines Konzepts.
Die Ausarbeitung des Konzepts startet mit einem Expertengespräch, in dem unsere Spezialisten mit dem Kunden die technische Fragestellung für das Projekt erarbeiten.
Unser Fokus liegt dabei darauf, zu ergründen was die schnellste und einfachste Lösungsmöglichkeit ist – das **Minimal Viable Product**, das auf Kundenseite Mehrwert generiert.
Hierbei stehen folgende Fragen im Mittelpunkt:

- Wo kann Mehrwert entstehen?
- Welche Funktionalitäten sind besonders wichtig?
- In welchem Zeitrahmen wird geplant?

Auf Basis dieser Informationen wird von unserem interdisziplinären Team ein Konzept erarbeitet, welches Lösungsansätze für die Fragestellung des Kunden enthält.
Anschließend stellen wir dieses Konzept dem Kunden in einer Präsentation vor.
Aus diesem Gespräch leiten wir dann gemeinsam mit dem Kunden die Rahmenbedingungen für eine weitere Zusammenarbeit ab.
Dies könnte dann z.B. der Start einer Machbarkeitsstudie oder einer Prototypenentwicklung sein.

## Arbeitsweise

Gerade in Projekten im Bereich der Forschung und Entwicklung gibt es viele Unwägbarkeiten.
Durch neue Technologien und Prozesse können Risiken entstehen und Aufwände gegebenenfalls schlecht abgeschätzt werden.

Dennoch gibt es für die meisten Projekte feste Abgabetermine.
Es müssen Prototypen auf Messen ausgestellt werden oder das gewonnene Wissen wird für die nächste Entwicklung dringend benötigt.

Um zeitliche Unsicherheiten und Planungsrisiken gemeinsam mit unseren Kunden zu reduzieren, verfolgt unser Team bei der iotec GmbH Ansätze des **evolutionären Prototyping**.
Dabei erweitern wir, nach und nach, in kurzen Entwicklungszyklen das Produkt.
Dies befähigt uns, sehr schnell erste Funktionsprototypen zu erstellen und diese dann iterativ weiter zu entwickeln.
Wir können dem Kunden dabei, durch unsere Projektmanagement-Tools und Entwicklungsplattform, volle Transparenz über die Ergebnisse und Zwischenstände bieten.
Der Kunde behält so die volle Kontrolle, um bei Änderungswünschen direkt Einfluss auf den Projektablauf nehmen zu können.

## Fachliche Expertise

Als Dienstleister im Bereich der Soft- und Hardwareentwicklung, bieten wir ein sehr breit gefächertes Wissen aus den unterschiedlichsten Bereichen.
Gerade, um unseren eigenen Ansprüchen zu genügen,
unseren Kunden in den ersten Entwicklungszyklen bereits vollständige Prototypen anbieten zu können,
haben wir die gesamte Wertschöpfungskette in unserem Repertoire abgebildet: Von der Auswahl und der Ansteuerung der richtigen Sensoren, über das Speichern und Transportieren der Daten, bis hin zu deren Auswertung und Visualisierung.

### Sensorik

Das Herzstück unserer Firma ist die technische Sensorik – ein breites Feld, dass alle Arten von Industriemesssystemen umfasst und über dessen Möglichkeiten und Grenzen wir ein umfängliches Verständnis entwickelt haben.
Im Laufe der Zeit haben wir sowohl einfache Sensoren wie beispielsweise zur Messung von Temperatur und Luftfeuchte, als auch hochkomplexe Sensoren, wie Laserprofilsensoren oder Industriekameras, erfolgreich eingesetzt.
Häufig benötigen gerade komplexe Sensoren spezielle Hardware, um repräsentative, also zum Beispiel hochaufgelöste oder rauscharme, Daten aufzunehmen.
So umfasst unsere Entwicklung auch das Designen von **Trägerplatinen**, um beispielsweise komplexen Timing- oder Spannungsanforderungen zu genügen oder mehrere Sensoren miteinander zu kombinieren.
Für das PCB-Design nutzen wir als Software den [Altium Designer](https://www.altium.com/de/).

### Mikrocontroller

Zur Ansteuerung der Sensoren setzen wir häufig Mikrocontroller ein.
Gerade in Bereichen, in denen ein exaktes Timing eingehalten werden muss oder die Umgebung spezielle Anforderungen an die Hardware stellt.
So haben wir beispielsweise Mikrocontroller in Langzeitmesssystemen eingesetzt, die mit möglichst wenig Energie auskommen mussten.

Um eine hohe Wiederverwertbarkeit für unsere Kunden zu gewährleisten und um eine hohe Geschwindigkeit bei der Entwicklung halten zu können,
setzen wir bei den Mikrocontrollern primär auf die ESPs der Firma [Espressif](https://www.espressif.com/) und auf C/C++ und das [Arduino Framework](https://www.arduino.cc/).
Nichts desto trotz haben wir gerade für speziellere Aufgaben auch weitere Frameworks und Mikrocontroller, auf die wir zurückgreifen,
um eine möglichst passgenaue Lösung für jeden Kunden zu entwickeln.

### Embedded Linux

Wenn die Leistung der Mikrocontroller für die Datenverarbeitung nicht mehr ausreicht, nutzen wir Embedded Linux Systeme als Backend für unsere Sensoren.
Diese haben außerdem den Vorteil, dass wir auf eine sehr große und sehr stabile Basis an Software zurückgreifen können.
So haben wir beispielsweise ein Embedded Linux System eingesetzt, um unterschiedlichste Sensoren auszulesen, live zu verarbeiten und sicher in einer zeitbasierten Datenbank zu speichern.

Für die Betriebssysteme verwenden wir meist das sehr robuste und viel verwendete [Debian](https://www.debian.org/index.de.html)
oder generieren, wo es nötig ist, eigene kleine Linux Distributionen, mit Werkzeugen wie [Buildroot](https://buildroot.org/).
Für die Softwareentwicklung nutzen wir vorwiegend [Python](https://www.python.org/) oder auch, für hardwarenahe Entwicklung, C/C++.
Die eingesetzte Hardware reicht hier von einfachen System-on-a-Chip Systemen bis zu leistungsstärkerer Hardware, wie die [NUCs von Intel](https://www.intel.de/content/www/de/de/products/boards-kits/nuc.html).

### Vernetzung

Die Übertragung bzw. Bereitstellung der gemessenen Daten, ist eine der wichtigsten Funktionalitäten bei einem Sensorsystem.
So ist es bei verteilten Systemen, die über einen langen Zeitraum mit wenig Energie auskommen müssen, wichtig,
dass die Übertragung so energieeffizient wie möglich stattfindet, da sie einen der größten Verbraucher darstellt.
Wir versuchen daher bei solchen Systemen Protokolle aus der Klasse der **Low Power Wide Area Networks**, kurz LPWAN,
wie beispielsweise [LoRaWAN](https://lora-alliance.org/about-lorawan) oder [NB-IoT](https://en.wikipedia.org/wiki/Narrowband_IoT) einzusetzen.
Im Nahbereich nutzen wir zusätzlich auch Funktechnologien wie WLAN oder Bluetooth.
Auf der Anwendungsschicht verwenden wir meist Protokolle, die sich im IoT-Bereich bewährt haben,
wie HTTP und MQTT und standardmäßig erweitern wir diese, um eine Transportsicherheitsschicht mittels TLS.

### Visualisierung

Um direktes Feedback über die gesammelten Daten zu erhalten, ist es häufig sinnvoll, diese Daten visuell erfahrbar zu machen.
Daher haben wir uns ein Portfolio an Visualisierungsmöglichkeiten geschaffen.
So können wir unseren Kunden die Möglichkeit bieten, die von den Sensoren aufgenommenen Informationen einfach zu überprüfen.
Außerdem werden viele unserer Entwicklungen als Prototypen auf Messen oder bei internen Präsentationen vorgestellt.
Durch die Visualisierung lässt sich der Mehrwert der Sensorsysteme schnell begreifbar machen.

Unser Portfolio umfasst sowohl webbasierte Lösungen, wie [Grafana](https://grafana.com/),
als auch einfache Android Apps,
die wir meist mit [Flutter](https://flutter.dev/) oder [nativ](https://developer.android.com/) umsetzen.

### Datenverarbeitung und Analyse

Wer mit Sensoren etwas misst, macht das meist nicht zum Selbstzweck, sondern um etwas aus den Sensordaten zu erfahren.
Außerdem produzieren Sensoren oft große Datenmengen, die zur weiteren Verarbeitung oder Speicherung reduziert oder vorverarbeitet werden müssen.
Um die entscheidenden Trends, Muster und Anomalien in den erhobenen Daten zu erkennen, nutzen wir **statistische Methoden** und **Signalverarbeitung** genauso wie **klassisches maschinelles Lernen**.
Die entstandenen Erkenntnisse werden von unseren Kunden häufig dazu benutzt, Maschinen automatisiert zu überwachen, Fehlerfälle zu klassifizieren oder Produktionstoleranzen zu überprüfen.
Da wir in diesem Bereich hauptsächlich Skriptsprachen wie [Python](https://www.python.org/) nutzen,
können wir die Erkenntnisse jederzeit schnell – zum Beispiel als interaktive [Jupyter-Notebooks](https://jupyter.org/) oder als PDF – zur Verfügung stellen.
So stellen wir sicher, dass unsere Kunden jederzeit unsere Ergebnisse aus ihrer eigenen fachlichen Perspektive beurteilen können und die für ihre Fragestellung relevanten Informationen nicht in der Datenverarbeitung verloren gehen.

Außerdem haben wir auch fortgeschrittene Kenntnisse in der Bildverarbeitung.
Dort arbeiten wir sowohl mit freien Tools wie [OpenCV](https://opencv.org/), als auch mit proprietären Lösungen aus der industriellen Bildverarbeitung.
