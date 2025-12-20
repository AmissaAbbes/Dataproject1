# Project-1
Project 1 - Cas, Utku, Amissa

# Klachten verwerkingsmodel
"Automatische classificatie van klachten binnen de juiste expertise"

|-----------------------------------------------------------------------------------------------|
| File                  | Omschrijving                                                          |
|-----------------------|-----------------------------------------------------------------------|
| `klachten.csv`        | Dataset                                                               |
| `klacht_test.csv`     | Dataset testdata 20%                                                  |
| `klacht_train.csv`    | Dataset traindata 80%                                                 |
| `klachten.ipynb`      | Notebook Analyse complete dataset                                     |
| `train.ipynb`         | Notebook traindata                                                    |
| `modelling.ipynb`     | Notebook modellen                                                     |
| `readme.md`           | Readme file: crisp-dm stappen, notebook omschrijvingen en instructies |
|-----------------------------------------------------------------------------------------------|

## Projectstructuur volgens CRISP-DM
1. **Business Understanding**
   Doel: automatische categorisatie van klachten binnen de juiste expertise met minimaal 90% accuratie

2. **Data Understanding**  
   Voor volledige dataset uitgevoerd in `klachten.ipynb`:
   Voor trainingsdata uitgevoerd in `train_eda.ipynb`:
   - Beschrijving van dataset
   - Visualisaties
   - Eerste observaties

3. **Data Preparation**  
   Uitgevoerd in `train.ipynb`:
   - vectorizer (tdidf en count)
   - lemmatizer
   - tokenizer

4. **Modeling**  
   Uitgevoerd in `modeling.ipynb`:
   - pipelines
   - randomizedsearch
   - gridsearch

   - SMOTE
   - logistic regression
   - naive bayes
   - random forest classifier
   - svc
   - svc calibrated

5. **Evaluation**  
   Evaluatie van modelprestaties met ....

6. **Deployment / Data Story**  
   PowerPoint-presentatie en rapport met inzichten.

## Vereisden:
- Python 3.x
- Jupyter Notebook
- Packages:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - nltk
  - collections
  - re
  - wordcloud
  - SciPy
  - imblearn

## Gebruik:
1. gebruikt dataset: `klachten.csv`.
2. installeer en laad bovenstaande libraries in (maak gebruik van een virtual enviroment om conflicten te voorkomen).
2.  - Open `klachten.ipynb` om data understanding en preparation uit te voeren op de 
      complete dataset.
    - Open `train_eda.ipynb` om data understanding en preparation uit te voeren op
      de trainingsdataset.
3. Gebruik de `klacht_train.csv` & `klacht_test.csv` datasets voor modellering.
4. Open de model notebooks om voorspellingen en evaluaties uit te voeren.
5. Bekijk de PowerPoint en het rapport voor de Data Story.
