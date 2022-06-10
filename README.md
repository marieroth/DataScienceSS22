# DataScienceSS22

Procedure to date

Step 1: Data Exploration 

Identifizierte Probleme in Bezug auf die Datenqualität 
  1. Missing Values
  2. Outliers
  3. Features to be transformed (eg. normalization)
  4. Fréatures to be removed (feature selection) 
  
 Step 2: Model Baseline and Data Preparation (Rapid Miner)
 
 Modell wurde entwickelt:
  1. Feature wip raus (zu viele MV und keine starke Correlation zum label)
  2. Restliche MV raus gefiltert (4 Zeilen - nicht durch Mittelwerte ersetzt, da ganze Zeilen waren) 
  3. alle Features die einen nicht signifikanten p-Value haben ebenfalls gekickt
  4. Bedinungen für Outliers gesetzt 
  
  -> Modell Schlecht 
  squared_correlation 0.275
  root_mean_squared_error: 0.217
  
  -> dennoch Datensatz gezogen und in Jupyter Notebook um zu checken ob wir hier finden warum das Modell so schlecht ist. 
  
  Step 3: 
  
    1. Jupyter Notebook erstellt 
    2. Datensatz rein geladen
    3. Lineare Regression Model erstellt
    4. Andere Modelle zum Vergleich erstellt
    
   -> Modell immer noch schlecht 
