# Einführung in die OOP mit C++

## Was ist ein Objekt?
- Eigenschaften, repräsentiert als Daten
- Operationen, repräsentiert als Funktionen

### Eigenschaften (Attribute)
- Beschreiben Aussehen und Funktionsweise eines Objektes

### Methoden (Funktionen)
- Funktionsweisen von Objekten
- Methoden zur Interaktion/Arbeit mit Objekten
#### - Technische Sicht
  - Objekt = Datenstruktur im Arbeitsspeicher
  - Eigenschaften = Variablen mit bestimmten Datentyp
  - Abhängigkeiten möglich

## Was ist eine Klasse?
- Schablone/Bauplan für Objekt
- Beschreibung von Eigenschaften und Methoden eines Objekts
- Eigenschaften besitzten keine konkreten Werte

## Objekte in C++
- Datenorganisation durch Objekte
- Objektzugriff (explizit/implizit) über Zeiger
- Sammlung von Feldern
  - Elementarer Typ
  - Referenz zu anderem Objekt
- Objekte = verpackt: Zugriff über Zugriffsprozeduren oder explizit öffentliche Felder
- Klasse assoziiert Prozeduren (Methoden) mit Objekt-Typ
- Abstrakte Klassen können Implementierung der Prozeduren weglassen - Schnittstelle verbleibt
- Typ eines Objekts spezifiziert externe Schnittstelle
- Objekt-Typen erweiterbar
  - Kein Verlust der Kompatibilität mit Basis-Typ
  - Vererbung
- Erzeugung von Objekten durch Klasse mit Hilfe von Konstruktoren (Instanzierung)
