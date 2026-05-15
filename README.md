# Détection de Ransomwares par Apprentissage Automatique

## Description
Ce projet est une solution complète de détection de ransomwares basée sur l'apprentissage automatique.  
Il analyse le comportement des logiciels via leurs appels API système afin de distinguer les logiciels légitimes (goodwares) des ransomwares, avant qu'ils ne causent des dommages.

## Features
- Ingénierie de caractéristiques avancée (score de suspicion, ratios d'activité)
- Augmentation de données synthétiques (CTGAN, TVAE, TDAE)
- Comparaison de plusieurs modèles de classification (XGBoost, Random Forest, SVM, KNN)
- Évaluation complète avec Accuracy, F1-Score et AUC-ROC

## Technologies Used
- Python
- XGBoost
- SDV (CTGAN, TVAE)
- TensorFlow 
- Pandas & NumPy
- Matplotlib 

## Installation
- Clone the repository:
   ```bash
   git clone https://github.com/Khadijarrabta-Coder/ransomware-detection-ml.git
   ```

## Results

| Modèle | Accuracy | F1-Score | AUC-ROC |
|---|---|---|---|
| **XGBoost + CTGAN** | **91.53%** | **91.46%** | **0.9711** |
| Random Forest + TVAE | 89.83% | 89.80% | 0.9661 |
| SVM + CTGAN | 89.83% | 89.80% | 0.9602 |
| KNN + TVAE | 88.98% | 88.98% | 0.9498 |

