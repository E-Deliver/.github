# E-Deliver

E-Deliver est une application web conçue pour gérer le processus de livraison des commandes jusqu'à la confirmation de leur réception par le client final. Elle permet à l'administrateur de gérer les commandes reçues, d'attribuer chaque livraison à un livreur spécifique, et de s'assurer que ce dernier confirme la réception de la commande par le client. De plus, le client a la possibilité de consulter les informations relatives à l'état de livraison de ses commandes.

## Membres du groupe

Ce projet a été réalisé collaborativement par :

- ADBIB Ilham
- EL MADANI Khadija
- LAMRINI Imane

## Technologies utilisées

Cette application a été réalisée en se basant sur les technologies suivantes :

- **Spring Boot** (pour la gestion du côté serveur du projet)
- **Spring Security** (pour la sécurisation de l'accès à l'application en se basant sur les jetons (tokens) de JWT (JSON Web Token))
- **Angular** (pour la gestion du côté client du projet)
- **MySQL** (pour la gestion des bases de données relationnelles)
- **JUnit5** et **Mockito** (pour la réalisation des tests unitaires dans le code backend)
- **Selenium** et **TestNg** (pour la réalisation des tests automatisés)
- **Docker** et **Docker Compose** (pour la conteneurisation de l'application)
- **GitHub Actions** (pour la gestion de flux de déploiement dans les deux codes de frontend et backend)

## Fonctionnalités principales

### Espace administrateur

- Se connecter à l'application
- Consulter le tableau de bord, y compris les statistiques clés
- Vérifier la liste de toutes les commandes de divers statuts (En attente, En cours, Livrée)
- Affecter les commandes ayant le statut "En attente" aux livreurs concernés
- Consulter la liste complète de tous les livreurs et clients ayant accès à l'application
- Voir les notifications représentant l'état de livraison des diverses commandes
- Modifier les informations du profil

### Espace livreur

- Se connecter à l'application
- Consulter le tableau de bord, y compris les statistiques clés
- Consulter la liste des commandes qui lui ont été affectées, tout en confirmant la livraison des commandes dont la procédure a eu lieu
- Voir les notifications représentant l'état de livraison des diverses commandes
- Modifier les informations du profil

### Espace client

- Se connecter à l'application
- Consulter le tableau de bord, y compris les statistiques clés
- Consulter la liste des commandes qui lui sont relatives, qui inclut l'état de livraison de chaque commande
- Voir les notifications représentant l'état de livraison des diverses commandes
- Modifier les informations du profil
