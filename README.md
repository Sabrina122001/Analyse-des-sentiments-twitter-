# Analyse-des-sentiments-twitter-

📊 Analyse des Sentiments sur Twitter  

📌 Description  
Ce projet vise à analyser les sentiments des tweets en utilisant le traitement du langage naturel (NLP). Il s'appuie sur le jeu de données Sentiment140 disponible sur Kaggle :  
🔗 (https://www.kaggle.com/datasets/kazanova/sentiment140)  

Le projet inclut :  
✅ Chargement et nettoyage des données**  
✅ Analyse exploratoire** (distribution des sentiments, fréquence des mots, visualisation des données)  
✅ Pré-traitement des textes** (tokenization, suppression des stopwords, vectorisation)  
✅ Modélisation(classification des sentiments"régression logistique")  
✅ Évaluation des modèles(précision, rappel, matrice de confusion)  

 🛠 Installation  

1️⃣ Cloner le dépôt GitHub :  
```bash
git clone https://github.com/votre-utilisateur/nom-du-repo.git
cd nom-du-repo
```

2️⃣ Installer les dépendances :  
```bash
pip install -r requirements.txt
```

3️⃣ Télécharger la base de données :  
- Récupérer `training.1600000.processed.noemoticon.csv` sur [Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140).  
- Placer le fichier dans le dossier `data/`.  


```

 🔍 Analyse exploratoire  
Avant d'entraîner un modèle, une exploration des données est réalisée :  
📌 Distribution des sentiments** : Proportion de tweets positifs et négatifs  
📌 Nuage de mots** : Visualisation des mots les plus fréquents  
📌 Longueur des tweets** : Analyse des caractéristiques textuelles  
📌 Fréquence des hashtags et mentions  

🚀 Utilisation  

Exécuter le notebook dans Jupyter :  
```bash
jupyter notebook projet_off1.ipynb
```

📊 Résultats  
Le modèle de classification évalue si un tweet est positif ou négatif en fonction du texte.  

📜 Licence  
📢 Ce projet utilise la base de données Sentiment140 sous licence libre, mais vérifiez les conditions d'utilisation sur Kaggle.  
 
