# Solarertragsrechner

Dieses Repository enthält ein Python-Programm, das den Ertrag einer Solaranlage unter Berücksichtigung des Sonnenstandes und der Ausrichtung von bis zu vier Solarmodulen berechnet. Das Tool ist mit der Python-Anwendung `marimo` und dem Python-Modul `pysolar` implementiert.

## Funktionen

- Berechnet den Solarertrag basierend auf dem Sonnenstand und der Ausrichtung der Module
- Unterstützt bis zu vier Solarmodule
- Verwendet `marimo` für die Anwendungsstruktur
- Nutzt `pysolar` für genaue Berechnungen des Sonnenstandes

## Installation

Klonen Sie das Repository:

```bash
git clone https://github.com/ruboerner/Solarertragsrechner.git
```

Um die notwendigen Abhängigkeiten zu installieren, kann `pip` verwendet werden:

```bash
pip install -r requirements.txt
```

## Aufruf

Nach der Installation wird folgender Befehl im Projektordner eingegeben:

```bash
marimo run solarertragsrechner.py
```

## Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert. Siehe die [[LICENSE]] Datei für Details.

## Danksagung

- [marimo](https://marimo.io)
- [pysolar](https://github.com/pingswept/pysolar)
