# PropertyValuePredictor

![Python](https://img.shields.io/badge/-Python-316A99?logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/-Jupyter%20Notebook-F37726?logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-Scikit%20learn-3499CD?logo=scikitlearn&logoColor=white)


Predicting property prices with machine learning using the **Ames Housing Dataset**. 
I have created this project as task for the AI club at Jagiellonian University.
The goal was to build and compare multiple models capable of estimating residential property prices based on 79 characteristics describing each house.

## Dataset - Ames Housing
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

