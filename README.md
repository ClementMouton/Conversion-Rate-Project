# Description d'un défi de machine learning 🚴🚴

Dans les défis de machine learning, l'ensemble de données est toujours séparé en fichiers :
data_train.csv contient des données étiquetées , ce qui signifie qu'il y a à la fois X (variables explicatives) et Y (la cible à prédire). Vous utiliserez ce fichier pour entraîner votre modèle comme d'habitude : effectuer le partage train/test, les prétraitements, évaluer les performances, essayer différents modèles, affiner les hyperparamètres etc...
data_test.csv contient de "nouveaux" exemples qui n'ont pas été utilisés pour entraîner le modèle, dans le même format que dans data_train.csv mais il n'est pas étiqueté , ce qui signifie que la cible Y a été supprimée du fichier. Une fois que vous aurez formé un modèle, vous utiliserez data_test.csv pour faire des prédictions que vous enverrez à l'équipe organisatrice. Ils pourront alors évaluer les performances de votre modèle de manière indépendante, en évitant la triche 🤸
Les prédictions de votre modèle seront comparées aux véritables étiquettes et publieront un classement où sont stockés les scores de toutes les équipes du monde.
Tous les participants sont informés de la métrique qui sera utilisée pour évaluer les scores. Vous devez vous assurer que vous utilisez la même métrique pour évaluer vos performances d'entraînement/test !
Description de l'entreprise 📇
www.datascienceweekly.org est une célèbre newsletter organisée par des data scientists indépendants. Tout le monde peut enregistrer son adresse e-mail sur ce site pour recevoir chaque semaine des informations sur la science des données et ses applications !

# Projet 🚧

Les data scientists qui ont créé la newsletter aimeraient mieux comprendre le comportement des utilisateurs visitant leur site internet. Ils aimeraient savoir s'il est possible de construire un modèle qui prédit si un utilisateur donné s'abonnera à la newsletter, en utilisant seulement quelques informations sur l'utilisateur. Ils souhaitent analyser les paramètres du modèle pour mettre en évidence des fonctionnalités importantes pour expliquer le comportement des utilisateurs, et peut-être découvrir un nouveau levier d'action pour améliorer le taux de conversion de la newsletter.

Ils ont conçu un concours visant à construire un modèle permettant de prédire les conversions (c'est-à-dire le moment où un utilisateur s'abonnera à la newsletter). Pour ce faire, ils ont ouvert un ensemble de données contenant des données sur le trafic sur leur site Web. Pour évaluer le classement des différentes équipes en compétition, ils ont décidé d'utiliser le f1-score .

# Objectifs 🎯

Le projet peut être découpé en quatre étapes :

Partie 1 : réaliser une EDA et les prétraitements et entraîner un modèle de base avec le fichier data_train.csv
Partie 2 : améliorez le score f1 de votre modèle sur votre ensemble de tests (vous pouvez essayer l'ingénierie de fonctionnalités, la sélection de fonctionnalités, la régularisation, les modèles non linéaires, l'optimisation des hyperparamètres par recherche de grille, etc...)
Partie 3 : Une fois que vous êtes satisfait du score de votre modèle, vous pouvez l'utiliser pour faire des prédictions avec le fichier data_test.csv . Vous devrez transférer les prédictions dans un fichier .csv qui sera envoyé à Kaggle (en fait, à votre professeur/TA 🤓). Vous pouvez faire autant de soumissions que vous le souhaitez, n'hésitez pas à essayer différents modèles !
Partie 4 : Prenez le temps d'analyser les paramètres de votre meilleur modèle. Existe-t-il des leviers d'action qui permettraient d'améliorer le taux de conversion de la newsletter ? Quelles recommandations feriez-vous à l’équipe ?# Conversion-Rate-Project
