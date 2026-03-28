# 🎓 Analyse des systèmes éducatifs mondiaux — Opportunités EdTech

![Python](https://img.shields.io/badge/Python-3.8-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualisation-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 🎯 Objectif

Analyser les données éducatives mondiales de la **Banque Mondiale (EdStats)** pour identifier les pays à fort potentiel de développement pour une startup EdTech souhaitant s'internationaliser.

Contexte : une startup d'enseignement en ligne cherche à prioriser ses marchés d'expansion — le projet fournit une analyse data-driven pour orienter la décision stratégique.

---

## 📊 Résultats

| Indicateur | Valeur |
|-----------|--------|
| Dataset | Banque Mondiale — EdStats |
| Pays analysés | 200+ |
| Indicateurs retenus | Taux scolarisation · Accès internet · PIB · Population |
| Méthode de scoring | Multi-critères pondéré |
| Livrable | Classement des pays à fort potentiel EdTech |

---

## 🏗️ Architecture du pipeline

```
Banque Mondiale — EdStats
(indicateurs éducatifs mondiaux)
        │
        ▼
  Nettoyage & traitement
  des valeurs manquantes
  (données lacunaires par pays/année)
        │
        ▼
  Sélection des indicateurs clés
  ├── Taux de scolarisation
  ├── Accès à internet
  ├── PIB par habitant
  └── Population cible (15-35 ans)
        │
        ▼
  Scoring multi-critères
  (pondération par pertinence métier)
        │
        ▼
  Segmentation & visualisation
  des opportunités par région
        │
        ▼
  Recommandations stratégiques
  (TOP 10 pays prioritaires)
```

---

## ⚙️ Stack technique

| Composant | Technologie |
|-----------|------------|
| Traitement données | Pandas · NumPy |
| Visualisation | Matplotlib · Seaborn |
| Analyse statistique | SciPy |
| Cartographie | (visualisation géographique) |
| Données | Banque Mondiale Open Data — EdStats |

---

## 🔑 Choix techniques clés

**Approche scoring multi-critères**
Plutôt qu'un modèle ML complexe, le projet utilise un scoring multi-critères transparent et explicable — directement interprétable par les décideurs non-techniques de la startup.

**Sélection rigoureuse des indicateurs**
Tous les indicateurs retenus sont justifiés par leur pertinence métier : un pays avec un fort taux de scolarisation mais sans accès internet n'est pas un bon candidat pour une plateforme en ligne.

**Vision stratégique orientée business**
Ce projet dépasse l'analyse technique — il produit une **recommandation d'expansion** directement actionnable par l'équipe dirigeante.

---

## 🗂️ Structure du projet

```
OC_DS_P2_Systemes_educatifs/
│
├── notebooks/
│   └── P2_EDA_EdStats.ipynb          # Exploration + nettoyage
│   └── P2_Scoring_Pays.ipynb         # Scoring + recommandations
│
└── README.md
```

---

## 📚 Formation

Projet réalisé dans le cadre de la formation **Data Scientist** — [OpenClassrooms](https://openclassrooms.com)
Accréditation universitaire **WSCUC** (Western Association of Schools and Colleges — USA) · Niveau Master / Bac+5

---

## 👤 Auteur

**Stéphane Barré**
Data Scientist | PySpark · AWS · ML · NLP | Double profil Ingénieur · Data Scientist

[![LinkedIn](https://img.shields.io/badge/LinkedIn-stephane--barre--data-blue?logo=linkedin)](https://www.linkedin.com/in/stephane-barre-data)
[![GitHub](https://img.shields.io/badge/GitHub-stephanebarre13--boop-black?logo=github)](https://github.com/stephanebarre13-boop)
