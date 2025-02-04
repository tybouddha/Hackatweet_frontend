# Hackatweet Frontend

## 🚀 Prérequis
- [Node.js](https://nodejs.org/) (version 14.x ou supérieure)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

## 📥 Clonage du Projet
```bash
git clone https://github.com/tybouddha/Hackatweet_frontend.git
cd Hackatweet_frontend
```

## 📦 Installation des Dépendances
```bash
npm install  # ou yarn install
```

## 🔧 Configuration
### Variables d'Environnement
Créez un fichier `.env` à la racine du projet avec les variables suivantes :
```env
NEXT_PUBLIC_API_URL=http://localhost:3000
```
Assurez-vous que l'URL pointe vers le backend de votre application.

## ▶️ Démarrage du Serveur
### Développement
```bash
npm run dev  # ou yarn dev
```
Le serveur de développement sera accessible sur [http://localhost:3000](http://localhost:3000).

### Production
```bash
npm run build
npm start  # ou yarn build && yarn start
```

## 📂 Structure du Projet
```
Hackatweet_frontend/
│
├── components/
├── pages/
├── public/
├── styles/
│
├── .env
├── package.json
└── README.md
```

## 🚀 Déploiement
### Plateformes Recommandées
#### **Vercel**
1. Connectez votre dépôt GitHub.
2. Configurez les variables d'environnement.
3. Déployez votre application.

#### **Netlify**
1. Connectez votre dépôt GitHub.
2. Configurez les variables d'environnement.
3. Déployez votre application.

## 🧪 Tests
```bash
npm test  # ou yarn test
```

## 🤝 Contribution
1. Forkez le projet.
2. Créez votre branche de fonctionnalité (`git checkout -b feature/AmazingFeature`).
3. Commitez vos modifications (`git commit -m 'Add some AmazingFeature'`).
4. Poussez votre branche (`git push origin feature/AmazingFeature`).
5. Ouvrez une Pull Request.

## 📞 Contact
- **Brunée** - bruneecedric@gmail.com
- **Projet GitHub** : [Hackatweet Frontend](https://github.com/tybouddha/Hackatweet_frontend)

## 🚨 Problèmes Courants
- Assurez-vous que le backend est opérationnel et accessible.
- Vérifiez que les variables d'environnement sont correctement définies.
- Consultez les logs en cas d'erreurs lors de l'exécution.

## 📚 Ressources Supplémentaires
- [📖 Documentation Next.js](https://nextjs.org/docs)
- [📘 Documentation React](https://reactjs.org/docs/getting-started.html)
- [📙 Documentation Redux](https://redux.js.org/introduction/getting-started)
