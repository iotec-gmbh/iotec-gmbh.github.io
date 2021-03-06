---
title: Forschung
sitemap:
  include: true
---

Die Digitalisierung der Industrie schreitet in schnellen Schritten voran.
Technologien und Prozesse, die vor einiger Zeit noch alternativlos waren,
sind heute schon obsolet und es treten neue, schnellere und effizientere an Ihre Stelle.
Um in dieser rasanten Entwicklung mitzuhalten, und diese sogar mitzugestalten,
beteiligt sich iotec maßgeblich an unterschiedlichen Forschungsprojekten.

Unsere Hauptanliegen sind dabei, die Chancen und Limitierungen **neuer Technologien** zu analysieren,
**Prozesse** zu verbessern und für unsere Kunden ein breites **Netzwerk aus Forschungs- und Entwicklungspartnern** aufzubauen.

Im Folgenden möchten wir Ihnen einige Themen unserer Forschungsprojekte detaillierter vorstellen.

## Die Wertschöpfungskette verkürzen

Neue Technologien legen in etablierten Prozessen Optimierungspotentiale offen.
Manuelle Tätigkeiten und Expertenwissen können heute auf vielfältige Art automatisiert werden
und so Reproduzierbarkeit und Qualität verbessern.
In unseren Forschungsprojekten dreht es sich daher oft um die Frage, wo das **Potential von Sensorik** genutzt werden kann,
um bestehende Prozesse zu verkürzen oder zu automatisieren.

