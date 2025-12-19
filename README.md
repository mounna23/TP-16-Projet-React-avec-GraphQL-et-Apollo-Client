# TP 16 : Projet React avec GraphQL et Apollo Client
## Objectif
L'objectif de cette activité est de développer une application web en React permettant de consommer une API GraphQL à l'aide d'Apollo Client. Cette application devra offrir les fonctionnalités suivantes:

- Gestion des comptes bancaires : création, visualisation et récupération des détails des comptes.
- Gestion des transactions financières associées aux comptes : ajout de transactions (dépôts et retraits) et affichage de l'historique des transactions.
- Interfaçage avec une API GraphQL : exécution de requêtes pour récupérer les données et de mutations pour modifier les données à distance.
- Mise en œuvre d'une interface utilisateur interactive et esthétique en utilisant Tailwind CSS.
Ce projet vise également à renforcer les compétences en développement frontend moderne, en manipulation des requêtes GraphQL et en gestion des états avec Apollo Client.

## Prérequis
- Node.js (>= 16 recommandé)
- npm
- Backend GraphQL accessible (ex: http://localhost:8080/graphql)

## Installation
- cd gestion-comptes
- npm install
- npm start
L’application sera disponible sur : http://localhost:3000

## Dépendances principales
- react / react-dom
- @apollo/client
- graphql
- tailwindcss, postcss, autoprefixer
## Configuration Apollo
- Le client Apollo est configuré dans :
  src/apollo/client.js
## Fonctionnalités
- Affichage des comptes (GET_ALL_COMPTES) : composant CompteList
- Création d’un compte (SAVE_COMPTE) : composant CreateCompte
- Transactions : TransactionForm et TransactionList (squelette / ou implémentation selon avancement)
  
## Captures d’écran
<img width="2940" height="1838" alt="image" src="https://github.com/user-attachments/assets/058b940f-0e93-4349-8cab-7d1b73149987" />
<img width="2940" height="1838" alt="image" src="https://github.com/user-attachments/assets/042627b9-4f17-45b5-b457-440864756479" />
