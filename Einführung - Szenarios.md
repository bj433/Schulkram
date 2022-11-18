Szenario 1 "No Backup"

Vulnerabilities
 
 - Backup-Speicherort/-art nicht gegen Naturkatastrophen geschützt
 - Fehlende regelmäßige Überprüfung des Backupverfahrens
 - Ein zentraler Server
 - Kein RAID
 - Potentiell nicht besonders abgesichertes Adminbüro als Serverraum & Backupspeicherort

Threats
 
 - Naturkatastrophen (Feuer/Überflutung)
 - Disaster-Recovery nicht durchführbar
 - Single Point of Failure -> Zentraler Angriffspunkt
 - Keine redundante Datenhaltung -> Nur Backupdaten verwendbar im Falle eines Festplattencrashes
 - Jede Person, die physischen Zugang zum Serverraum bekommt, kann auf das gesamte System zugreifen

Risks

 - Gefahr des Totalausfalls digitaler Informationen (Daten)
 - Jobverlust für Arbeitnehmer
 - DSGVO-Verstöße -> Imageverlust

Measures

 - Imageserver z.B beim externen IT-Provider
 - Offline Backups
 - Physische Maßnahmen der Zugriffsbeschränkung


Szenario 2 "infection by computer viruses"

Vulnerabilities

 - Antivirussoftware wird nur unregelmäßig geupdated (Virusdefinition)
 - Schulungsdefizite hinsichtlich IT-Sicherheit für Mitarbeiter
 - Keine automatischen Updates
 - Keine redundante Datenhaltung/Backups
 - Keine Filter im Mailserver
 - Lokale Datenhaltung
 - Mangelnde Softwaremanagementpraktiken
 - Diverse Virus-Scanner

Threats

 - Unbedarftes Verhalten der Mitarbeiter
 - Veraltete Sicherheitslücken können ausgenutzt werden
 - Virenbefall/Phishing
 - Komplettabschaltung der IT notwendig
 - Datenverlust
 
Risks

 - Lahmlegung des Firmennetzwerks
 - Imageschaden
 - Nachvollziehen von Firmenmails
 - Finanzieller Schaden aufgrund der Abschaltung
 
Measures

 - Abschaltung des Systems
 - Schulung der Mitarbeiter
 - Automatisierung von Virenscannern und zugehörigen Updates (zentral gesteuert)
 - Zentralisierung der Daten -> Integration ins Netzwerk
 - Einrichtung von Backups
 - Vereinheitlichung der IT-Infrastruktur


Szenario 3 "Sudden departure of the administrator"

Vulnerabilities

 - Nur der Admin ist über administrative Aufgaben unterrichtet
 - Schlechte Dokumentation
 - Adminpasswort nirgends notiert

Threats

 - Keine Administration möglich
 - Mitarbeiter können nicht arbeiten -> Geldverlust
 - Systeme nahezu ungeschützt vor Gefahren - Keine Datenführung
 - Keine Backups?

Risks

 - Gefahr vor ungeschütztem Totalausfall
 - Jobverlust

Measures

 - Zurücksetzen des Adminpassworts und Notieren dieses Passworts
 - Aufbesserung der Dokumentation -> Erstellen einer klaren Daten- und Prozessstruktur
 - Gründung eines Teams zu Administration
 - Einrichtung eines Backups


Szenario 4 "Hacker attack from the Internet"

Vulnerabilities

 - Vertrauliche Daten sind nur auf einem passwortgeschützten PC gesichert
 - Keine Sicherung durch jemand Anderen -> Fehleranfälligkeit, weil der Arzt alles macht

Threats

 - Patienteninformationen "liegen" ungeschützt im Netz
 - Ausfallen von Softwareupdates/Backups
 - Jobverlust für den Arzt

Risks

 - Informationen werden von Dritten ausgenutzt
 - Gefahr vor Datenverlust

Measures

 - Sicherung auf einem externen Gerät/Server
 - Firewall/Virenschutz
 - Ordnerzugriffe anpassen/verschlüsseln (Passwort/Keys)

