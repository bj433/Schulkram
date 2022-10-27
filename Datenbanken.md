Definition:
	- System zur elektronischen Datenverwaltung/Datenorganisation
	- Dabei wichtig: Effizienz, Widerspruchsfreiheit, Konsistenz, Sicherheit
	- Aufgaben einer Datenbank:
		○ Zugriff auf die Daten ermöglichen, ohne dass Informationen über die Datenorganisation innerhalb der Datenbank erforderlich sind
		○ Schutz vor nicht erwünschten Zugriffen und ungewollten Manipulationen an den Daten
		○ Daten gegen parallelen Zugriff mehrerer Benutzer schützen

Begriffe:

Redundanz:
	- Das Vorhandensein von eigentlich überflüssigen, für die Informationen nicht notwendigen Elementen; Überladung mit Merkmalen
	- Sollte in Datenbanken vermieden werden -> redundanzfreie Datensicherung
Konsistenz (auch Integrität von Daten)
	- Die Korrektheit der in Datenbanken gespeicherten Daten
		○ 2 Perspektiven:
			-> "klassische" relationale Datenbanken
			-> Verteilte Systeme
	- Arten von Integritätsbedingungen:
		1. Bereich: Wert von Attributen in bestimmten Wertbereichen
		2. Entitätsintegrität: Primärschlüssel müssen eindeutig sein und der Feldinhalt eines Primärschlüssels darf auf keinen Fall leer (not null) sein
		3. Referentielle Integrität: Der Wert einer Referenz/eines Fremdschlüssels muss entweder NULL oder existent sein. Steht ein Wert in einem Feld eines Fremdschlüssels, so muss das referenzierte Objekt existieren.
Datenbankmanagementsystem (DBMS)
	- Beschreibung des Aufbaus von Daten
	- Verwaltung der Daten
	- Abfrage der Daten
	- Suchen, lesen und schreiben der Daten
	- Bietet Schnittstellen nach außen, um auf den Daten arbeiten zu können
Datenbanksprache
	- Schnittstelle zwischen Benutzer/Programm und dem DBMS
	- Datenbanksprache wird vom DBMS interpretiert und ausgeführt
	- SQL (Structured Query Language) -> weit verbreitet
	- Bestandteile einer Datenbanksprache:
		○ Datendefinition (Tabellen erstellen, Felder definieren)
		○ Datenmanipulation (Datensätze eingeben, löschen, verändern)
		○ Datenabfrage (Datensätze aus der Datenbank abfragen)
		○ Datenschutz (Datenschutz vor unberechtigten Zugriffen)

