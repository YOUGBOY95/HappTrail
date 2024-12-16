# HappTrail

HappTrail est une application mobile innovante qui connecte les utilisateurs aux événements autour d'eux en temps réel. En combinant des cartes interactives et des notifications contextuelles, HappTrail permet de découvrir des activités locales de manière amusante et intuitive.

---

## **Table des Matières**

1. [Fonctionnalités](#fonctionnalités)
2. [Technologies](#technologies)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributions](#contributions)
6. [Licence](#licence)

---

## **Fonctionnalités**

- **Carte interactive** : Affiche les événements en temps réel sur une carte.
- **Notifications basées sur la localisation** : Recevez des alertes pour des événements proches.
- **Catégories personnalisées** : Filtrez les événements selon vos préférences (sports, musique, expositions, etc.).
- **Création d’événements** : Proposez vos propres activités et invitez les autres utilisateurs.
- **Connexion sociale** : Partagez des événements avec vos amis et suivez leurs activités.

---

## **Technologies**

HappTrail utilise des outils modernes pour une expérience fluide et performante :

### **Frontend** :
- [React Native](https://reactnative.dev/) (avec Expo pour un déploiement rapide)
- Bibliothèques :
  - `react-navigation` : Pour la navigation entre les pages.
  - `react-native-maps` : Pour afficher les cartes interactives.

### **Backend** :
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) : Base de données NoSQL cloud.

### **Outils supplémentaires** :
- Axios : Gestion des requêtes API.
- Dotenv : Gestion des variables d’environnement.
- GitHub : Gestion du versionnement et collaboration.

---

## **Installation**

### **Prérequis**
Avant de commencer, assurez-vous d’avoir :
- **Node.js** installé (version LTS recommandée).
- **Expo CLI** installé globalement :
  ```bash
  npm install -g expo-cli
  ```
- **Git** pour le versionnement.
- Un compte [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) pour configurer la base de données.

### **1. Cloner le projet**
```bash
git clone https://github.com/ton-utilisateur/happtrail.git
cd happtrail
```

### **2. Installer le Frontend**
1. Naviguez dans le dossier `client` :
   ```bash
   cd client
   ```
2. Installez les dépendances :
   ```bash
   npm install
   ```

### **3. Installer le Backend**
1. Naviguez dans le dossier `server` :
   ```bash
   cd ../server
   ```
2. Installez les dépendances :
   ```bash
   npm install
   ```

### **4. Configuration**
1. Créez un fichier `.env` dans le dossier `server` et ajoutez les variables suivantes :
   ```env
   MONGO_URI=your-mongodb-uri
   PORT=5000
   ```
2. Démarrez le backend :
   ```bash
   node app.js
   ```
3. Démarrez le frontend :
   ```bash
   cd ../client
   expo start
   ```

---

## **Usage**

1. **Lancer l’application** : Scannez le QR code affiché par Expo dans votre terminal ou navigateur avec l’application Expo Go.
2. **Explorer la carte** : Parcourez les événements proches sur la carte interactive.
3. **Filtrer par catégories** : Utilisez les filtres pour trouver des événements correspondant à vos intérêts.
4. **Créer des événements** : Ajoutez vos propres événements et invitez d’autres utilisateurs à y participer.

---

## **Contributions**

Les contributions sont les bienvenues ! Voici comment vous pouvez aider :

1. Forkez le dépôt.
2. Créez une nouvelle branche :
   ```bash
   git checkout -b feature/nom-de-la-fonctionnalité
   ```
3. Ajoutez vos modifications.
4. Soumettez une pull request.

---

## **Licence**

HappTrail est distribué sous la licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

