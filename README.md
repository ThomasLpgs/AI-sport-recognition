# AI-sport-recognition using Deep Learning
Intelligence Artificielle permettant la reconnaissance d'un sport en fonction du ballon/balle.

Ce projet a été réalisé dans le cadre d'un cours sur le Deep Learning à l'EPSI Montpellier, cours prodigué par M. ALTAZIN Thomas.

Les sports suivants sont disponibles : baseball, basketball, football, footballamericain, golf, handball, pingpong, rugby, tennis, volleyball.

L'IA a été entrainée avec 2 types d'images, des images où l'on voit seulement le ballon/la balle et des images où l'on voit des personnes jouer au sport.
L'IA est donc capable d'identifier un sport même s'il n'y a pas seulement le ballon/la balle sur l'image.

Notre modèle entraîné est également disponible sur un site web : https://ai-test-jco.herokuapp.com/

Le projet associé à ce site web est disponible ici : https://github.com/joconte/ai-sport-api

# Outils utilisés

- FastAI
- Jupyter Notebook
- Python3

# Groupe de travail

- JACQUES Nils
- SEVRAIN Florian
- LASPOUGEAS Thomas
- CONTE Jonathan

# Constitution du dataset

Recherche sur Google Image puis téléchargement des images via l'extension 'Download All Images' : https://chrome.google.com/webstore/detail/download-all-images/ifipmflagepipjokmbdecpmjbibjnakm

Suppression des doublons d'images via le logiciel 'Duplicate Cleaner' : https://www.digitalvolcano.co.uk/duplicatecleaner.html

Suppression des images non pertinentes "à la main".

# Comment effectuer des prédictions avec notre modèle sans l'entrainer à nouveau ?

Prérequis : 
- FastAI
- Jupyter Notebook
- Python3

Etapes :
- Cloner le repository : `git clone https://github.com/ThomasLpgs/AI-sport-recognition.git`
- Positionnez vous dans le projet : `cd AI-sport-recognition/`
- Exécuter un Jupyter Notebook : `jupyter notebook nos_propres_dataset.ipynb`
- Exécuter les cellules suivantes du Jupyter Notebook : 
  - Import des dépendances de FASTAI
  - Chargement de notre modèle
  - Prédiction
