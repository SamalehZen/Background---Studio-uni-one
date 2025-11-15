# ChatGPT Clone avec Unicorn Studio

Cette mini-application est une interface d'accueil de style ChatGPT qui utilise le fond animé d'Unicorn Studio.

## Prévisualisation locale

Ouvrez simplement `index.html` dans votre navigateur favori. Les dépendances (Tailwind, Lucide, Unicorn Studio) sont chargées via CDN, il suffit donc d'une connexion Internet.

## Déploiement sur Vercel

1. Installez l'outil CLI de Vercel si nécessaire :
   ```bash
   npm install -g vercel
   ```
2. Authentifiez-vous :
   ```bash
   vercel login
   ```
3. Depuis ce dossier, lancez le déploiement :
   ```bash
   vercel --prod
   ```
   Vercel détecte `vercel.json` et sert le fichier statique `index.html`.

Aucune variable d'environnement n'est requise.
