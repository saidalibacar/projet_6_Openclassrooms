Parcours Data Scientist - Projet 6 : Classifiez automatiquement des biens de consommation.

Source de données :

Contexte:

Nous sommes Data Scientist au sein de l’entreprise "Place de marché”, qui souhaite lancer une marketplace e-commerce. Sur la place de marché, des vendeurs proposent des articles à des acheteurs en postant une photo et une description. Pour l'instant, l'attribution de la catégorie d'un article est effectuée manuellement par les vendeurs, et est donc peu fiable. De plus, le volume des articles est pour l’instant très petit. Pour rendre l’expérience utilisateur des vendeurs (faciliter la mise en ligne de nouveaux articles) et des acheteurs (faciliter la recherche de produits) la plus fluide possible, et dans l'optique d'un passage à l'échelle, il devient nécessaire d'automatiser cette tâche.

Notre mission :

Réaliser une étude de faisabilité d’un moteur de classification pour l'automatisation de l'attribution de la catégorie de l'article, en se basant sur la description et l’image de l’article.

Différentes approches mises en oeuvre pour d’extraire les features texte :

deux approches de type “bag-of-words”, comptage simple de mots et Tf-idf ;
une approche de type word/sentence embedding classique avec Word2Vec ;
une approche de type word/sentence embedding avec BERT ;
une approche de type word/sentence embedding avec USE (Universal Sentence Encoder).

Différentes approches mise en oeuvre pour extraire les features image :

un algorithme de type SIFT ;
un algorithme de type CNN (VGG16) Transfer Learning.
