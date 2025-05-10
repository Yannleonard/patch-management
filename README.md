# Patch-Management
# Création by Yann LEONARD "Gtek-it.fr"
## Description
Application de gestion distante des serveurs (Windows/Linux) avec surveillance, exécution de commandes et interface web.

## Technologies utilisées
- **Backend** : Python (Flask)
- **Frontend** : React
- **Base de données** : PostgreSQL
- **Conteneurisation** : Docker

## Démarrage local
1. Clonez le dépôt
2. Assurez-vous que Docker et Docker Compose sont installés
3. Exécutez `docker-compose up --build`
4. Accédez à l'application via http://localhost

## Structure du projet
- `/backend` : API Flask
- `/frontend` : Application React
- `/db` : Scripts et migrations de base de données

## Configuration
Modifiez le fichier `.env` pour configurer les variables d'environnement.
