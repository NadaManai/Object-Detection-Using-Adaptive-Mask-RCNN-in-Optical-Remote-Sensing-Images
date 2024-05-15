# Projet de Deep Learning : Détection d'objets avec Faster R-CNN

## Description
Ce projet implémente un système de détection d'objets en utilisant l'algorithme Faster R-CNN sur le jeu de données NWPU VHR-10. Le modèle est construit en utilisant PyTorch et torchvision, et entraîné sur le jeu de données NWPU VHR-10 qui contient des images aériennes de haute résolution avec des annotations d'objets dans différentes catégories.

## Prérequis
- Python 3.x
- PyTorch
- torchvision
- Albumentations
- Matplotlib
- OpenCV

## Fonctionnalités Principales :
- Chargement des images et des annotations du jeu de données NWPU VHR-10.
- Définition d'un modèle de détection d'objets basé sur Faster R-CNN.
- Prétraitement des données, y compris le redimensionnement des images et la conversion des annotations.
- Définition de transformations pour la data augmentation.
- Entraînement du modèle en utilisant différentes techniques d'optimisation (SGD, Adam, RMSprop).
- Évaluation des performances du modèle en termes de précision et de rappel pour chaque classe d'objet détectée.
- Visualisation des résultats avec des boîtes englobantes autour des objets détectés.
- Analyse des courbes de précision-rappel pour chaque classe d'objet.
