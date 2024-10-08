# Application de Recherche de Données

Bienvenue dans l'application de recherche de données développée par Swilpy. Ce projet permet de rechercher des informations en utilisant divers critères et d'envoyer les résultats à un canal Discord via un webhook.

## Table des Matières

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Utilisation](#utilisation)
4. [Librairies Utilisées](#librairies-utilisées)
5. [Configuration](#configuration)
6. [Contribuer](#contribuer)
7. [Contact](#contact)

## Introduction

Cette application vous permet de rechercher des informations selon différents critères tels que :

- Nom, prénom et date de naissance
- Adresse IP
- Nom de domaine
- Numéro de téléphone
- Adresse
- URL
- Identifiant de réseau social

Les résultats de recherche sont envoyés à un canal Discord via un webhook.

## Installation

Suivez ces étapes pour installer et configurer l'application sur votre ordinateur :

1. **Clonez le Répertoire**

   Ouvrez un terminal et exécutez la commande suivante pour cloner le dépôt :

   ```bash
   git clone https://github.com/votre-utilisateur/votre-repository.git
   cd votre-repository
   ```


2. **Installez les Dépendances**

Assurez-vous que Node.js est installé sur votre machine. Installez les dépendances du projet avec npm :

```bash 
npm install
```

3. **Configurez le Projet**

Créez un fichier config/config.js et ajoutez les informations suivantes :

```js
module.exports = {
  DISCORD_WEBHOOK_URL: 'VOTRE_URL_WEBHOOK_DISCORD',
  GOOGLE_API_KEY: 'VOTRE_CLE_API_GOOGLE',
  GOOGLE_CX: 'VOTRE_ID_MOTEUR_DE_RECHERCHE_PERSONNALISE_GOOGLE',
};
```

Remplacez les valeurs par vos propres informations.

## Utilisation

1. **Démarrez l'Application**

Exécutez la commande suivante pour lancer l'application :

```bash
node index.js
```

2. **Interagissez avec l'Application**

Suivez les instructions à l'écran pour sélectionner le type de recherche et entrer les informations demandées. Les résultats seront affichés dans la console et envoyés au canal Discord spécifié.

## Librairies Utilisées
- axios : Pour effectuer des requêtes HTTP.
- chalk : Pour styliser les messages dans la console.
- figlet : Pour générer des textes stylisés dans la console.
- Installez ces librairies avec la commande suivante :

```bash
npm install axios chalk figlet
```

## Configuration

- DISCORD_WEBHOOK_URL : L'URL du webhook Discord où les résultats seront envoyés.
- GOOGLE_API_KEY : Votre clé API Google pour le moteur de recherche personnalisé.
- GOOGLE_CX : L'ID de votre moteur de recherche personnalisé Google.

## Contribuer
Pour contribuer au projet :

- Forkez le dépôt.
- Créez une nouvelle branche (git checkout -b ma-branche).
- Faites vos modifications.
- Commitez vos changements (git commit -am 'Description des modifications').
- Poussez vos changements (git push origin ma-branche).
- Ouvrez une pull request.

## Contact
- Développeur : Swilpy
- Discord : Swilpy

Pour toute question ou suggestion, n'hésitez pas à me contacter sur Discord.


#   S _ R e c h e r c h e  
 