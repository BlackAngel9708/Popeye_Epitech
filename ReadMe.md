# Popeye - Projet de Tech 1 (Epitech)  :whale:

## Description
Popeye est un projet réalisé dans le cadre du cursus de Tech 1 à Epitech. L'objectif principal est de découvrir et de se familiariser avec Docker, en utilisant les Dockerfiles et Docker Compose pour créer et gérer des conteneurs.

## Prérequis
Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :
- Docker
- Docker Compose

## Structure du Projet
Le projet est organisé de la manière suivante :
- `Popeye_Epitech/` : Fichier principal du projet.
- `docker/` : Contient les Dockerfiles pour construire les images Docker.
    - `worker/` : Dockerfile pour le composant Worker.
    - `result/` : Dockerfile pour le composant Result.
    - `poll/` : Dockerfile pour le composant Poll.
- `docker-compose.yml` : Fichier de configuration Docker Compose à la racine pour orchestrer les conteneurs.


## Instructions d'Installation

1. Clonez le dépôt :
   ```bash
   git clone git@github.com:JimmyRamsamynaick/Popeye_Epitech.git
   cd Popeye_Epitech

## Utilisation
1. Construisez les images Docker :
   ```bash
   docker compose build
   
2. Lancez les conteneurs :
    ```bash
   docker compose up -d

### Comment savoir si cela fonctionne bien?
Une fois les conteneurs démarrés, vous pouvez accéder aux applications aux adresses suivantes : http://localhost:5000. et : http://localhost:5001.

#### Auteur
- [Jimmy](https://github.com/JimmyRamsamynaick)