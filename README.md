# BPMN-project-Business-process-modeling

## Process Overview
BPMN-basierte Prozessmodellierung eines landwirtschaftlichen Robotersystems
Ziel des Prozesses

Ziel des Projekts ist die Modellierung eines ganzheitlichen Geschäftsprozesses zur Planung, Zuweisung, Ausführung und Überwachung landwirtschaftlicher Feldarbeiten mithilfe autonomer Roboter. Der Fokus liegt auf der strukturierten Abbildung operativer, technischer und strategischer Abläufe unter Berücksichtigung verschiedener Rollen und Ereignisse.

## Beteiligte Rollen

Feldbesitzer / Benutzer – Verwaltung und Bearbeitung eigener Felder

Administrator – Operative Planung und Zuweisung von Aufgaben an Roboter

Roboter – Autonome Ausführung landwirtschaftlicher Tätigkeiten

Techniker – Technische Wartung, Fehleranalyse und -behebung

Strategischer Planer – Langfristige Planung zukünftiger Feldarbeiten

## Prozessübersicht (End-to-End)

Feldverwaltung durch Feldbesitzer
Feldbesitzer können Felder anlegen, bearbeiten, Informationen einsehen sowie Anträge zur Feldbearbeitung, Bepflanzung oder Schädlingsbekämpfung erstellen. Die Prozesse sind wiederholbar und erlauben eine flexible Verwaltung der Felddaten.

Operative Aufgabenplanung (Administrator)
Täglich werden Arbeitspläne analysiert und Aufgaben geeigneten Robotern zugewiesen. Die Auswahl basiert auf Roboterkonfigurationen und Verfügbarkeit. Aufgaben können iterativ verteilt werden, bis alle geplanten Tätigkeiten zugewiesen sind.

Ausführung landwirtschaftlicher Aufgaben (Roboter)
Roboter führen je nach Aufgabentyp Tätigkeiten wie Pflanzenanbau, Ernte oder Unkrautentfernung aus. Nach Abschluss wird automatisch ein Ergebnisbericht erstellt. Bei Fehlern wird ein Fehlerbericht generiert und relevante Stakeholder informiert.

Technische Wartung und Fehlerbehebung (Techniker)
Fehler können zeitgesteuert oder ereignisbasiert erkannt werden. Nach der Analyse erfolgt entweder eine Neukonfiguration oder eine technische Reparatur des Roboters. Anschließend wird der Roboter getestet. Der Prozess wird iterativ wiederholt, bis keine Fehler mehr vorliegen.

Strategische Planung (Strategischer Planer)
Wöchentlich werden Anfragen der Feldbesitzer analysiert und daraus langfristige Einsatzpläne erstellt. Diese Pläne werden an den Administrator übermittelt und dienen als Grundlage für zukünftige operative Aufgaben.

## Verwendete BPMN-Konzepte

Timer-, Message- und Conditional Events

Exclusive und Parallel Gateways

Swimlanes zur klaren Verantwortungszuordnung

Iterative Prozessschleifen (Loops)

Trennung operativer, technischer und strategischer Prozesse

## Mehrwert des Modells

Das BPMN-Modell ermöglicht eine transparente Darstellung komplexer Abläufe und zeigt die Interaktion zwischen Geschäftsprozessen und IT-Systemen. Es unterstützt die Analyse von Optimierungspotenzialen, verbessert die Kommunikation zwischen Fachbereichen und IT und bildet eine solide Grundlage für die technische Umsetzung in Informationssystemen.
