# Patch-Management
## Description
Application de gestion distante des serveurs (Windows/Linux) avec surveillance, ex�cution de commandes et interface web.

## Technologies utilis�es
- **Backend** : Python (Flask)
- **Frontend** : React
- **Base de donn�es** : PostgreSQL
- **Conteneurisation** : Docker

## D�marrage local
1. Clonez le d�p�t
2. Assurez-vous que Docker et Docker Compose sont install�s
3. Ex�cutez `docker-compose up --build`
4. Acc�dez � l'application via http://localhost

## Structure du projet
- `/backend` : API Flask
- `/frontend` : Application React
- `/db` : Scripts et migrations de base de donn�es

## Configuration
Modifiez le fichier `.env` pour configurer les variables d'environnement.
