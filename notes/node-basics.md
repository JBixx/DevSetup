# Notes Node.js basics

Objectif : Approfondir npm, les modules Node.js et les bonnes pratiques de projet.

## npm : ce qu'il faut retenir

`package.json` est le fichier central d'un projet Node.js. Il décrit le nom, la version et les dépendances du projet.

Installer une dépendance :

```bash
npm install express                 # production
npm install --save-dev nodemon      # développement uniquement
```

## Bonnes pratiques notées

1. Ne jamais committer `node_modules/` : c'est volumineux et régénérable
2. Utiliser des variables d'environnement pour les secrets (fichier `.env`)
3. Verrouiller les versions avec `package-lock.json`
4. Nommer les commits de façon claire et descriptive

## Exercice 1 : Afficher "Hello World"

Crée un fichier `hello.js` :

```javascript
console.log("Hello World!");
```

Pour l'exécuter on lance avec : `node hello.js`

Résultat attendu : `Hello World!`

## À approfondir

- Gestion des erreurs avec try/catch et les Promises
- Utilisation de nodemon pour le rechargement automatique