So hat sich das Forschungsprojekt [soil2data](#soil2data) zum Ziel genommen,
das zeitaufwendige Standardverfahren im Bereich der Bodenbeprobung auf landwirtschaftlichen Flächen zu verbessern.
Dazu wurde ein autonomes System entwickelt, welches Bodenproben vor Ort auf die Nährstoffzusammensetzung analysiert,
um so dem Landwirt zeitnah eine Entscheidungsgrundlage zur Düngung geben zu können.
Die Herausforderung für iotec besteht darin, die verschiedenen Teilsysteme miteinander zu verknüpfen,
so dass eine **automatisierte Prozesskette** möglich wird.
Das Nachfolgeprojekt *soil2data2* beinhaltet die Weiterentwicklung zu einem seriennahen Produkt.

In einem anderen Beispiel stehen Gartenbaubetriebe vor der Herausforderung,
den Befall Ihrer Pflanzen mit Schädlingen möglichst zeitnah und genau zu bestimmen,
um die angemessene Bekämpfung genau berechnen zu können.
Dazu werden Schädlingsfallen in unregelmäßigen Intervallen, mit hohem manuellem Aufwand ausgetauscht und ausgewertet.
Um hier zum einen den Arbeitsaufwand zu reduzieren und zum anderen die **Datengrundlage** zu verbessern,
hat iotec im Forschungsprojekt [DSSARTH](#dssarth), den Prototyp einer autonomen Klebefalle entwickelt.
Diese erfassen den aktuellen Befall zeitnah und werten die Anzahl und die Art der Schädlinge automatisch aus.
Die Ergebnisse werden an eine Plattform übertragen, die auf der Grundlage des festgestellten Schädlingsbefalls
**Handlungsempfehlungen** zur Bekämpfung ausstellt.
Die Weiterentwicklung dieses Systems erfolgt im Nachfolgeprojekt [IPMaide](#ipmaide).

Auch beim Verkleben von Kohlefaserverbundstoffen gibt es etablierte Prozesse, die verbessert werden können.
Die von iotec, im Forschungsprojekt [STEP-UP](#stepup), mitentwickelte geführte manuelle Verklebung,
zeigt dem Mitarbeiter die aktuellen Arbeitsschritte und Messwerte vom zu klebenden Objekt visuell in einem *Virtual Reality Headset* an.
Dieses System kann, mit relativ einfachen Mitteln, in die vorhandene Fertigung implementiert werden und dadurch die **Qualität** der Klebungen steigern.

## Verteilte Sensoren in der Realität

Ein weiteres Thema das iotec in seinen Forschungsprojekten bearbeitet ist die Aufnahme und Übertragung von Sensordaten.
Wie verhalten sich die **unterschiedlichen Technologien in der Praxis**?
Welche Technologien sollte ich einsetzen, wenn ich nur sehr **limitierte Energie** zur Verfügung habe?
Wie müssen Sensorsysteme aufgebaut sein, damit sie auch unter **schwierigen Umweltbedingungen** weiter zuverlässig funktionieren?
Und wie wird eine möglichst **einfache Inbetriebnahme** geschaffen?

In den beiden Forschungsprojekten *Nagerfalle* und [DSSARTH](#dssarth) werden jeweils verteilte Sensorsysteme eingesetzt, um Schädlingsbefall zu überwachen.
Damit die verteilten Sensoren effizient in die IT-Infrastruktur eingebunden werden können, werden unterschiedliche Funkprotokolle,
wie diverse Protokolle aus der **LPWAN** (Low Power Wide Area Network) Familie,
aber auch **Übertragungsmethoden** wie Bluetooth Low Energie, WLAN-Mesh oder GSM, auf Energieeffizienz, Reichweite und Robustheit untersucht.
Darüber hinaus werden diese Messgrößen für die verschiedenen Netzwerkprotokolle, wie MQTT oder HTTP, und diverse **Verschlüsselungsmethoden** bestimmt.

Zusätzlich wählt iotec die Sensoren und elektrischen Systeme so aus, dass eine möglichst hohe **physische Robustheit** erreicht wird.
Mittels unterschiedlicher Gehäuse-Ausführungen und Coatingverfahren, wird in diesem Zusammenhang auch versucht die Robustheit noch weiter zu steigern.
Ziel ist es dabei die Sensorsysteme auch im Außenbereich, bei unterschiedlichen Wettereinflüssen und möglichst autark über die Dauer eines Jahres zu betreiben.

iotec nutzt das Forschungsprojekt *Nagerfalle* ebenfalls, um **einfache und sichere Protokolle zur Inbetriebnahme** dieser verteilten Sensorsysteme zu entwickeln.
Ziel ist es, die möglichen Fehlerquellen so stark zu reduzieren, dass auch ungelernte Kräfte diese Systeme in Betrieb nehmen und gleichzeitig die Richtigkeit und Integrität der Daten überprüfen können.

## Sensordaten benutzbar machen

Sensoren produzieren oft eine Menge unstrukturierter Daten.
Dabei liegt der **Wert der Sensordaten** häufig in einem, in den Messwerten, versteckten Signal.
In einem automatisierten Prozess ist es daher notwendig, die in den Rohdaten enthaltenen Informationen zu extrahieren und diese strukturiert an den nachfolgenden Prozess übergeben zu können.

Die im Forschungsprojekt [DSSARTH](#dssarth) verwendeten Kameras erstellen Aufnahmen von Schädlingen auf Klebetafeln.
Hierbei ist die **kritische Information**, wie viele Schädlingsinsekten auf der Tafel vorhanden sind.
iotec setzt sich in diesem Forschungsprojekt mit der Frage auseinander, wie die Rohdaten in Form des Fotos ausgewertet werden können, um die Anzahl von Schädlingen bestimmen zu können.
In diesem komplexen Fall werden dazu Methoden der **Bildverarbeitung** und des **maschinellen Lernens** benutzt.
Die Anzahl an Insekten wird anschließend, über eine definierte Schnittstelle, geordnet an ein Entscheidungshilfesystem *downstream* übergeben.

Andere Forschungsprojekte, an denen sich iotec beteiligt, beschäftigen sich mit ähnlichen Fragen unter der Zuhilfenahme **verschiedenster Sensorarten**:
Das Projekt [soil2data](#soil2data) entwickelt ein mobiles Feldlabor, das automatisch Daten über die Bodenbeschaffenheit landwirtschaftlicher Flächen bereitstellt.
Dazu werden die im Feld genommenen Bodenproben automatisiert, analysiert und die Nährstoffkonzentrationen des Bodens **strukturiert aufbereitet**.
Die Projekte [OptiBlend](#optiblend) und *AQM* beschäftigen sich ebenfalls mit dieser Herausforderung.

## Forschungsprojekte

{% include research-bibliography.html %}
