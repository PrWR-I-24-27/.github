# Projektauftrag Nr. 3: Interaktive Risiko-Netzwerkanalyse (IDAF)

## 1. Orientierung

Im modernen Risikomanagement sind Gefahren systemisch vernetzt. Der
Ausfall einer Komponente kann kaskadenartige Effekte im gesamten
Netzwerk auslösen. Dieser Projektauftrag verknüpft die Informatik
(Datenvisualisierung mit Python) mit methodischer Risikoanalyse. Der
Fokus liegt auf technischer Exzellenz, Code-Effizienz und der
Nutzerführung (UX). 

## 2. Absicht

Das Ziel ist die Identifikation und Visualisierung von Risikostrukturen
mittels **Graph-Theorie**. Durch den Einsatz von `NetworkX` und `Quarto`
transformieren Sie abstrakte Daten in ein intuitiv bedienbares
Dashboard. Sie beweisen dabei, dass Sie komplexe technische
Anforderungen in ein sauberes, wartbares und benutzerfreundliches
Produkt überführen können. 

## 3. Auftrag

Erstellen Sie als Team ein **interaktives Quarto-Dashboard**, das eine
Risiko-Netzwerkanalyse abbildet. Das Endprodukt muss technisch stabil
(DRY-Prinzip), sprachlich einwandfrei und nach modernen UX-Standards
gestaltet sein. 

## 4. Besondere Anordnungen

### Zeitplan & Meilensteine

| Phase | Meilenstein / Deliverable | Termin |
| --- | --- | --- |
| **Konzeption** | Disposition (via README) | **27.02.2026** |
| **Finalisierung** | Abgabe Dashboard (fertig gerendert) | **10.04.2026** |

### Technische Vorgaben

* **Stack**: Python (`NetworkX`), Quarto-Dashboard-Layout, GitHub.
* **Programmiergrundsatz**: Konsequente Anwendung von **DRY (Don't
  Repeat Yourself)**. Redundanter Code führt zu Punktabzug.
* **Scope**: Mindestens **10 Knoten** im Netzwerk.

### Bewertungskriterien

Die Gesamtnote setzt sich wie folgt zusammen:

1. **Produkt (66%)**:
* **Technik**: Einhaltung der DRY-Prinzipien und saubere Implementierung.
* **UX/UI**: Klarheit der Darstellung und Qualität der Benutzerinteraktion.
* **Sprache**: Fehlerfreie Texte (Deutsch).
* **Inhalt**: Plausibilität der Risiko-Modellierung (keine fachliche Tiefenprüfung).


2. **Prozess (33%)**:
* Individuelle Bewertung gestützt auf das **git-log** (Kontinuität, Commit-Qualität).



### Einschränkungen

* **Wichtig**: Ohne nachvollziehbare Git-Historie wird der Prozess mit
  einer **Note 1** beurteilt. 

## 5. Erreichbarkeit

* **Support**: Alle technischen und organisatorischen Anfragen erfolgen via **GitHub Issues**.
* **Abgabeweg**: **Pull Request (PR)** auf den Main-Branch. Zuweisung des PR an den Mentor.
* **Feedback**: Erhalten Sie direkt als Kommentar im Merge Commit nach Projektabschluss.



# Projektauftrag Nr. 2

## Orientierung

Mit dem Projektauftrag Nr. 1 haben Sie das Format Jupyter Notebook
kennengelernt. Im Projektauftrag Nr. 2 geht es nun darum, ein Jupyter
Notebook als Grundlage für eine Onlinepublikation zu verwenden.

## Absicht

Ich will, dass Sie in Gruppen einen Text im Sinne des 
<a href="https://de.wikipedia.org/wiki/Datenjournalismus" target="_blank">
Data Driven Journalism
</a>
Verfassen und diesen mit einem geeigneten Framework publizieren.

## Auftrag

Verfassen Sie eine datengestützte Reportage zu einem aktuellen
wirtschaftlichen Thema.

## Besondere Anordnungen

### Termine

* Abgabe Themenbewerbung: 24. Oktober 2025
* Abgabe Disposition: 30. Oktober 2025
* Abgabe Reportage: 23. Dezember 2025

### Arbeitsprozess

Der gesamte Arbeitsprozess richtet sich nach den verschiedenen *Best
Practices* Beschreibungen von GitHub.  
Ein besonderer Hinweis gilt für die Disposition. Diese ist der
*laufende* Arbeitsplan. Das bedeutet, dass sie immer wieder an die sich
ändernden Gegebenheiten angepasst werden muss. Dies gilt insbesondere
für den Zeitpunkt nach der offiziellen Abgabe vom 30. Oktober 25. Die
Disposition ist denn auch *das einzige Dokument*, dass von Ihnen direkt
in den Branch `main` gemergt werden darf.

### Technische Vorgaben

* Die Abgaben haben als Pull Request auf Main zu erfolgen.
* Die Reportage hat aus einer Kombination von Text und Grafik(en) zu
  bestehen.
