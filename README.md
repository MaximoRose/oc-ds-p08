# Reconnaissance d'images / Calcul distribué (Spark/AWS)

Pour ce projet, nous allons mettre en place une infrastructure Cloud de calcul distribué de facon à évaluer un modèle pré-entraîné de reconnaissance d'image, sur notre jeu de données.

On utilise la version 2 du réseau de neurones MobileNet, auquel on enlèvera la dernière couche de classification, afin d'éventuellement implémenter notre propre modèle de classification, adapté à notre problématique spécifique.

L'architecture du projet repose donc sur les services Cloud AWS IAM, AWS S3 et AWS EMR et structure ainsi :

![architecture du projet](https://maximorose.eu/datascience_gh_ress/architecture_projet_aws.png)

Pour faciliter la lisibilité, j'ai regroupé l'ensemble des actions dans un seul fichier Jupyter : _etude_cloud_et_locale.ipynb_


