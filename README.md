# DevSetup

Configuration de mon environnement de développement local. Ce dépôt centralise les notes, la documentation et les fichiers de base pour démarrer un projet Node.js proprement.

## Installation

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/JBixx/DevSetup.git
   cd DevSetup
   ```

2. Vérifier que Node.js est installé (version 18 ou supérieure recommandée) :
   ```bash
   node --version
   npm --version
   ```

3. Installer les dépendances du projet :
   ```bash
   npm install
   ```

4. Lancer le script de démarrage pour vérifier que tout fonctionne :
   ```bash
   npm start
   ```

## Utilisation

Ce dépôt sert de point de départ pour mes projets. Le dossier `notes/` contient mes réflexions et apprentissages au fil des semaines. Le fichier `package.json` définit les scripts de base disponibles.

Commandes utiles :

| Commande      | Description                          |
|---------------|--------------------------------------|
| `npm start`   | Lance l'application en mode simple   |
| `npm run dev` | Mode développement avec rechargement |

Pour ajouter une nouvelle note, créer un fichier markdown dans `notes/` en suivant la convention de nommage existante.

## Structure du projet

```
DevSetup/
├── README.md                        # Documentation principale
├── package.json                     # Configuration npm et scripts
├── index.js                         # Point d'entrée de l'application
├── .gitignore                       # Fichiers exclus du versioning
├── .editorconfig                    # Règles de formatage éditeur
└── notes/
    ├── notes-semaine1.md            # Première semaine
    ├── node-basics.md               # Deuxième semaine
    └── setup-guide.md               # Guide
```

## Liens et références

- [Documentation Node.js](https://nodejs.org/docs/)
- [Guide GitHub — Premiers pas](https://docs.github.com/fr/get-started)
- [npm — Documentation officielle](https://docs.npmjs.com/)
- [Markdown Guide](https://www.markdownguide.org/)
