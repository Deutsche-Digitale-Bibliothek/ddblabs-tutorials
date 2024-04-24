# Einführung in die API der Deutsche Digitale Bibliothek

## Tutorial 1: Einführung in die Deutsche Digitale Bibliothek und ihre API
*Einführung in die API der Deutschen Digitalen Bibliothek*

Dieses Tutorial bietet einen grundlegenden Überblick über die Deutsche Digitale Bibliothek und deren API. Es führt in die verschiedenen Arten von digitalisierten Kulturgütern ein, die über die Plattform zugänglich sind, und zeigt, wie man einen API-Schlüssel beantragt. Die Teilnehmer werden durch den Prozess geführt, wie man einfache API-Anfragen stellt, um Basisinformationen zu erhalten, und lernen die wichtigsten Endpunkte der API kennen.

### Python-Bibliotheken

- `requests`: Zum Senden und Empfangen von HTTP-Anfragen.
- `json`: Zum Handling der JSON-Daten, die von der API zurückgegeben werden.

## Tutorial 2: Grundlagen der API-Anfragen
*API-Anfragen an die Deutsche Digitale Bibliothek stellen*

In diesem Tutorial lernen die Teilnehmer, wie man effektiv mit der API kommuniziert, indem man spezifische Anfragen zu verschiedenen Objektkategorien stellt. Es wird gezeigt, wie man nach digitalisierten Büchern, Kunstwerken und Archivmaterialien sucht und welche Parameter verwendet werden können, um die Suche zu verfeinern.

### Python-Bibliotheken

- `requests`
- `json`

## Tutorial 3: Verstehen und Nutzen von Metadaten
*Metadaten aus der Deutschen Digitalen Bibliothek effektiv nutzen*

Dieses Tutorial vertieft das Verständnis und die Nutzung der Metadaten, die über die API bezogen werden können. Teilnehmer lernen, wie man detaillierte Informationen zu einzelnen Objekten abruft, einschließlich Beschreibungen, Urheberinformationen und Digitalisierungsstatus. Es wird auch erklärt, wie man diese Metadaten in Python analysiert und vorverarbeitet, um sie für weitere Anwendungen vorzubereiten.

### Python-Bibliotheken

- `pandas`: Zum Organisieren der Daten in einem strukturierten Format.
- `json`

## Tutorial 4: Suchfunktionen der API
*Erweiterte Suchfunktionen in der DDB API nutzen*

In diesem Tutorial wird die Nutzung der erweiterten Suchfunktionen der API detaillierter behandelt. Die Teilnehmer lernen, wie man komplexe Suchanfragen erstellt, die mehrere Parameter kombinieren, um gezielte Ergebnisse zu erzielen. Beispiele hierfür sind die Suche nach Objekten aus einem bestimmten Zeitraum oder die kombinierte Suche nach Objekten, die bestimmte Wörter im Titel und eine bestimmte Sprache aufweisen.

### Python-Bibliotheken

- `requests`
- `json`

## Tutorial 5: Nutzung von Apache Solr-Suchindizes in der DDB API
*Apache Solr-Suchindizes mit der DDB API nutzen*

