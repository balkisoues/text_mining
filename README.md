# Text-Mining-Labs-


Lab 1 – Text Pre-processing & Feature Extraction
Objectif : Découvrir les principales étapes du prétraitement de texte et les différentes représentations vectorielles utilisées en NLP.
Étapes principales : 
Part I – Text Pre-processing
Conversion en minuscules
Segmentation en phrases et en mots
Suppression de la ponctuation
Filtrage des stopwords
Comparaison entre Stemming et Lemmatization
Part II – Text Representations
Extraction des caractéristiques textuelles à l’aide de :
Bag of Words (BoW)
TF-IDF
Word2Vec
Résultat : Ce laboratoire permet de comprendre comment transformer un texte brut en représentation numérique exploitable par les algorithmes de Machine Learning.


Lab 2 – Text Classification
Objectif : Classer des tweets d’avis sur les compagnies aériennes en deux catégories : complaining et non-complaining.
Étapes principales : 
Chargement et nettoyage du jeu de données
Extraction des caractéristiques via TF-IDF
Entraînement d’un classifieur Naive Bayes
Évaluation des performances sur le jeu de test
Résultat : Le modèle obtient une bonne précision sur la détection des tweets de réclamation.
Ce lab illustre le processus complet de Text Classification supervisée.


Lab 3 – Sentiment Analysis
Objectif : Prédire le sentiment d’un avis de cours (positif ou négatif) à partir du texte.
Étapes principales : 
Prétraitement et nettoyage des données textuelles
Extraction des caractéristiques avec le modèle Bag of Words
Entraînement d’un modèle de Régression Logistique
Évaluation de la performance du modèle
Résultat : Ce TP met en œuvre un pipeline de sentiment analysis complet et démontre l’efficacité de la régression logistique sur des données textuelles.


Lab 4 – Text Summarization
Objectif : Comparer différentes méthodes de résumé automatique de texte.
Étapes principales :
Prétraitement du texte de référence
Application de trois approches de résumé :
TF-IDF Summarization
TextRank (approche basée sur les graphes)
LSA (Latent Semantic Analysis)
Évaluation de la qualité des résumés via la BLEU Score
(Texte de référence : “Travelling teaches you about yourself. It makes you more tolerant.”)
Résultat :
Chaque méthode produit un résumé extractif différent.
TF-IDF : sélectionne les phrases contenant les termes les plus informatifs.
TextRank : privilégie les phrases les plus centrales dans le graphe de similarités.
LSA : identifie les dimensions sémantiques dominantes pour condenser le texte.


Environnement :
Python 3.x
Google Colab


Bibliothèques : 
nltk, sklearn, gensim, numpy, pandas, matplotlib
