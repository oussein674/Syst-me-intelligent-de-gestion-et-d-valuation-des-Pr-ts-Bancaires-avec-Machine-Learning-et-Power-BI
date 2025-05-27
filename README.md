# 📊 Prédiction de l'Éligibilité aux Prêts Bancaires avec Machine Learning et Power BI

Ce projet consiste à développer un modèle de Machine Learning pour prédire l'éligibilité des clients à un prêt bancaire, et à visualiser les résultats de manière dynamique via un tableau de bord Power BI.

---

## 📌 Objectif du projet

Prédire si un client est éligible à un prêt bancaire à partir de ses caractéristiques socio-financières, et permettre une visualisation interactive et compréhensible pour les analystes grâce à Power BI.

---

## 🧠 Approche de Machine Learning

- **Modèle utilisé** : XGBoost Classifier
- **Étapes suivies** :
  - Nettoyage et préparation des données
  - Encodage des variables catégorielles (Label Encoding)
  - Séparation en jeu d'entraînement/test
  - Entraînement du modèle
  - Évaluation (accuracy, matrice de confusion, etc.)
  - Sauvegarde du modèle `.pkl`

---

## 🧪 Données utilisées

Les données contiennent les informations suivantes :
- Âge
- Situation Familiale
- Nombre d’enfants
- Profession
- Revenu mensuel
- Montant du prêt demandé
- Durée de remboursement
- Historique de crédit
- Endettement (%)
- Statut professionnel
- Score crédit
- Éligibilité au prêt (variable cible)

---

 ## Tableau de bord Power BI
 
Le tableau de bord comprend :

Nombre total de clients

Nombre de clients éligibles / non éligibles

Taux d’éligibilité

Visualisation des variables clés : revenu mensuel, montant prêt demandé, durée remboursement, score crédit, historique crédit

Filtres dynamiques par statut professionnel, profession, historique crédit…

✅ Possibilité de filtrer par client (ajout d’un identifiant ou nom fictif)

---

## 📦 Structure du projet

```plaintext
├── data/
│   ├── donnees_prets_bancaires_FR.xlsx
│   ├── nouvelles_donnees_a_predire.xlsx
├── model/
│   └── xgb_model.pkl
├── notebooks/
│   └── modele_prediction_prets.ipynb
├── dashboard/
│   └── power_bi_eligibilite.pbix
├── README.md