* Für die Aufbereitung der Daten ist `pandas` zu verwenden.
* Für die Erstellung der Grafiken ist `matplotlib`, `seaborn`, `plotly`
  oder `bokeh` zu verwenden.
* Die Verwendung weiterer Python Libraries ist ausdrücklich erlaubt.
* Die Verwendung von generativer KI ist in einem Abschnitt *Methoden* zu
  beschreiben. 
* Die Texte und Grafiken sind in einem `dev` Branch bzw. allfälligen
  Unterbranches zu `dev` zu erstellen.
* Die Disposition ist im README.md des jeweiligen Repositorys zu
  erstellen.
* Der Code für die Datenaufbereitung und das erstellen der Grafiken ist
  in der Publikation auszublenden.
* Sämtliche Abgaben haben als Pull Request mit mir als Assignee zu
  erfolgen. 

### Themen

* Die Auswirkung des Fahrplans des öffentlichen Verkehrs auf die Kosten
  fürs Wohnen

  Bearbeitet von Jakub, Luca und Lucien
* Die Auswirkung des Ausbaus des S-Bahn-Netzes im Kanton Zürich auf das
  Bevölkerungswachstum in den angeschlossenen Gemeinden

  Bearbeitet von Lenas, Laurens Sp. und Mathis
* Der Zusammenhang zwischen der Beleuchtungsdichte an öffentlichen
  Plätzen und der Anzahl gemeldeter Bagatelldelikte in der Stadt Zürich

  Bearbeite von André, Jonas und Matteo sowie

  Tymur, Laurens und Josua
* Der Zusammenhang zwischen Bildungsausgaben pro Kanton und Erfolgsquoten an (Matura) Prüfungen

  Bearbeitet von Guy, Sebastian und Silvan

### Beurteilungskriterien

* Datenbasierung  
  Beruht die Story tatsächlich auf einer belastbaren Datengrundlage?
* Datendarstellung  
  Wurde eine passende Darstellungsform für die Datengrundlage gewählt?
* Text  
  Ist der Text sprachlich korrekt und schlüssig formuliert?
* GitHub-Workflow
  Wurden die Vorgaben eingehalten?  
  Entsprechen die Commits den git Best Practices?
* Code  
  Ist der Code nachvollziehbar aufgebaut (inklusive Kommentare)

## Erreichbarkeiten

Sie erreichen mich via GitHub Issue. Das Issue ist mir zuzuweisen.

# Projektauftrag Nr. 1

## Orientierung

Im vorliegenden Projekt geht es darum, erste Erfahrungen mit Jupyter
Notebooks, pandas und matplotlib zu sammeln.

## Absicht

Ich will, dass Sie in Gruppen Daten aus zwei offiziellen Quellen
fusionieren und in geeigneter Form visualisieren.

## Auftrag

Erstellen Sie in einem Jupyter Notebook eine Datenanalyse, die die
fusionierten Daten visualisiert.

## Besondere Anordnungen

* Arbeiten Sie in Dreiergruppen.
* Erstellen Sie ein Repository für Ihr Team.
* Arbeiten Sie in feature branches bzw. in einem dev branch.
* Verwenden Sie Pull Requests, um Ihre Änderungen in den dev branch zu
  integrieren. 
* Verwenden Sie branch protection rules, um sicherzustellen, dass nur
  überprüfte Änderungen in den main branch gelangen.
* Die Projektskizze ist im README des Teamrepository zu verfassen.
* Die Projektskizze soll Auskunft über die Teamzusammensetzung, die
  geplante Analyse und die verwendeten Datenquellen geben.
* Abgabetermin Projektskizze: 1. September 2025, 1200
* Abgabetermin: 26. September 2025 (per Pull Request vom dev nach main)
* Bewertungskriterien: 
  * Der durch Commits dokumentierte Prozess
  * Klarheit der Projektskizze
  * Qualität der verwendeten Daten
  * Eignung der Visualisierungen für die gewählten Daten
  * Nachvollziehbarkeit der Analyse (Code und Text)
  * Umsetzung der Best Practices für 
    <a href="https://www.w3schools.com/git/git_best_practices.asp?remote=github" target="_blank">git</a> und
    <a href="https://docs.github.com/en/repositories/creating-and-managing-repositories/best-practices-for-repositories" target="_blank">GitHub</a>
    (ab 5. September 2025, 0840)
* Ressourcen:
  * [Bundesamt für Statistik](https://www.bfs.admin.ch)
  * [Statistik Kanton Zürich](https://www.zh.ch/de/direktion-der-justiz-und-des-innern/statistisches-amt.html)
  * [Open Data Portal](https://opendata.swiss)
  * [Dataviz Project](https://datavizproject.com)
  * [pandas Documentation](https://pandas.pydata.org/docs/)
  * [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)

## Erreichbarkeit

Ich bin während der Lektionen direkt erreichbar. Ausserhalb der
Lektionen erreichen Sie mich via mir zugewiesenem Issue.
