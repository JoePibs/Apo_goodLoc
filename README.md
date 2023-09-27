# Bienvenue sur le projet Good Loc

Ce projet est une application qui permet de louer des jeux de société entre particulier de fin d'étude . 


## Exécution de l'application

Pour lancer cette application en local, rendez-vous dans le dossier `config/docker/`.
Copiez le fichier `env-example` sous le nom `.env`.
Définissez les ports de votre machine qui seront utilisés par les conteneurs MySQL et PHPMyAdmin.
Exécutez la commande `docker compose up -d` (ou `docker-compose` si vous l'avez) pour lancer les conteneurs MySQL et PHPMyAdmin.
Cela lancera les conteneurs de la base de données MySQL et de PHPMyAdmin.

## Structure de l'app

### Back

Notre back-end est construit avec Express.js, un framework pour Node.js qui facilite la création d'applications web et d'API. Express.js est très populaire pour sa simplicité et sa flexibilité. Avec Express.js, nous configurons facilement nos routes et nos contrôleurs pour répondre aux demandes HTTP, ce qui correspond au composant contrôleur dans le modèle MVC.

Notre API back s'appuie sur une architecture en couches, organisée de manière logique pour une meilleure évolutivité et facilité de test.

### Front

Utilisation de Nuxt.js 2.

### Scripts

Elle contient un ensemble de script qui a été utilisé pour construire les tables Games, Publishers et mechanics à partir de l'api Board Games Atlas.

### PostMan

Contient un ensemble de script qui a été utilisé pour construire les tables Games, Publishers et mechanics à partir de l'api Board Games Atlas.

### Config

- docs : Contient un fichier markdown qui explique la stratégie CI/CD utilisée pour ce projet. Les pipelines CI/CD sont inactifs.
- docker : Contient les fichiers liés à Docker. Nous avons seulement deux services pour la base de données MySQL et pour PHPMyAdmin.
- postman : Contient une collection Postman en partie obsolète.


# Welcome to the Good Loc Project

This project is an application that allows individuals to rent board games from each other.

## Running the Application

To run this application locally, navigate to the `config/docker/` directory.
Copy the `env-example` file as `.env`.
Set the ports on your machine that will be used by the MySQL and PHPMyAdmin containers.
Execute the command `docker compose up -d` (or `docker-compose` if you have it) to launch the MySQL and PHPMyAdmin containers.
This will start the MySQL database and PHPMyAdmin containers.

## App Structure

### Back-End

Our back-end is built with Express.js, a Node.js framework that simplifies the creation of web applications and APIs. Express.js is highly regarded for its simplicity and flexibility. With Express.js, we easily configure routes and controllers to handle HTTP requests, corresponding to the controller component in the MVC pattern.

Our back-end API follows a layered architecture, logically organized for scalability and ease of testing.

### Front-End

Using Nuxt.js 2.

### Scripts

This section contains a set of scripts used to build the Games, Publishers, and Mechanics tables from the Board Games Atlas API.

### Postman

Contains a set of scripts used to build the Games, Publishers, and Mechanics tables from the Board Games Atlas API.

### Config

- **docs**: Contains a Markdown file that explains the CI/CD strategy used for this project. The CI/CD pipelines are inactive.
- **docker**: Contains files related to Docker. We have only two services, one for the MySQL database and one for PHPMyAdmin.
- **postman**: Contains a partially outdated Postman collection.


Original project : https://github.com/O-clock-Griffon/projet-02-good-lock