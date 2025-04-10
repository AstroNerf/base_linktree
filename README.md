# Base de projet Linktree HTML/CSS
<img width="1431" alt="Capture d’écran 2025-04-10 à 18 27 39" src="https://github.com/user-attachments/assets/8b4b8abc-ed1f-46ce-978b-85358a5f6de5" />
Salut la team ! 👋

Ceci est le repo de base pour votre Projet Linktree en pure HTML & CSS. Vous trouverez ici tous les éléments fondamentaux pour démarrer le projet tout en respectant les meilleures pratiques de développement web moderne.

## Structure HTML imposée par le projet

Le projet nécessite d'utiliser les balises sémantiques fondamentales :

* **Header** : Cette section contiendra l'en-tête de votre page, idéalement avec votre identité visuelle et votre nom/titre. C'est la première impression que les visiteur·euse·s auront de votre Linktree.

* **Main** : C'est le cœur de votre Linktree où vous placerez tous vos liens et contenus principaux. Cette balise indique au navigateur et aux technologies d'assistance que c'est ici que se trouve le contenu principal.

* **Footer** : Cette partie clôture votre page et contient généralement des informations secondaires comme les mentions légales, les crédits, ou encore des liens vers vos réseaux sociaux.

## Organisation des fichiers
<img width="1238" alt="Capture d’écran 2025-04-10 à 18 49 13" src="https://github.com/user-attachments/assets/5538664e-a350-445c-9709-e4ec960d671a" />
J'ai organisé ce repo pour vous faciliter la vie et vous introduire aux bonnes pratiques d'architecture CSS :

```
index.html                  → Le fichier HTML principal déjà connecté au CSS
style.css                   → Le fichier CSS principal qui importe toutes les variables
│
├── assets/                 → Contient toutes les ressources statiques
│   ├── images/             → Pour stocker vos images & icônes
│   └── fonts/              → Polices personnalisées (déjà chargées depuis fontspace.com)
│
└── styles/                 → Organisation modulaire de votre CSS
    ├── all_variables.css   → Le point central qui importe tous les fichiers de variables
    ├── fonts.css           → Variables de typographie & chargement des polices
    ├── colors.css          → Palette de couleurs sous forme de variables
    ├── animations.css      → Transitions & animations réutilisables
    ├── layout.css          → Variables pour conteneurs, espacements, breakpoints, etc.
    └── boutons.css         → Composants de boutons prêts à l'emploi
```

## Pourquoi utiliser des variables CSS ?

Les variables CSS (aussi appelées propriétés personnalisées) transforment complètement votre façon de travailler :

1. **Cohérence visuelle** : Modifiez une couleur ou une taille à un seul endroit & tout votre site s'adapte automatiquement. Fini les rechercher/remplacer risqués !

2. **Maintenabilité** : Lorsque votre projet grandit, les variables vous évitent de vous perdre dans des centaines de lignes de CSS. Tout est organisé & nommé de façon logique.

3. **Travail d'équipe simplifié** : Vous travaillez en groupe ? Les variables créent un langage commun : tout le monde sait que `var(--color-primary)` est la couleur principale du projet.

4. **Responsive sans prise de tête** : Grâce aux media queries, vous pouvez modifier la valeur d'une variable selon la taille d'écran, et tous les éléments qui l'utilisent s'adapteront automatiquement.

## Comment contribuer à ce projet ?

Que vous souhaitiez ajouter des fonctionnalités, corriger des bugs ou simplement améliorer la structure, votre contribution est la bienvenue ! Deux approches s'offrent à vous :

### Option 1 : Cloner le repository

Le clonage crée une copie locale du projet que vous pouvez modifier tout en gardant un lien avec le repository original.

```bash
# Dans votre terminal
git clone git@github.com:AstroNerf/base_linktree.git
cd base_linktree

# Créez une nouvelle branche pour vos modifications
git checkout -b ma-nouvelle-fonctionnalite

# Après avoir fait vos modifications
git add .
git commit -m "Ajout de ma super fonctionnalité"
git push origin ma-nouvelle-fonctionnalite
```

Ensuite, rendez-vous sur GitHub pour créer une Pull Request afin que vos modifications puissent être revues et intégrées au projet principal.

### Option 2 : Forker le repository

Le fork crée votre propre copie du projet sur votre compte GitHub, vous donnant une liberté totale pour l'adapter à vos besoins.

1. Cliquez sur le bouton "Fork" en haut à droite de la page du repository
2. Clonez VOTRE version du repository sur votre machine
3. Faites vos modifications
4. Si vous souhaitez partager vos améliorations avec le projet original, créez une Pull Request depuis votre fork

## Pour démarrer rapidement

```bash
# Clonez le repository
git clone git@github.com:AstroNerf/base_linktree.git

# Accédez au dossier du projet
cd base_linktree

# Ouvrez le projet dans VS Code (si vous l'utilisez)
code .

# Ou simplement ouvrez index.html dans votre navigateur préféré
```

À partir de là, vous pouvez commencer à personnaliser votre Linktree en modifiant le HTML et le CSS selon vos besoins. La structure et les variables sont déjà en place pour vous faciliter le travail !

N'hésitez pas à explorer les fichiers de variables CSS pour comprendre comment ils sont organisés & comment les utiliser au mieux dans votre projet.

Bon coding à tou·te·s ! 💻✨
