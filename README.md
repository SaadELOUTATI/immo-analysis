# 🏢 Immo Analysis

Analyse exploratoire du marché des locaux commerciaux parisiens.

## 📌 Objectif

Explorer les dynamiques de prix et de disponibilité des locaux commerciaux à Paris en croisant :
- Prix au m² par arrondissement
- Flux piétons
- Disponibilité des locaux
- Type de commerce

## 📊 Contenu du notebook

| Section | Description |
|---|---|
| Génération du dataset | 200 locaux commerciaux simulés avec des prix réalistes par arrondissement |
| Exploration & nettoyage | Statistiques descriptives, valeurs manquantes, répartition par statut |
| Analyse par arrondissement | Prix moyen au m², taux de disponibilité |
| Flux piétons vs Prix | Corrélation et visualisation |
| Scoring des emplacements | Top 5 des meilleurs locaux disponibles (rapport flux/prix) |

## 🛠️ Stack technique

- `pandas` — manipulation des données
- `numpy` — génération et calculs
- `matplotlib` — visualisations


## 📁 Structure

```
immo-analysis/
│
├── analyse_immo_commercial_paris.ipynb   # Notebook principal
├── prix_par_arrondissement.png           # Graphique exporté
└── README.md
```


## 👤 Auteur

**Saad El Ouatati** — Étudiant ingénieur Data & Applications @ ESIEE Paris
