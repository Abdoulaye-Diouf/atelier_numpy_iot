#  Atelier NumPy — Analyse de données IoT

Préparation et analyse de données de capteurs (température) avant transmission à un système de Machine Learning, à l'aide de la bibliothèque **NumPy**.

##  Contexte

Une entreprise dispose de plusieurs capteurs installés dans différents bâtiments, mesurant régulièrement la température. Avant d'être transmises à un futur système de Machine Learning capable de détecter des situations anormales, ces données doivent être préparées, explorées et analysées.

##  Structure du projet

```
.
├── atelier_numpy_iot.ipynb   # Notebook principal (toutes les parties)
├── requirements.txt          # Dépendances Python
├── .gitignore
└── README.md
```

##  Contenu de l'atelier

| Partie | Sujet |
|---|---|
| 1 | Listes Python vs tableaux NumPy |
| 2 | Création des données |
| 3 | Exploration des tableaux |
| 4 | Indexation et slicing |
| 5 | Filtrage booléen |
| 6 | Manipulation des dimensions |
| 7 | Concaténation |
| 8 | Calcul scientifique (statistiques, standardisation, normalisation) |
| 9 | Broadcasting |
| 10|  Bonus : Benchmarking de performance (NumPy vs Python pur)

Chaque partie se termine par un tableau récapitulatif des fonctions NumPy utilisées, mis en perspective avec leurs alternatives.

##  Installation

**1. Cloner le dépôt**
```bash
git clone <url-du-depot>
cd atelier_numpy_iot
```

**2. Créer et activer l'environnement virtuel**
```bash
python -m venv venv
```
- Windows : `venv\Scripts\Activate.ps1`
- macOS / Linux : `source venv/bin/activate`

**3. Installer les dépendances**
```bash
pip install -r requirements.txt
```

## Utilisation

Ouvrir `atelier_numpy_iot.ipynb` dans VS Code (extension Jupyter) ou Jupyter Notebook, puis exécuter les cellules dans l'ordre.

##  Technologies

- Python 3
- NumPy
- Jupyter Notebook

##  Auteur

Abdoulaye DIOUF
Projet réalisé dans le cadre d'un atelier de pratique NumPy.