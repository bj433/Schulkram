![image](https://user-images.githubusercontent.com/104757507/198281048-fd5b695e-09f2-4487-9dbf-8c63f4a7ba16.png)

Notation nach Prof. Dr. Scheer -> (EPK) - Ereignisgesteuerte Prozesskette

Kriterien zum Bestehen eines Unternehmens:

	- Hohe Qualität der Produkte und Dienstleistungen
		○ Beratungs- und Dienstleistungsfunktionen inbegriffen
	- Hohe Flexibilität im Umgang mit unterschiedlichen Kundenwünschen
	- Möglichst geringer Zeitaufwand für die Umsetzung der Kundenwünsche
	- Eine große Vielfalt unterschiedlicher Abläufe sind zu berücksichtigen, um betriebliche Leistungen erzielen zu können
	- Möglichst niedrige Kosten für die Produktion und die damit verbundenen Abläufe innerhalb sämtlicher Organisationseinheiten im Unternehmen

Spannungsbild geschäftlicher Aktivitäten:

![image](https://user-images.githubusercontent.com/104757507/198281206-5b875492-c047-4267-bc05-79d1086a79b6.png)

Ein Geschäftsprozess stellt eine Folge von Aktivitäten dar, die

	- In einem logischen Zusammenhang stehen
	- Inhaltlich abgeschlossen sind
	- Unter Zuteilnahme von Ressourcen und Informationen
	- Durch Menschen und/oder Maschinen
  
Im Hinblick auf ein Unternehmensziel ausgeführt werden

Vorteile an prozessorientierter Vorgehensweise

	- Abläufe werden ganzheitlich betrachtet
	- Eindeutige Zuordnung von Verantwortung für die Aktivitäten
	- Einsparung von Kosten für die Dateneingabe
	- Laufende Aktualisierung der Datenbestände
	- Fehlerverringerung in allen Phasen der Produktion und Kundenbetreuung

Darstellung der Geschäftsprozesse mit ereignisgesteuerten Prozessketten

-> Zeigen Ablaufstruktur aus Ereignissen und Funktionen

Grundelemente:

![image](https://user-images.githubusercontent.com/104757507/198281409-0955eb38-0dfd-4744-a9ea-a3edd0023b8d.png)

Operatoren:

XOR: Entweder - Oder

	- Funktionen/Ereignisse schließen sich gegenseitig aus

^ : Oder

	- Funktionen/Ereignisse können, müssen aber nicht parallel auftreten

V : Und

	- Funktionen/Ereignisse müssen parallel auftreten


Modellierungsregeln:

	- Geschäftsprozess beginnt immer mit einem oder mehreren Ereignissen
	- Geschäftsprozess endet immer mit einem oder mehreren Ereignissen
	- Alle Ereignisse, Funktionen und Operatoren müssen über Linien verbunden werden
	- Ein Ereignis hat immer nur einen Eingangs- und einen Ausgangspfeil
	- Ereignisse können nicht direkt mit anderen Ereignissen verbunden werden
	- Eine Funktion hat immer nur einen Eingangs- und einen Ausgangspfeil, bei zugeordneten Informationsobjekten können es auch mehrere Eingangs- und/oder Ausgangspfeile sein
	- Funktionen können nicht direkt mit Funktionen verbunden werden
	- Eine Funktion folgt einem oder mehreren Funktionen und führt zu einem oder mehreren Ereignissen
	- Mit Operatoren werden Verzweigungen innerhalb eines Geschäftsprozesses dargestellt. Sie werden im Anschluss an Ereignisse oder Funktionen eingesetzt.
	- Verzweigungen können entweder im Anschluss an ein Ereignis oder an eine Funktion vorgenommen werden (an Ereignisse nur bei "und")
	- Operatoren können unmittelbar hintereinander geschaltet werden
	- Organisationseinheiten werden Funktionen zugeordnet
	- Informationsobjekte werden Funktionen zugeordnet
	- Gestrichelte Linien zu Informationsobjekten; keine Linien zu Organisationseinheiten



