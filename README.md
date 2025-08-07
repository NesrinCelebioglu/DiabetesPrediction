# Diabetes Prediction

Dieses Projekt implementiert ein Machine Learning-Modell zur Vorhersage von Diabetes anhand medizinischer Messwerte. Die Analyse basiert auf dem bekannten Pima Indians Diabetes-Datensatz.

## Projektübersicht

Ziel dieses Projekts ist es, ein Klassifikationsmodell zu erstellen, das vorhersagt, ob eine Person an Diabetes leidet oder nicht. Das Notebook beinhaltet:

- Datenexploration
- Datenvorverarbeitung
- Modelltraining (Logistische Regression)
- Evaluation der Modellleistung

## Datenquelle

Die verwendeten Daten stammen aus dem [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database). Die Merkmale umfassen unter anderem:

- Anzahl der Schwangerschaften
- Glukosekonzentration
- Blutdruck
- Hautfaltendicke
- Insulinspiegel
- BMI
- Diabetes-Pedigree-Funktion
- Alter

## Verwendete Bibliotheken

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn` (für Modellierung, Evaluation und Datenvorverarbeitung)

## Explorative Datenanalyse (EDA)

Das Notebook enthält visuelle Analysen zur Verteilung der Merkmale und zur Korrelation mit dem Zielwert (Diabetes). Einige Highlights:

- Boxplots zur Erkennung von Ausreißern
- Korrelationsmatrix mit Heatmap
- Histogramme der einzelnen Merkmale

## Datenvorverarbeitung

- Behandlung fehlender oder unrealistischer Werte (z. B. 0 bei BMI oder Blutdruck)
- Aufteilen in Trainings- und Testdaten (z. B. 80/20)
- Skalierung der Daten mit `StandardScaler`

## Modellierung

Das Hauptmodell ist eine **Logistische Regression**. Es wurde mithilfe von `sklearn` trainiert und getestet.

### Modellbewertung:

- **Genauigkeit (Accuracy)**
- **Konfusionsmatrix**
- **ROC-Kurve**
- **AUC-Wert**

## Ergebnisse

Das Modell zeigt solide Leistung bei der Klassifizierung, mit einer akzeptablen Balance zwischen Sensitivität und Spezifität. Die ROC-Kurve zeigt eine gute Trennung zwischen den Klassen.



---

