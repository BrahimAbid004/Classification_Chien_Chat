# Projet de Classification Chiens vs Chats

## Description
Ce projet s'inscrit dans le domaine de la Vision par Ordinateur et du Machine Learning. L'objectif est de concevoir et implémenter un système capable de distinguer automatiquement des images de chiens et de chats en utilisant des méthodes classiques de traitement d'image.

## Approche Méthodologique
Notre approche repose sur trois étapes fondamentales :
1. **Préparation des Données** - Chargement et prétraitement des images
2. **Extraction de Caractéristiques** - Utilisation du descripteur HOG (Histogram of Oriented Gradients)
3. **Classification et Modélisation** - Application de plusieurs algorithmes de Machine Learning

## Technologies Utilisées
- **Python** avec les bibliothèques suivantes :
  - OpenCV (cv2) pour le traitement d'images
  - scikit-image pour l'extraction de caractéristiques HOG
  - scikit-learn pour les modèles de classification
  - NumPy et Pandas pour la manipulation des données
  - Matplotlib pour la visualisation

## Algorithmes de Classification Testés
- Support Vector Machine (SVM)
- Random Forest
- K-Nearest Neighbors (KNN)
- Decision Tree
- Logistic Regression

## Résultats
Le classement des modèles par performance (accuracy) :
1. **SVM** : 67.74%
2. **Random Forest** : 67.56%
3. **Logistic Regression** : 67.56%
4. **Decision Tree** : 55.79%
5. **KNN** : 53.30%

## Structure des Données
- Dataset équilibré avec environ 1400 images par classe
- Images redimensionnées à 128x128 pixels
- Conversion en niveaux de gris
- Extraction de 8100 caractéristiques HOG par image

## Conclusion
Le projet démontre qu'il est possible d'atteindre une bonne précision (67.74%) sans recourir aux réseaux de neurones profonds, en utilisant des techniques d'extraction de caractéristiques manuelles combinées à des classifieurs traditionnels.
