Projet 7 OpenClassrooms **Mon Vieux Grimoire**

![Notation de livres]

<div align="center">
<img src="">
</div>

## Création du Backend

- Création d'un serveur express simple.
- Création d'une **API RESTful**.
- Configuration des models **Book** et **User**.
- Création du **CRUD** ains que configuration du **router**.
- Mise en plase d'un système d'authentification par **Token**(jwt).
- Hachage du mot de passe avec **bcrypt**.
- Mise en place d'une gestion des fichiers utilisateur via **Sharp** et **Multer**.
- Ajout et calcul de la notation des livres.

## Technologies utilisées

- Node Js
- Express
- MongoDB
- Git

## Comment lancer projet ?

Projet testé sur node 19.

Ouvrez un terminal puis `git clone https://github.com/JaouharOUERTANI/P7-Mon-Vieux-Grimoire.git`

## Créez un fichier .env à la racine du projet avec en parametres

- **PORT**=4000
- **MONGO_USER**=Adresse de votre base de donnée mongoDB
- **MONGO_PASSWORD**= Mot de passe de votre base de donnée mongoDB
- **JWT_SECRET**= Votre clé secrète

## Lancer le frontend

Ouvrez un terminal puis `cd frontend`, faites la commande `npm install` pour installer les dépendances puis `npm start` pour lancer le client.

## Lancer le backend

Ouvrez un terminal puis `cd backend`, faites la commande `npm install` pour installer les dépendances puis `nodemon` pour lancer le server.