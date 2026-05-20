# Streamlit Titanic App
lien du streamili: https://app-test-ufrskbqwyow3h64nvldtua.streamlit.app/ 

Application Streamlit pour afficher et visualiser un jeu de données Titanic.

## Fichiers inclus

- `streamlit_app.py` : application Streamlit principale
- `train.csv` : données Titanic au format CSV
- `train.csv.xlsx` : données Titanic encodées dans un fichier Excel (même contenu)

## Installation

1. Créez un environnement Python (recommandé) :
   ```bash
   python -m venv .venv
   .\.venv\Scripts\activate
   ```
2. Installez les dépendances :
   ```bash
   pip install -r requirements.txt
   ```

## Utilisation

Depuis le dossier `Streamlit` :

```bash
streamlit run streamlit_app.py
```

## Notes

- L'application charge le fichier `train.csv.xlsx` si nécessaire.
- Le fichier `train.csv` est également présent pour un chargement direct en CSV.
