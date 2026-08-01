# PropertyValuePredictor

![Python](https://img.shields.io/badge/-Python-316A99?logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/-Jupyter%20Notebook-F37726?logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-Scikit%20learn-3499CD?logo=scikitlearn&logoColor=white)


Predicting property prices with machine learning using the **Ames Housing Dataset**. 
I have created this project as task for the AI club at Jagiellonian University.
The goal was to build and compare multiple models capable of estimating residential property prices based on 79 characteristics describing each house.

## Dataset - Ames Housing
I used the [Ames Housing Dataset](https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset) from Kaggle. It contains data on residential houses sales at *Ames in Iowa* during the years 2006 to 2010. Dataset consists of *2,930* house sale records, each with *79 features*. The features include either numerical and categorical variables, such as *lot size, number of rooms, foundation type, sale type and more*.

Data contained many missing values. The target (SalePrice) was very left skewed and I used Log Tranfrom on it. Ames Housing Dataset has many string features, it was required to encode them. I used one hot encoding, target encoding and ordinal encoding for ordinal columns. While using this dataset - it is important to remove outliers. I knew that there are a few big properties sold very cheap. I made manual filter to detect them. I also run IsolationForest (5%) on the train set. At the end I scaled data using StandardScaler.

## Models
## Results - Project summary

## Instalation and setup
1. **Clone repository from Github**
    ```
    git clone https://github.com/fistaszek2009/PropertyValuePredictor
    cd PropertyValuePredictor
    ```
2. **Create a virtual environment and install dependencies**
   
   Linux / macOS:
    ```console
    python -m venv .venv
    . .venv/bin/activate
    pip install -r requirements.txt
    ```

    Windows:
    ```console
    python -m venv .venv
    .venv\Scripts\activate
    pip install -r requirements.txt
    ```
3. **Open notebook**
   - ```solve-eng.ipynb```
   - ```solve-pol.ipynb```


## Project structure
```console
PropertyValuePredictor/
│
├── data/                        # Dataset (ignored)
├── .venv/                       # Virtual environment (ignored)
│
├── solve-eng.ipynb              # English notebook
├── solve-pol.ipynb              # Polish notebook
│
├── task-description.md          # Original assignment
├── data-description.txt         # Ames feature descriptions
├── project-presentation.pdf     # University presentation
│
├── requirements.txt
├── README.md
└── .gitignore
```

