# Fraud_detection
# Détection de Faux Billets en Euros

Ce projet propose une approche pour détecter les faux billets en euros en se basant sur leurs dimensions.  
Il utilise la régression linéaire pour imputer les valeurs manquantes et la régression logistique pour classifier les billets authentiques et frauduleux.

## 🎯 Objectif du Projet

L'objectif principal est de développer un modèle capable de distinguer les vrais billets des faux en analysant leurs dimensions physiques.  
Cette méthode offre une solution rapide et non invasive pour la détection de la fraude monétaire.

## 📊 Données Utilisées

Les données contiennent des mesures physiques de billets en euros, avec des annotations sur leur authenticité.  
Certaines entrées comportent des valeurs manquantes (`NaN`) traitées dans ce projet.

## 🧠 Méthodologie

1. **Prétraitement des Données**  
   Nettoyage, traitement des valeurs manquantes et normalisation des données.

2. **Imputation des Valeurs Manquantes**  
   Utilisation de la **régression linéaire** pour estimer les dimensions manquantes.

3. **Classification**  
   Application d’un modèle de **régression logistique**, qui s’est avéré le plus performant pour cette tâche.

4. **Évaluation**  
   Mesure des performances avec les métriques suivantes : précision, rappel, F1-score.

## ✅ Résultats

- Le modèle de **régression logistique** a obtenu de bons résultats, montrant une capacité efficace à détecter les faux billets.
- L’imputation par **régression linéaire** a permis d’améliorer la qualité du dataset et la robustesse du modèle.

## ⚙️ Prérequis

- Python 3.x
- Bibliothèques :
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`

## 🚀 Utilisation

1. **Cloner le dépôt**

   ```bash
   git clone https://github.com/Ichraf-MOUELHI/Fraud_detection.git
Installer les dépendances

bash
Copier
Modifier
pip install -r requirements.txt
Lancer le notebook

Ouvrir le fichier IM_Detection_fraud_euros.ipynb avec Jupyter Notebook ou Jupyter Lab pour explorer le projet.

👩‍💻 Auteur
Ce projet a été réalisé par Ichraf MOUELHI.
