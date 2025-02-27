# data_mining_dsba
Das Repository für den DBUAS Kurs Data Mining im DSBA


# Aufbau des repos
data_mining_dsba/
│
├── data/
│   ├── raw/                   # Unveränderte, originale Daten
│   └── processed/             # Vorverarbeitete Daten (cleaned)
│
├── notebooks/                 # Jupyter Notebooks für Exploration und Prototyping
│   ├── 01_exploratory_analysis.ipynb
│   └── 02_model_training.ipynb
│
├── src/                       # Wiederverwendbarer Code (Module, Funktionen, Klassen)
│   ├── __init__.py
│   ├── data_processing.py
│   └── model.py
│
├── tests/                     # Unit-Tests für den Code in src/
│   ├── test_data_processing.py
│   └── test_model.py
│
├── docs/                      # Dokumentation (z. B. technische Spezifikationen, Manuals)
│   └── projektbeschreibung.md
│
├── environment.yml            # Conda-Umgebung oder
├── requirements.txt           # Python-Abhängigkeiten (alternativ)
│
├── .gitignore                 # Dateien/Ordner, die nicht ins Repository sollen
│
├── README.md                  # Projektübersicht, Installations- und Nutzungsanleitung
│
└── LICENSE                    # Lizenzinformationen
