````markdown
<p align="center">
  <img src="images/banner.png" alt="Analyse de Données Pokémon" width="600"/>
</p>

# Analyse de Données Pokémon

Ce projet a été réalisé dans le cadre du cours **Analyse et exploration de données** par [Akemi-ito](https://github.com/Akemi-ito) et [Wawanke](https://github.com/Wawanke).

L’objectif est d’explorer et analyser un dataset Pokémon pour répondre à la problématique suivante :

> **Y a-t-il une différence de statistiques notable entre les Pokémon qui ont une évolution et ceux qui n'en ont pas ?**

## 📁 Structure du projet

Tout le projet est contenu dans un seul notebook Jupyter :

- 📓 `analyse_pokemon.ipynb` : code, visualisations, tests statistiques, et conclusions.

## 🧠 Démarche

Nous avons :

- Nettoyé et enrichi les données avec des colonnes personnalisées
- Réalisé une analyse descriptive
- Construit des visualisations avec `seaborn` et `matplotlib`
- Mené des tests statistiques (corrélations, moyennes, etc.)
- Interprété les résultats pour répondre à la problématique

## 📊 Dataset

Le jeu de données original provient de Kaggle :  
👉 https://www.kaggle.com/datasets/mrdew25/pokemon-database/data

Il a été **modifié** avec l’ajout de données personnalisées (comme les chaînes d’évolution ou des regroupements par génération).

## ▶️ Exécution

1. Clone le repo :
   ```bash
   git clone https://github.com/Akemi-ito/Analyse-de-donnee-Pokemon.git
   cd Analyse-de-donnee-Pokemon
````

2. Installe les dépendances :

   ```bash
   pip install -r requirements.txt
   ```

3. Lance le notebook :

   ```bash
   jupyter notebook analyse_pokemon.ipynb
   ```

## ✅ Requirements

Voici le contenu du fichier `requirements.txt` :

```
pandas
numpy
matplotlib
seaborn
scipy
jupyter
```

## 🧑‍🏫 Réalisé par

* [Akemi-ito](https://github.com/Akemi-ito)
* [Wawanke](https://github.com/Wawanke)

---

*Projet pédagogique réalisé dans le cadre de la 3e année Ynov – Data & IA.*

```
