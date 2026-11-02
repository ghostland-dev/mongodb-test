Absolument ! Voici un README professionnel et détaillé, conçu pour impressionner les recruteurs et mettre en valeur vos compétences techniques.

---

# 🚀 TypeScript MongoDB Data Service Template

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Licence MIT](https://img.shields.io/badge/Licence-MIT-green.svg)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Mongoose ODM](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker--Compose-000000?style=for-the-badge&logo=docker&logoColor=white)

## 📋 Description

Ce projet, nommé "TypeScript MongoDB Data Service Template", est une preuve de concept et un boilerplate robuste conçu pour illustrer l'implémentation d'une API RESTful moderne et scalable, interagissant avec une base de données MongoDB. Développé en TypeScript, il met l'accent sur la **sécurité de type**, la **modularité**, et les **bonnes pratiques de développement backend** pour créer des services de données fiables et maintenables.

L'objectif principal de ce dépôt est de fournir une base solide pour la création de microservices ou de services backend qui nécessitent une persistance de données NoSQL avec MongoDB. Il résout le problème de l'initialisation de projets complexes en offrant une structure claire, une configuration simplifiée via Docker et Docker Compose, et une interaction avec la base de données encapsulée et typée. Ce template démontre une expertise dans la gestion du cycle de vie des applications, de la configuration de l'environnement au déploiement conteneurisé, en passant par la conception d'API.

La valeur ajoutée pour les recruteurs réside dans la démonstration concrète d'une maîtrise des technologies backend clés, de l'architecture logicielle, de l'intégration de bases de données, et de l'utilisation de la conteneurisation pour garantir des environnements de développement et de production cohérents. C'est un exemple fonctionnel d'un service prêt à l'emploi, facilement extensible et conforme aux standards de l'industrie.

## ✨ Fonctionnalités

*   **API RESTful complète:** Implémentation de toutes les opérations CRUD (Create, Read, Update, Delete) pour une entité exemple (`User`).
*   **Type Safety avec TypeScript:** Utilisation rigoureuse de TypeScript pour un code robuste, moins sujet aux erreurs d'exécution et plus facile à maintenir.
*   **Architecture modulaire:** Séparation claire des préoccupations (contrôleurs, services, modèles) pour une meilleure organisation du code et une facilité de test.
*   **Intégration MongoDB:** Connexion et interaction efficaces avec une base de données MongoDB via Mongoose ODM.
*   **Conteneurisation Docker & Docker Compose:** Environnement de développement et de production reproductible et isolé, garantissant une cohérence maximale.
*   **Gestion des variables d'environnement:** Utilisation de `.env` pour une configuration sécurisée et flexible de l'application.
*   **Validation des données:** (Optionnel, mais facilement intégrable) Possibilité d'ajouter des couches de validation au niveau du modèle ou des routes.
*   **Code propre et commenté:** Adhésion aux principes de code propre pour une lisibilité et une compréhension accrues.

## 🚀 Technologies utilisées

Ce projet s'appuie sur une stack technologique moderne et éprouvée, choisie pour ses performances, sa fiabilité et sa flexibilité :

*   **TypeScript**: ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
    *   **Pourquoi**: Offre la sécurité de type statique au JavaScript, ce qui améliore la maintenabilité du code, réduit les erreurs et facilite la collaboration sur des projets de grande envergure. Indispensable pour des applications backend robustes.
*   **Node.js**: ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
    *   **Pourquoi**: Runtime JavaScript asynchrone et événementiel, idéal pour construire des APIs rapides et scalables.
*   **Express.js**: ![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)
    *   **Pourquoi**: Framework minimaliste et flexible pour Node.js, standard de l'industrie pour la création d'APIs RESTful.
*   **MongoDB**: ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
    *   **Pourquoi**: Base de données NoSQL orientée document, offrant une grande flexibilité de schéma et une excellente performance pour les applications à forte intensité de données.
*   **Mongoose**: ![Mongoose ODM](https://img.shields.io/badge/Mongoose-880000?style=flat&logoColor=white)
    *   **Pourquoi**: Un ODM (Object Data Modeling) puissant pour MongoDB et Node.js, qui simplifie la gestion des relations et des schémas, et apporte une couche de validation.
*   **Docker**: ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
    *   **Pourquoi**: Pour la conteneurisation de l'application et de la base de données, assurant un environnement d'exécution isolé, portable et reproductible.
*   **Docker Compose**: ![Docker Compose](https://img.shields.io/badge/Docker--Compose-000000?style=flat&logo=docker&logoColor=white)
    *   **Pourquoi**: Pour l'orchestration multi-conteneurs, facilitant le déploiement et la gestion de l'application et de sa base de données comme un seul service.
*   **dotenv**: Pour charger les variables d'environnement depuis un fichier `.env`.

## 📦 Installation

Suivez ces étapes pour mettre en place et exécuter le projet localement.

### Prérequis

Assurez-vous d'avoir les outils suivants installés sur votre machine :

*   **Docker** et **Docker Compose** : [Installer Docker Desktop](https://www.docker.com/products/docker-desktop)
*   **Node.js** (version 14 ou supérieure) et **npm** (inclus avec Node.js) : [Télécharger Node.js](https://nodejs.org/en/download/)

### Étapes d'installation

1.  **Cloner le dépôt** :
    ```bash
    git clone https://github.com/votre-utilisateur/Mongodb-test.git
    cd Mongodb-test
    ```

2.  **Configuration des variables d'environnement** :
    Créez un fichier `.env` à la racine du projet en copiant le fichier `.env.example` et en renseignant les valeurs appropriées.
    ```bash
    cp .env.example .env
    ```
    Exemple de `.env` :
    ```env
    # Application Port
    PORT=3000

    # MongoDB Configuration
    MONGO_DB_URL=mongodb://mongodb:27017/mydatabase # 'mongodb' est le nom du service dans docker-compose
    MONGO_DB_NAME=mydatabase
    ```
    *Note*: Pour une exécution hors Docker Compose (développement local sans conteneur de DB), `MONGO_DB_URL` devrait pointer vers `mongodb://localhost:27017/mydatabase` si MongoDB est installé localement.

3.  **Lancer les conteneurs Docker (Recommandé)** :
    Utilisez Docker Compose pour démarrer l'API et la base de données MongoDB.
    ```bash
    docker-compose up --build -d
    ```
    *   `--build` : Construit les images Docker si elles ne sont pas déjà présentes.
    *   `-d` : Démarre les conteneurs en mode détaché (en arrière-plan).

    Les services devraient être accessibles :
    *   API : `http://localhost:3000`
    *   MongoDB : Accessible uniquement depuis le conteneur API (port 27017 interne au réseau Docker).

4.  **Installation et exécution locale (Alternative, sans Docker pour l'API)** :
    Si vous souhaitez exécuter l'application Node.js directement sur votre machine (par exemple, pour le développement avec rechargement à chaud), tout en utilisant un MongoDB conteneurisé :

    *   Démarrer uniquement le conteneur MongoDB :
        ```bash
        docker-compose up -d mongodb
        ```
    *   Installer les dépendances Node.js :
        ```bash
        npm install
        ```
    *   Lancer l'application en mode développement (avec `ts-node-dev` pour le rechargement à chaud) :
        ```bash
        npm run dev
        ```
    *   Lancer l'application en mode production :
        ```bash
        npm run start
        ```

## 🎯 Utilisation

Une fois le service démarré, l'API est accessible via `http://localhost:3000`. Voici quelques exemples de requêtes que vous pouvez effectuer :

Nous utiliserons une entité `User` simple avec les champs `username` et `email`.

### 1. Créer un nouvel utilisateur (POST)

```bash
curl -X POST \
  http://localhost:3000/api/users \
  -H 'Content-Type: application/json' \
  -d '{
    "username": "john_doe",
    "email": "john.doe@example.com"
  }'
```
Réponse (succès) :
```json
{
  "_id": "65b7d6e8f0a2b1c3d4e5f6g7",
  "username": "john_doe",
  "email": "john.doe@example.com",
  "createdAt": "2024-01-29T10:00:00.000Z",
  "updatedAt": "2024-01-29T10:00:00.000Z",
  "__v": 0
}
```

### 2. Récupérer tous les utilisateurs (GET)

```bash
curl http://localhost:3000/api/users
```
Réponse (liste d'utilisateurs) :
```json
[
  {
    "_id": "65b7d6e8f0a2b1c3d4e5f6g7",
    "username": "john_doe",
    "email": "john.doe@example.com",
    "createdAt": "2024-01-29T10:00:00.000Z",
    "updatedAt": "2024-01-29T10:00:00.000Z",
    "__v": 0
  },
  {
    "_id": "65b7d6e8f0a2b1c3d4e5f6h8",
    "username": "jane_smith",
    "email": "jane.smith@example.com",
    "createdAt": "2024-01-29T10:05:00.000Z",
    "updatedAt": "2024-01-29T10:05:00.000Z",
    "__v": 0
  }
]
```

### 3. Récupérer un utilisateur par ID (GET)

Remplacez `[USER_ID]` par l'ID réel d'un utilisateur (par exemple, `65b7d6e8f0a2b1c3d4e5f6g7`).

```bash
curl http://localhost:3000/api/users/[USER_ID]
```
Réponse (utilisateur unique) :
```json
{
  "_id": "65b7d6e8f0a2b1c3d4e5f6g7",
  "username": "john_doe",
  "email": "john.doe@example.com",
  "createdAt": "2024-01-29T10:00:00.000Z",
  "updatedAt": "2024-01-29T10:00:00.000Z",
  "__v": 0
}
```

### 4. Mettre à jour un utilisateur (PUT)

```bash
curl -X PUT \
  http://localhost:3000/api/users/[USER_ID] \
  -H 'Content-Type: application/json' \
  -d '{
    "username": "john_updated",
    "email": "john.updated@example.com"
  }'
```
Réponse (utilisateur mis à jour) :
```json
{
  "_id": "65b7d6e8f0a2b1c3d4e5f6g7",
  "username": "john_updated",
  "email": "john.updated@example.com",
  "createdAt": "2024-01-29T10:00:00.000Z",
  "updatedAt": "2024-01-29T10:15:00.000Z",
  "__v": 0
}
```

### 5. Supprimer un utilisateur (DELETE)

```bash
curl -X DELETE \
  http://localhost:3000/api/users/[USER_ID]
```
Réponse (succès, pas de contenu) : `204 No Content`

## 🏗️ Architecture

Ce projet suit une architecture en couches, favorisant la séparation des préoccupations (SoC) et rendant le code plus maintenable, testable et évolutif.

```
+------------------+     +-----------------------+     +---------------------+
|      Client      | --> |  API Gateway (Express)| --> | Controllers (Routes)|
+------------------+     +-----------------------+     +---------------------+
                                     |                           |
                                     v                           v
+------------------+       +---------------------+       +-----------------+
|   Environment    | <---- |     Services        | <---- |  Models/Mongoose|
|   Configuration  |       |  (Business Logic)   |       | (Data Schema)   |
+------------------+       +---------------------+       +-----------------+
                                     |
                                     v
+---------------------+
|   MongoDB Database  |
|  (via Docker/Docker |
|       Compose)      |
+---------------------+
```

### Composants Principaux

*   **API Gateway (Express.js)** : Le point d'entrée de l'application. Gère les requêtes HTTP entrantes et les achemine vers les contrôleurs appropriés. Responsable de la configuration des middlewares globaux.
*   **Controllers** : Chaque contrôleur est responsable de la gestion des requêtes spécifiques à une ressource (ex: `UserController` pour les utilisateurs). Il orchestre l'interaction entre la requête HTTP et la logique métier du service. Il ne contient pas de logique métier directe, mais délègue aux services.
*   **Services** : Contiennent la logique métier principale de l'application. Ils interagissent avec les modèles (via Mongoose) pour effectuer des opérations sur la base de données et manipuler les données. Cette couche est agnostique à la source HTTP.
*   **Models (Mongoose)** : Définit la structure des données (schémas) pour les collections MongoDB et fournit l'interface pour interagir avec la base de données (CRUD). Mongoose ajoute également des fonctionnalités de validation et des hooks.
*   **Configuration (`.env` & `config` modules)** : Gère les variables d'environnement et les configurations spécifiques à l'application, assurant une séparation claire entre le code et les paramètres d'environnement.
*   **Docker & Docker Compose** : Fournissent une couche d'abstraction pour l'environnement d'exécution, garantissant que l'application et sa base de données fonctionnent de manière cohérente, quelle que soit la machine hôte.

### Flux de Données

1.  Une requête HTTP (ex: `POST /api/users`) est reçue par l'**API Gateway (Express)**.
2.  L'API Gateway la route vers le **Contrôleur** approprié (ex: `UserController.createUser`).
3.  Le Contrôleur extrait les données de la requête et les passe au **Service** (ex: `UserService.createUser`).
4.  Le Service utilise le **Modèle Mongoose** correspondant (ex: `UserModel`) pour interagir avec la **base de données MongoDB**.
5.  MongoDB exécute l'opération (insertion, récupération, etc.) et renvoie le résultat au Modèle.
6.  Le Modèle renvoie les données au Service.
7.  Le Service traite les données (si nécessaire) et renvoie le résultat au Contrôleur.
8.  Le Contrôleur formate la réponse HTTP et la renvoie au **Client** via l'API Gateway.

## 📸 Screenshots/Demos

*   **Démarrage des conteneurs** : (capture d'écran ou GIF des logs `docker-compose up`)
    ```
    Attaching to mongodb-test_api_1, mongodb-test_mongodb_1
    mongodb_1  | ... MongoDB starting ...
    api_1      | [nodemon] starting `ts-node src/server.ts`
    api_1      | MongoDB connected: mongodb://mongodb:27017/mydatabase
    api_1      | Server running on port 3000
    ```
*   **Exemples de requêtes Postman/Insomnia** : (captures d'écran montrant les requêtes `GET /api/users` et `POST /api/users` avec leurs réponses)
    *   Montrer une requête `POST` réussie avec le corps JSON et la réponse `201 Created`.
    *   Montrer une requête `GET` réussie avec une liste d'utilisateurs et la réponse `200 OK`.
*   *(Si un frontend était associé, une capture de l'interface utilisateur interagissant avec l'API serait idéale ici)*

## 🤝 Contributions

Les contributions sont les bienvenues ! Si vous souhaitez améliorer ce projet, voici comment procéder :

1.  **Fork** ce dépôt.
2.  **Clonez** votre fork : `git clone https://github.com/votre-utilisateur/Mongodb-test.git`
3.  Créez une **nouvelle branche** pour vos modifications : `git checkout -b feature/ma-nouvelle-feature`
4.  Effectuez vos changements et assurez-vous que le code respecte les bonnes pratiques.
5.  **Commit** vos modifications : `git commit -m "feat: Ajout d'une nouvelle fonctionnalité"`
6.  **Push** vers votre branche sur GitHub : `git push origin feature/ma-nouvelle-feature`
7.  Ouvrez une **Pull Request** détaillée expliquant vos modifications.

Veuillez suivre les bonnes pratiques de codage, inclure des tests si possible, et mettre à jour la documentation si vos changements l'affectent.

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

## Author

**Ismail.M**, Software Engineer & DevOps

- GitHub: [@ghostland-dev](https://github.com/ghostland-dev)
- Website: [ismail-mouyahada.com](https://www.ismail-mouyahada.com)
