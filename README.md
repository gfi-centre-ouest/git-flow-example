Exemple git flow
----------------

Un repository git mettant en oeuvre git-flow.

git-flow est un ensemble d'extensions git permettant des opérations de haut niveau sur un dépôt pour appliquer le 
modèle de branches de Vincent Driessen.


Conventional Commits
--------------------
Avant de parler de git-flow, commençons par parler de la structure de nos messages de commit.

On utilisera la convention [Conventional Commits 1.0.0](https://www.conventionalcommits.org/fr/v1.0.0/) pour rédiger 
chaque message de commit.

Pour respecter cette convention facilement, vous pouvez utiliser le plugin Jetbrains [Git Commit Template](https://plugins.jetbrains.com/plugin/9861-git-commit-template), 
ou bien [Commitizen](https://github.com/commitizen/cz-cli) si vous êtes plutôt habitué à la ligne de commande (Nécessite NodeJS).

Les types de branches de git-flow
---------------------------------

Git flow est structuré via différent type de branche.

- **develop**: Il s'agit de la version en cours de développement. Notre intégration doit refléter cette branche en permance.
