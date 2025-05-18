# 📊 ProjetIntégrer – Étude sur l'impact des activités parascolaires sur la performance académique

Ce projet analyse les relations entre l'engagement étudiant dans des activités parascolaires et leur performance académique, à partir de données réelles collectées via un questionnaire. Il comprend un tableau de bord interactif et une série de visualisations construites avec Streamlit.

---

## 🎯 Objectif

Explorer des corrélations potentielles entre :
- Le genre, l'âge, le niveau d'études
- Le temps hebdomadaire consacré aux activités
- Les performances académiques auto-évaluées
- Les stratégies de gestion du temps
- La perception de soutien institutionnel

---

## 🛠️ Contenu du dépôt

```
ProjetIntegrer/
├── projetintegrer/              # Dossier de données
│   └── projetintegrer.csv       # Données brutes issues de l'enquête
├── Dashboard.py                 # Application Streamlit interactive
├── Pintegrer.ipynb              # Notebook d'exploration initiale
├── wordcloud.png                # Nuage de mots des activités préférées
├── README.md                    # Documentation du projet
```

---

## 🚀 Lancer le dashboard

1. Installer les dépendances :

```bash
pip install streamlit pandas matplotlib seaborn wordcloud scipy
```

2. Lancer l'application Streamlit :

```bash
streamlit run Dashboard.py
```

---

## 📈 Fonctionnalités interactives

- Graphiques par genre, âge et niveau d'études
- Tests d’hypothèse (ex. : temps passé vs genre)
- Diagrammes en barres et en violon
- Nuage de mots des activités préférées
- Analyse de la satisfaction, du soutien institutionnel et des relations sociales

---

## 📊 Aperçu des données

Les données ont été collectées anonymement auprès d’étudiants de différents niveaux universitaires. Des champs incluent : âge, genre, stratégie de gestion du temps, nombre d’événements suivis, évaluation académique, etc.

---

## 🧪 Analyse statistique

- Tests T pour comparaison hommes/femmes
- Visualisation des moyennes par sous-groupes
- Proportions par genre sur les relations sociales

---

## 👤 Auteur

- **Brahim Mechaouat**  
  [Portfolio](https://brahex123.github.io/ibrahex123.github.io/)  
  [GitHub](https://github.com/brahex123)

---

## 📄 Licence

Projet académique libre d'utilisation à des fins pédagogiques et scientifiques.