Dieses Tutorial führt in die Grundlagen von [Apache Solr](https://solr.apache.org/guide/8_11/overview-of-searching-in-solr.html) ein, einem mächtigen Suchindex-System, das von der DDB verwendet wird. Teilnehmer lernen, wie sie Solr-spezifische Suchanfragen formulieren und die robusten Suchfunktionen von Solr nutzen, um komplexe Abfragen effektiv durchzuführen. Es wird erklärt, wie man die Solr-Query-Syntax verwendet, um spezifische Felder, Ranglisten und Filterabfragen zu nutzen. Dabei wird beispielsweise gezeigt, wie man nach digitalisierten Objekten aus einem bestimmten Zeitraum oder von spezifischen Orten sucht.

### Python-Bibliotheken

- `requests`: Für das Senden von HTTP-Anfragen an die DDB API.
- `json`: Zum Parsing der JSON-Antworten, die von der API zurückgegeben werden.

## Tutorial 6: Verarbeitung von API-Antworten
*Verarbeitung und Analyse von API-Antworten*

In diesem Tutorial lernen die Teilnehmer, wie man die von der API erhaltenen Daten verarbeitet. Dabei wird auf die Struktur der JSON-Antworten eingegangen und gezeigt, wie diese in Python effektiv gehandhabt und für die weitere Verarbeitung vorbereitet werden können. Es werden Methoden zur Fehlerbehandlung und zur Optimierung von API-Anfragen behandelt, um effiziente und robuste Anwendungen zu entwickeln.

### Python-Bibliotheken

- `requests`: Für das Senden von Anfragen und Empfangen von Antworten.
- `json`: Zum Laden und Parsen von JSON-Daten.
- `pandas`: Zur Umwandlung von JSON in DataFrame für eine einfache Datenmanipulation.

## Tutorial 7: Nutzung von Python-Bibliotheken zur Datenmanipulation
*Python-Bibliotheken zur Manipulation von DDB-Daten verwenden*

Dieses Tutorial führt in die Verwendung von Python-Bibliotheken ein, die für die effektive Manipulation und Bereinigung der über die DDB API erhaltenen Daten notwendig sind. Die Teilnehmer lernen, wie sie mit pandas komplexe Datenstrukturen handhaben, Daten bereinigen, transformieren und für die Analyse vorbereiten können. Zusätzlich wird die Verwendung von numpy für mathematische Operationen und Datentransformationen eingeführt.

### Python-Bibliotheken

- `pandas`: Zum Organisieren, Bereinigen und Vorbereiten von Daten.
- `numpy`: Für mathematische Berechnungen und Array-basierte Operationen.

## Tutorial 8: Grundlagen der Datenvisualisierung
*Einführung in die Datenvisualisierung mit DDB-Daten*

In diesem Tutorial werden die Grundlagen der Datenvisualisierung behandelt. Die Teilnehmer lernen, wie man mithilfe der Bibliotheken matplotlib und seaborn einfache Diagramme und Grafiken erstellt, um die Daten visuell darzustellen. Es wird gezeigt, wie man Histogramme, Scatterplots und Bar-Charts erstellt, um die Verteilung, Beziehungen und Kategorisierung der Daten aus der Deutschen Digitalen Bibliothek zu visualisieren.

### Python-Bibliotheken

- `matplotlib`: Für die Erstellung von Diagrammen und Grafiken.
- `seaborn`: Für fortgeschrittene Visualisierung und ansprechendes Design.

## Tutorial 9: Fortgeschrittene Datenvisualisierung mit DDB-Daten
*Erweiterte Visualisierungstechniken für Daten der Deutschen Digitalen Bibliothek*

In diesem fortgeschrittenen Tutorial lernen die Teilnehmer, wie sie komplexe Visualisierungen erstellen, um tiefere Einblicke in die Daten der DDB zu gewinnen. Es werden spezifische Datensätze wie die Verteilung von Objekten nach Kategorien (Bücher, Bilder, Artefakte usw.), Zeitstempel von Objekten (Erstellungs- und Digitalisierungsdatum) und geografische Daten (Herkunftsorte der Objekte) untersucht. Teilnehmer erfahren, wie man diese Daten mithilfe von Python-Bibliotheken visualisiert, um Trends, Muster und Beziehungen zu erkennen.

### Python-Bibliotheken

- `pandas`: Zum effizienten Laden und Manipulieren von Daten.
- `matplotlib` und `seaborn`: Für die Erstellung von Grafiken und Diagrammen.
- `geopandas` und `folium`: Für geografische Datenvisualisierungen, die aufzeigen, woher die Objekte stammen oder wie sie geografisch verteilt sind.

