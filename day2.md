# Machine Learning - Jour 2

@auteur : Mael Gruand

**4 Domaines Principaux :**

- Traitement des données (Data Processing)
- Développement (Development)
- Déploiement (Deployment)
- Inférence (Inference)

## Définitions :

- **Inférence :** Processus de mise en production d'un modèle de machine learning. Cela implique de répondre aux requêtes du serveur web en utilisant le modèle (requête/query) et de fournir une réponse rapide.
- **IOPS (Input/Output Operations Per Second) :** Nombre d'opérations de lecture/écriture qu'un système de stockage peut effectuer par seconde.
- **EFS (Elastic File System) :** Service de stockage de fichiers élastique d'AWS.
- **NPU (Neural Processing Unit) :** Unité de traitement neuronal, spécialisée dans les calculs d'intelligence artificielle.
- **EBS (Elastic Block Storage) :** Service de stockage de blocs élastique d'AWS.

## Entraînement (Training) :

- L'entraînement nécessite l'étiquetage des données (Training Workloads).
- Utilisation d'E/S aléatoires (random I/O random access).
- Click streaming : Flux de données provenant des interactions des utilisateurs avec un site web ou une application, souvent corrélé avec les logs de pare-feu (Firewall).
- **Ingénierie des caractéristiques (Feature engineering) :** Processus de création de nouvelles caractéristiques à partir des données brutes pour améliorer les performances du modèle. AWS propose des ressources pour cela (Blog AWS).
- Utilisation du cloud et de l'IA pour la détection de fraude.
- Données en flux constant : Utilisation d'Amazon Data Firehose pour streamer les données vers Amazon Redshift (RDS Operational).
- Avantage du Web : Paiement à l'utilisation (pay-as-you-go), comme avec S3 (exemple de coût : 1,256 $/mois).
- **S3 (Simple Storage Service) :** Service de stockage d'objets d'AWS. Il n'est pas optimisé pour la récupération rapide de données.
- **Redshift :** Entrepôt de données (data warehouse) plus rapide, souvent utilisé avec Kinesis Data Streams pour le transfert de données en temps réel vers S3.
- **EFS :** Service de stockage de fichiers élastique, permettant à plusieurs serveurs ou systèmes de stockage sur AWS d'accéder aux mêmes données.

## Ingestion de données (Data Digestion) :

- Données semi-structurées : Formats courants tels que CSV ou JSON.
- Référence au document "AWS Data Strategy".
- Bases de données : Relationnelles ou non relationnelles.
- Machine Learning : Utilisation d'une zone de données centralisée, généralement AWS S3 (Bucket Storage).
- Utilisation de l'IA pour l'ingestion de données en temps réel pour la détection de fraud
- Service Apache Kafka (Clusters de machine)
- Amazon --> MSK = Managed Service Kafka

