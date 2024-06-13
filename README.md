# 🚀 Application de Gestion des Valeurs

Bienvenue dans notre application de gestion des valeurs! Cette application est conçue pour stocker et afficher des valeurs, en utilisant une stack technologique moderne comprenant React, Node.js, PostgreSQL, Nginx et Docker.

## 🛠️ Technologies Utilisées

- **React** - Pour l'interface utilisateur.
- **Node.js** - Pour le backend.
- **PostgreSQL** - Pour la base de données.
- **Nginx** - Comme serveur web.
- **Docker** - Pour la containerisation.

## 🚀 Fonctionnalités

- Stockage sécurisé des valeurs.
- Affichage en temps réel des valeurs stockées.
- Interface utilisateur intuitive et réactive.

## 📦 Installation

### Prérequis

Assurez-vous d'avoir installé les éléments suivants sur votre machine :

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Étapes d'installation

1. Clonez ce dépôt :

   ```bash
   git clone https://github.com/ayoubm11/Application-de-Gestion-des-Valeurs.git
   cd client
   docker build -f dockerfile.dev -t mayoub12/multi_client .
   docker run -d -p 3003:4000 mayoub12/multi_client
   
   cd server
   docker build -f dockerfile.dev -t mayoub12/multi_server .
   docker run -d -p 3004:5000 mayoub12/multi_server


   docker-compose --build


