# Notty — TODO app

Notty est une application de liste de tâches (TODO)

## Fonctionnalités

- Inscription / connexion (authentification)
- Page d'accueil (landing)
- Dashboard utilisateur protégé (liste de todos)
- CRUD complet des todos : créer, lire, mettre à jour, supprimer
- Marquer comme fait / non fait
- Stockage en ligne via Supabase
- Design responsive avec Tailwind CSS

## Prérequis

- Node.js v18+ (recommandé)
- npm, yarn, ou pnpm
- Compte Supabase

## Variables d'environnement

Crée un fichier `.env` à la racine du projet et ajoute :

```
SUPABASE_URL=https://xxxxx.supabase.co
```

```
SUPABASE_KEY=public-anon-key-or-service-role-if-server
```

## Commandes utiles

#### lancer le projet en dev (hot-reload)

```
npm run dev
```

#### build pour production

```
npm run build
```
