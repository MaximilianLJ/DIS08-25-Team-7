DIS08-25-Team-7 – Group 7 – Data Modeling
1. Team

Maximilian L. Jäger – 11333148

Emirhan Hamit Eraslan – 11404231

2. Project Topic

Migration und öffentliche Meinung in Deutschland (2010–2024)

Dieses Projekt untersucht, wie sich die jährliche Zuwanderung nach Deutschland zwischen 2010 und 2024 entwickelt hat und wie sich im gleichen Zeitraum die Einstellungen der Bevölkerung gegenüber Migration verändert haben. Zudem wird analysiert, ob zwischen realer Migration und öffentlicher Meinung statistische Zusammenhänge bestehen.

Der Zeitraum umfasst migrationspolitisch relevante Ereignisse wie die EU-Arbeitsmarktöffnung, die Fluchtmigration 2015/2016, die Corona-Pandemie und den Ukrainekrieg. Diese bieten eine geeignete Grundlage für eine datengetriebene Analyse.

3. Dataset Selection
3.1 Open Data Sources

Destatis / Eurostat
Jahresdaten zu Zuwanderung, Wanderungssaldo, Herkunftsländern sowie Bevölkerungsbewegungen.

BAMF – Bundesamt für Migration und Flüchtlinge
Asylgeschäftsstatistiken, Anerkennungsquoten, Schutzberechtigte.

Eurobarometer / ALLBUS (GESIS)
Einstellungsdaten der Bevölkerung zu Migration, Integration und gesellschaftlichen Fragen.

3.2 Optional Additional Sources (Enrichment)

Diese Quellen dienen der späteren Datenanreicherung (optional für Milestone 2):

Google Trends (Suchinteresse zu Begriffen wie „Migration“, „Asyl“, „Flüchtlinge“)

Twitter/X API (Stimmungsanalyse, Keyword-Frequenz)

Nachrichtenportale (Artikel-Häufigkeiten zum Migrationsthema)

4. Research Questions

RQ1: Wie haben sich die jährlichen Zuwanderungszahlen nach Deutschland zwischen 2010 und 2024 entwickelt?

RQ2: Wie haben sich die Einstellungen der Bevölkerung gegenüber Migration im gleichen Zeitraum verändert?

RQ3: Besteht ein statistischer Zusammenhang zwischen Zuwanderungsniveau und negativen Einstellungen gegenüber Migration?

RQ4 (optional): In welchem Verhältnis stehen mediale bzw. online-basierte Aufmerksamkeit (z. B. Google Trends, Nachrichtenartikel) zu Stimmungsänderungen gegenüber Migration?

5. Hypotheses

H1: Höhere Zuwanderungsraten korrelieren mit negativeren Einstellungen der Bevölkerung gegenüber Migration.

H2: Nach Phasen stark erhöhter Zuwanderung (z. B. 2015–2016) verbessert sich die Einstellung zur Migration mit zeitlicher Verzögerung wieder.

H3 (optional): Die Einstellungen variieren zwischen unterschiedlichen Bevölkerungsgruppen (z. B. Altersgruppen oder Bildungsniveaus).

6. Roadmap (Aligned with Course Milestones)
Date	Task	Description
07.11.2025	Topic, datasets, research questions, roadmap	Abschluss Milestone 1
13.11.2025	Data collection	Download von Destatis, Eurostat, BAMF und Eurobarometer
20.11.2025	Data cleaning	Bereinigung, Formatierung, Umgang mit fehlenden Werten
04.12.2025	Data integration	Zusammenführung und Strukturierung der Datensätze
12.12.2025	Pipeline prototype	Erstellung einer einfachen ETL-Pipeline (Obtain → Scrub → Explore → Model → Interpret)
18.12.2025	Analysis	Deskriptive Statistik, Korrelation, erste Hypothesentests
08.01.2026	Visualization	Erstellung von Diagrammen und Auswertungen
15.01.2026	Documentation	Vorbereitung des Posters und der finalen Dokumentation
19.01.2026	Final presentation	Präsentation des Notebooks und Projektergebnisse
7. Tools and Methods

Python (Jupyter Notebook)

Pandas, NumPy, Matplotlib, Seaborn

Git & GitHub (Version Control)

Markdown (Dokumentation)

FAIR & Open Data Principles

OSEMN-Pipeline (Obtain, Scrub, Explore, Model, Interpret)

8. Project Goal

Ziel ist der Aufbau einer datengetriebenen Pipeline, die den Zusammenhang zwischen Migration, öffentlicher Meinung und medialer Aufmerksamkeit in Deutschland von 2010 bis 2024 untersucht. Die Ergebnisse werden anhand eines Jupyter Notebooks, statistischer Analysen und Visualisierungen nachvollziehbar dargestellt und im Poster präsentiert.





                                                                                                               (KI Sktrukturiert)
