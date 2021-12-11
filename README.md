# h_da machine learning challenge - NO2 prediction on different crossings in Darmstadt

## Einleitung
Die h_da machine learning challenge wurde im Sommer 2021 durchgeführt. Hierbei ging es darum den Stickstoffdioxidgehalt (NO2) pro m³ Luft an verschiedenen Kreuzungen in Darmstadt vorherzusagen. Es wurden ca. 40 Features, welche verschiedenste Wetterdaten und Daten von Verkehrssensoren zur Vorhersage genuzt. Die Challenge war ein Regressionsproblem, welche den RMSE als Evaluationsmetrik genutzt hat. In der Challenge belegte ich den 3. Platz mit einem RMSE von 26.

## Beschreibung
Für das feature selection und feature creation habe ich eine ausführliche EDA durchgeführt. Die Resultate dieser sind in dem Notebook "DAnalyticsSS21_EDA.ipynb" zu sehen. Anschließend habe ich verschiedene Algorithmen und deren Hyperparamter mittels K-Fold Cross Validation getestet. Der Algorithmus mit der bei weitem besten Performance war XGBOOST. Das Notebook "ML_Model_XGBoost.ipynb" zeigt die Erstellung und Evaluation des Modells. Eine detailliertere Version der Vorgehensweise und der Ergebnisse lassen sich in der <b>Powerpoint Präsentation</b> finden.

## Weitere Analysemöglichkeiten
Weitere Analysemöglichkeiten liegen im Bereich der Zeitreihenanalyse mithilfe von Neuronalen Netzen. Da die Verkehrssensoren beispielsweise minütliche Messungen durchführen lässt sich die Verkehrssituation mit dieser Methode wahrscheinlich gut modellieren.
