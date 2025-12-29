# INKAR-Daten mit Python laden (Jupyter Notebook)

Dieses Jupyter Notebook zeigt Schritt für Schritt, wie **regionale Indikatoren aus dem INKAR-System** (Indikatoren und Karten zur Raum- und Stadtentwicklung) programmgesteuert mit **Python** geladen, aufbereitet und für Analysen sowie Visualisierungen genutzt werden können.

Das Notebook wird im Rahmen der Lehrveranstaltung  
**Data Visualization & Data Storytelling** eingesetzt.

---

## 1. Was ist INKAR?

**INKAR** ist ein vom **Bundesinstitut für Bau-, Stadt- und Raumforschung (BBSR)** bereitgestelltes Indikatorensystem zur:

- Raum- und Regionalentwicklung  
- Stadt- und Kreisanalyse  
- Sozial-, Wirtschafts- und Demografieanalyse  

INKAR stellt Daten für unterschiedliche **Raumbezüge** bereit, z. B.:

- Kreise und kreisfreie Städte  
- Regierungsbezirke  
- Bundesländer  
- Raumordnungsregionen  

🔗 Offizielle Website:  
https://www.inkar.de

---

## 2. Was macht dieses Notebook?

Das Notebook zeigt:

- wie man **INKAR-Daten** lädt  
- wie man mit **mehreren Indikatoren und Jahren** arbeitet  
- wie man Raumbezüge filtert (z. B. nur Bayern oder Nordbayern)  
- wie man typische Datenprobleme löst (z. B. Dezimaltrennzeichen)

Am Ende stehen **saubere DataFrames**, die direkt für:
- Diagramme (Matplotlib, Plotly)
- Karten (GeoPandas)
- Animationen
verwendet werden können.

---

## 3. Voraussetzungen

### Python-Pakete

Bitte stelle sicher, dass folgende Pakete installiert sind:

```bash
pip install pandas requests tqdm pyarrow
