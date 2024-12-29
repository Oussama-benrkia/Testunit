
# Système d'Automatisation de Tests Logiciels

Ce projet propose un logiciel basé sur l'IA capable de générer automatiquement des scénarios de tests unitaires et fonctionnels. Il utilise des algorithmes d'apprentissage automatique pour analyser le code source, optimiser la couverture des tests et identifier les cas d'erreurs potentiels. En cas de test échoué, le logiciel peut également suggérer des correctifs ou ajustements.

## Fonctionnalités

1. **Clonage de projets GitHub** : Extraction des projets pour une analyse approfondie.
2. **Analyse AST (Abstract Syntax Tree)** : Analyse syntaxique pour détecter les classes et méthodes.
3. **Génération de tests** : Création de tests unitaires à partir des informations extraites.
4. **Visualisation des résultats** : Une interface utilisateur interactive pour afficher les statuts des tests.

## Architecture du Système

- **Frontend** : Développé avec Angular pour gérer les projets et afficher les résultats des tests.
- **Backend** : Implémenté avec Spring Boot pour la logique métier et la génération des tests.
- **Base de données** : MySQL pour le stockage structuré des données.



## Outils Utilisés

- **Spring Boot** : Framework backend pour les APIs et la logique métier.
- **Angular** : Développement de l'interface utilisateur.
- **MySQL** : Base de données relationnelle pour stocker les projets et résultats.
- **Docker** : Conteneurisation de l'application.
- **Postman** : Outil pour tester les APIs.
- **IntelliJ IDEA** et **VSCode** : Environnements de développement intégrés.

### Prérequis :

1. *Git :*
   - Assurez-vous que Git est installé. Sinon, téléchargez-le et installez-le depuis [git-scm.com](https://git-scm.com/).

2. *XAMPP :*
   - Installez XAMPP depuis [apachefriends.org](https://www.apachefriends.org/).
   - Démarrez les serveurs Apache et MySQL dans XAMPP.
   - Assurez-vous que MySQL utilise le port 3306.

3. *Node Js Version   :*
   - Installez node depuis [node](https://nodejs.org/en/download/package-manager).

### Configuration du Backend :

1. *Cloner le Projet :*
```bash
   git clone https://github.com/Oussama-benrkia/AI-Software-for-Test-Automation-System.git
   cd AI-Software-for-Test-Automation-System
```

2. *Installer les Dépendances Backend :*
   - Ouvrez un terminal dans le dossier du projet backend.
   - Exécutez les commandes suivantes :
```bash
   mvn clean install
```

3. *Exécuter le Backend :*
   - Démarrez vos serveurs Apache et MySQL via XAMPP.
   - Lancez l'application Spring Boot. La base de données et les entités seront créées automatiquement.
   - Vérifiez que le backend fonctionne en visitant [http://localhost:8080](http://localhost:8080) dans votre navigateur.

### Configuration du Frontend :

1. *Installer Node.js et Angular :*
   - Ouvrez un nouveau terminal pour le projet frontend.
cdd    - Installez Angular CLI globalement : `npm install -g @angular/cli`.

2. *Installer les Dépendances Frontend :*
   - Exécutez les commandes suivantes dans le dossier du projet frontend :
```bash
   npm install
```
- Si vous rencontrez des erreurs pendant l'installation, utilisez la commande suivante :
```bash
   npm install --save --legacy-peer-deps
```

3. *Exécuter le Frontend :*
   - Après avoir installé les dépendances, lancez le serveur de développement Angular :
```bash
   ng serve
```

- Accédez à l'interface frontend à [http://localhost:4200](http://localhost:4200) dans votre navigateur.

Votre projet full-stack devrait maintenant être opérationnel en local. Si vous rencontrez des problèmes, consultez les journaux de la console pour les messages d'erreur et assurez-vous que toutes les dépendances et prérequis sont correctement installés.

## Vidéo de Démonstration

Cliquez sur le lien ci-dessous pour regarder une vidéo de démonstration :
[http://localhost:4200](https://drive.google.com/file/d/1wK-G16si_1OjPYiB6nUjni810F4J0DZb/view)


## Contribution

Nous accueillons les contributions de tous et nous apprécions votre aide pour améliorer ce projet ! Si vous souhaitez contribuer, veuillez suivre ces lignes directrices :

---

J'espère que cette version vous convient !
