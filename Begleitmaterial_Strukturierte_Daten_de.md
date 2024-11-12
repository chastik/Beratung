<!--
author:   Canan Hastik
email:    c.hastik@igsd-ev.de
version:  0.1.0
language: 
icon:     https://raw.githubusercontent.com/chastik/Beratung_Dateityp_Bild/refs/heads/main/SODa-Logo_full.svg
link:     https://raw.githubusercontent.com/chastik/Beratung/refs/heads/main/soda.css
comment:  Dieses Modul....
-->

# Wie unterscheiden sich strukturierte und unstrukturierte Datenformate?


## Strukturierte Datenformate

Strukturierte Datenformate sind als vordefiniertes Datenmodell oder Schema standardisiert. Damit isz eine klare Organisation der Daten möglich, sodass diese leicht von Maschinen gelesen, interpretiert und verarbeitet werden können. Die wichtigsten Datenformate sind:

1. Tabellenbasierte Formate

    - CSV (Comma-Separated Values): Ein einfaches textbasiertes Format, bei dem Daten in Zeilen und Spalten organisiert sind, wobei Spalten durch Kommas getrennt werden.
    - XLS/XLSX (Microsoft Excel): Ein binäres bzw. XML-basiertes Format, das von Microsoft Excel verwendet wird und umfangreiche Tabellendaten mit Formatierungen, Formeln und Makros speichern kann.

2. Hierarchische und strukturierte Formate

    - JSON (JavaScript Object Notation): Ein textbasiertes Format zur Darstellung von Datenstrukturen, insbesondere verschachtelten Arrays und Objekten, das weit verbreitet in Web-Anwendungen ist.
    - XML (Extensible Markup Language): Ein flexibles textbasiertes Format zur Beschreibung von Daten, bei dem benutzerdefinierte Tags verwendet werden, um die Struktur der Daten zu definieren.
    - YAML (YAML Ain't Markup Language): Ein menschenlesbares Format, das oft für Konfigurationsdateien verwendet wird und eine einfache Alternative zu JSON und XML darstellt.

3. Semantische Datenformate (für Linked Data)

    - RDF (Resource Description Framework): Ein XML-basiertes Format zur Darstellung von Informationen im Web, insbesondere für die Beschreibung von Beziehungen zwischen Ressourcen.
    - Turtle (Terse RDF Triple Language): Eine menschenlesbare Syntax für RDF, die kompakter ist als die XML-basierte Variante.
    - N-Triples: Ein einfaches Format zur Darstellung von RDF-Daten als eine Liste von Subjekt-Prädikat-Objekt-Tripletten.

4. Geodatenformate

    GeoJSON: Eine Erweiterung von JSON zur Darstellung geografischer Daten, wie z. B. Punkte, Linien und Polygone.
    KML (Keyhole Markup Language): Ein XML-basiertes Format, das von Google Earth und Google Maps verwendet wird, um geografische Informationen zu speichern.
    Shapefile (.shp): Ein binäres Format zur Speicherung von Geodaten, das häufig in GIS (Geographische Informationssysteme) verwendet wird.

5. Austauschformate für statistische Daten

    - SPSS (.sav): Ein proprietäres Format für statistische Daten, das von der Software SPSS verwendet wird.
    - Stata (.dta): Ein Format für statistische Daten, das von der Software Stata verwendet wird.
    - SAS (.sas7bdat): Ein proprietäres Format für statistische Analysen, das von der Software SAS genutzt wird.

6. Datenbank-Spezifische Formate

    - SQL (Structured Query Language): Kein Dateiformat im herkömmlichen Sinn, sondern eine Abfragesprache zur Verwaltung von Daten in relationalen Datenbanken.
    - SQLite (.sqlite): Ein plattformübergreifendes, leichtgewichtiges Datenbankformat, das als einzelne Datei gespeichert wird.
    - Postgres

7. Konfigurations- und Protokollformate

    - INI (Initialisation File): Ein einfaches textbasiertes Format zur Speicherung von Konfigurationsdaten.
    - Log-Dateien (.log): Textdateien, die strukturierte Protokolleinträge enthalten, oft im Zeilenformat mit Zeitstempeln.

8. Weitere Formate

    - HDF5 (Hierarchical Data Format version 5): Ein Format zur Speicherung und Organisation großer Mengen an numerischen Daten, oft in wissenschaftlichen Anwendungen verwendet.

Strukturierte Datenformate sind für die Datenanalyse, -statistik und -visualisierung grundlegend.


SIEHE AUCH https://aws.amazon.com/de/compare/the-difference-between-structured-data-and-unstructured-data/ 

## Unstrukturierte Dateitypen

Unstrukturierte Dateitypen haben keine vorab definierte Datenstruktur. Sie können Text, Multimedia oder Rohdaten sein, die ohne einheitliches Schema gespeichert werden. 

**Beispiele** sind Texte, Dokumente, E-Mails, Bild, Audio, Video, Webseiteninhalte, Social-Media-Posts, Sensor und IioT-Daten.

## Semi-strukturierte Daten

[[HTML]] HTML
[[JSON]] JSON
[[YAML]] YAML
[[E-Mails]] E-Mails
