# Projet VilleFutur_DataWarehouse

## Description
Le projet VilleFutur_DataWarehouse est axé sur la collecte, la modélisation et l'analyse de données météorologiques dans le but d'anticiper les besoins en infrastructure et services publics pour la ville de VilleFutur. L'objectif principal est de créer un entrepôt de données solide et évolutif qui centralisera toutes les informations météorologiques de la ville. Cet entrepôt permettra de prendre des décisions éclairées pour l'avenir de VilleFutur en surveillant et en analysant ces données.

## Tâches Réalisées
- **Collecte des Données :** Extraction des données pertinentes telles que la température, l'humidité, la vitesse du vent, les précipitations, etc., pour les années spécifiées.
- **Intégration des Données :** Transformation des données en utilisant un schéma en étoile et chargement des données dans un entrepôt de données dans Azure.
- **Modélisation des Données :** Création de tables de dimension, peuplement des tables de dimension, et création de la table de faits pour stocker les données météorologiques.
- **Création d'un Entrepôt de Données :** Définition des attributs pour les tables, implémentation du schéma en étoile, gestion de la sécurité et conformité GDPR.
- **Surveillance de l'Activité de l'Entrepôt :** Utilisation d'Azure Monitor pour surveiller l'activité et les performances de l'entrepôt.
- **Suivi des Modifications Historiques :** Mise en place du Slowly Changing Dimension (SCD) pour suivre les changements historiques dans les données.

## Outils Utilisés
- Azure Blob Storage : Stockage des données météorologiques.
- Azure Data Factory : Intégration et transformation des données.
- Azure Synapse Analytics : Entreposage et analyse des données.
- Azure Monitor : Surveillance de l'activité de l'entrepôt.
