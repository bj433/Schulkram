- Bezeichnet bei einem Computernetz die Struktur der Verbindungen mehrerer Geräte untereinander, um einen gemeinsamen Datenaustausch zu gewährleisten.
- Wichtig zur Beurteilung von: Ausfallsicherheit, Leistungsfähigkeit, Auswahl geeigneter Zugangstechniken und Netzwerkhardware

Physische Topologie: beschreibt den Aufbau der Netzverkabelung
Logische Topologie: beschreibt den Datenfluss zwischen den Endgeräten


Bus-Topologie

- Zentales Kabel (=Bus) als shared medium
- Passive Technologie, d.h. keine Signalregeneration durch angeschlossene Teilnehmer
- Signalausbreitung in beide Richtungen
- Signalschwächung (=Dämpfung) entlang der Leitung
	-> Einsatz von Repeatern nötig
	
Einsatzgebiete: In kleinen Netzwerken als Ethernet der Form 10Base5 und 10Base2, heute noch als wireless im Einsatz

Vorteile:

- Niedrige Kosten wegen kurzen Kabellängen
- Ausfall einer Station hat keinen Einfluss auf andere Stationen

Nachteile:

- Alle Daten werden über ein einzelnes Kabel übertragen
- Kein "gleichzeitiges" Senden mehrerer Stationen möglich
- Busunterbrechungen legen gesamtes Netz lahm und sind aufwendig zu finden
- Netzverkehr kann mitgelesen werden


Stern-Topologie

- Jedes Gerät nutzt ein eigenes Kabel
- Zentraler Verteiler (=Hub), durch Switches abgelöst

Einsatzgebiete: Heutige Ethernet-Versionen

Vorteile:

- Ausfall einer Station hat keinen Einfluss auf andere Stationen
- Aktive Verteiler wirken als Signalverstärker
- Beim Einsatz eines Switches können zwei Stationen die volle Bandbreite des Netzes nutzen, ohne andere Stationen zu beeinflussen
- Weitere Stationen und Verteiler können hinzugefügt werden

Nachteile:

- Große Kabelmengen
- Ausfall des Verteilers führt zu Netzwerkausfall


Ring-Topologie

- Geschlossene Form (Kabel haben kein Anfang und Ende)
- Alle Stationen verarbeiten und verstärken die angekommenen Signale und leiten sie ggf. weiter
- Datenverkehr nur in eine Richtung (Punkt-zu-Punkt)

Einsatzgebiete: selten, logisch in zentralen Ringleitungsverkehr realisiert

Nachteil: Ausfall einer Station kann das Netz lahmlegen


Topologie im LAN

- Meist sternförmig
- Netzwerkkarte in jeder Station; wird mit Verteiler verbunden
- Ein einfacher Hub sendet ein empfangenes Signal an alle weiter. Ersetzt man ihn durch einen Switch, so erzielt man höhere Durchsatzraten, weil dieser die Datenpakete nicht an alle, sondern nur an die Zieladresse (MAC-Adresse) weiterleitet

Structured Cabling System

- Stern innerhalb einer Etage; Bus von Verteiler zu Verteiler
- Ein Satz von Kopplungselementen (Kabel, Anschlusselemente, Verteiler)
- Bestimmte Verfahren und Standards zur Anwendung
- Reguläre, skalierbare Strukturen von Rechnernetzwerken können geschaffen werden
