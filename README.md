# Prédiction de la qualité de l'eau

Ce projet vise à créer un outil de classification, qui permet de prédire la qualité d'un point d'eau en fonction de différentes données relevées sur place.

Cahier des charges

    Exploiter l'historique des enregistrements de 2018, 2019 et 2020.
    Appliquer une étude EDA.
    Sélectionner les features importants (pas plus de 10 features).
    Concaténer les trois bases de données (de 2018, 2019 et 2020).
    Reformuler la cible (target ou label).
    Préparer les données pour la conception du modèle IA.
    Tester plusieurs modèles de classification et sélectionner le modèle le plus performant.

Procédure

    Exploiter les données historiques de qualité de l'eau pour 2018, 2019 et 2020.
    Effectuez une étude EDA pour identifier les features les plus importantes.
    Sélectionnez les 10 features les plus importantes.
    Concaténez les trois bases de données en une seule base de données.
    Reformulez la cible en trois catégories : bad, poor, moderate et good
    Préparez les données pour la conception du modèle IA.
    Testez plusieurs modèles de classification de la library sklearn:
        RandomForestClassifier
        DecisionTreeClassifier
        KNeighborsClassifier
        Support Vector Machine
        GradientBoostingClassifier
    Sélectionnez le modèle le plus performant en fonction de différentes métriques.

Résultats

Ce projet a permis de développer un outil de prédiction de la qualité de l'eau efficace. Le modèle de Random Forest a été choisi car il a obtenu les meilleures performances en termes de précision, de sensibilité et de spécificité (et en temps de calculs).
