# Cours de Prompt Engineering avec l'API Gemini

Ce dépôt contient mes exercices et mes scripts de test pour suivre le cours de prompt engineering, adaptés pour utiliser l'API gratuite de Google Gemini via la couche de compatibilité OpenAI.

## Prérequis

- Python 3.10 ou supérieur
- Une clé API Google AI Studio

## Installation et configuration

1. Cloner le dépôt et créer un environnement virtuel :
   ```bash
   python -m venv venv
   source venv/bin/activate  # Sur Windows : venv\Scripts\Activate.ps1

2. Installer les dépendances :


pip install openai python-dotenv


3. Créer un fichier .env.local à la racine du projet et y ajouter ta clé API :

### Extrait de code

GEMINI_API_KEY=ton_clé_api_ici

### Structure du projet

Guidelines/ : Contient les scripts du premier module (principes fondamentaux et fonction d'envoi de prompt).

### Les futurs dossiers de parties suivront la même structure.

### Exécution
Se placer dans le dossier de la partie souhaitée et lancer le script :

### Bash

python main.py