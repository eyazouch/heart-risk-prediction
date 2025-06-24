# 💓 Détection du Risque de Crise Cardiaque

> Mini-projet de TP - Apprentissage Automatique  
> Auteur : Eya Zouch

## 🧠 Objectif du projet

Ce projet vise à développer un modèle prédictif de machine learning pour détecter précocement les risques de crise cardiaque à partir de caractéristiques médicales. Une détection précoce permettrait des interventions médicales plus rapides, pouvant sauver de nombreuses vies.

---

## 📁 Structure du projet

- `cardio_predict.py` : Script principal contenant l'importation des données, la préparation, l'entraînement des modèles, l'évaluation, et une interface interactive.
- `heart.csv` : Fichier de données utilisé .
- `README.md` : Ce fichier de documentation.

---

## 📊 Jeu de données utilisé

Le fichier `heart.csv` contient les attributs suivants :

| Attribut        | Description |
|----------------|-------------|
| `age`          | Âge du patient |
| `sex`          | Sexe (1 = homme, 0 = femme) |
| `cp`           | Type de douleur thoracique (0–3) |
| `trestbps`     | Pression artérielle au repos (mm Hg) |
| `chol`         | Taux de cholestérol sérique (mg/dl) |
| `fbs`          | Glycémie à jeun > 120 mg/dl (1 = oui, 0 = non) |
| `restecg`      | Résultat ECG au repos |
| `thalach`      | Fréquence cardiaque maximale atteinte |
| `exang`        | Angine induite par l’exercice (1 = oui, 0 = non) |
| `oldpeak`      | Dépression ST induite |
| `slope`        | Pente du segment ST |
| `ca`           | Nombre de gros vaisseaux colorés |
| `thal`         | Résultat de thalassémie |
| `target`       | 0 = faible risque, 1 = haut risque |

---

## 🔍 Méthodologie

1. **Nettoyage et normalisation des données**
2. **Entraînement de plusieurs modèles** :
   - Régression logistique
   - K-Nearest Neighbors
   - SVM
   - Arbre de décision
   - Random Forest
   - Gradient Boosting
3. **Évaluation des performances** (accuracy, matrice de confusion, courbes ROC)
4. **Interface interactive** permettant de tester manuellement un patient via saisie de ses caractéristiques

---

## 🛠️ Technologies utilisées

- Python 3
- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn`
- Interface interactive via `input()` dans le terminal

---

## ▶️ Exécution

Assurez-vous d’avoir Python 3 et les dépendances installées, puis lancez :

```bash
python cardio_predict.py
```

Suivez ensuite les instructions pour évaluer manuellement le risque d’un patient.

---

## 📌 Auteurs

- **Eya Zouch** — [eya.zouch](mailto:eya.zouch@example.com)
