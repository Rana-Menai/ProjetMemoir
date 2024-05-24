# **ProjetMemoir**

## **Détection de Fraude par Carte de Crédit**

Ce dépôt contient un projet de détection de fraude par carte de crédit (ModelsML.ipynb) utilisant divers modèles de classification de machine learning. L'objectif de ce projet est de comparer les performances de différents classificateurs dans l'identification des transactions frauduleuses.

### **Jeu de Données**

Le jeu de données utilisé pour ce projet est disponible dans un fichier d'archive compressé archive.zip. Le jeu de données contient des transactions effectuées par des cartes de crédit en septembre 2013 par des titulaires de carte européens. Ce jeu de données présente des transactions survenues en deux jours, avec 492 fraudes sur 284 807 transactions. Le jeu de données est très déséquilibré, avec la classe positive (fraudes) représentant 0,172 % de toutes les transactions.

### **Modèles Utilisés**

- Arbre de Décision
- K-Nearest Neighbors (KNN)
- Régression Logistique
- Support Vector Machine (SVM)
- Forêt Aléatoire

### **Métriques d'Évaluation**

Les modèles sont évalués selon les métriques suivantes :
- Précision (Accuracy)
- Score F1
- Matrice de Confusion
