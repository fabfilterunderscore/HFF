# TP Git — Association Les Codeurs

Petit site réalisé pour notre TP de Git en première année. On travaille à trois : Flavien, Hadrien et Fabrice.

Le but est d’apprendre à travailler sur le même projet avec des branches, des commits et des pull requests, puis à gérer les conflits et corriger nos erreurs.

## Prérequis

- Un navigateur web.
- Git installé.
- Un éditeur de code, comme Visual Studio Code.

Aucune dépendance à installer ni serveur à lancer.

## Installation

Cloner le dépôt :

```bash
git clone https://github.com/fabfilterunderscore/HFF.git
```

Entrer dans le dossier :

```bash
cd HFF
```

Ouvrir le projet dans Visual Studio Code :

```bash
code .
```

## Lancement

Ouvrir `index.html` dans un navigateur en double-cliquant dessus.

## Structure du projet

Les pages sont ajoutées au fur et à mesure du TP.

```text
HFF/
├── index.html      # Page d'accueil
├── projets.html    # Présentation des projets
├── contact.html    # Page contact
├── mentions.html   # Mentions légales
├── .gitignore      # Fichiers ignorés par Git
└── README.md       # Présentation du projet
```

## Répartition du travail

- Flavien : page projets et pied de page.
- Hadrien : page contact et résolution du conflit sur le titre.
- Fabrice : mentions légales, réparation du commit cassé et tag final.

## Contribution

Chacun travaille sur sa branche et publie ses modifications. Un autre membre relit la pull request avant de la fusionner dans `main`.

## Exercices du TP

- Créer et publier des branches.
- Résoudre un conflit de fusion.
- Faire un rebase et résoudre son conflit.
- Utiliser `restore`, `stash` et `revert`.
- Créer le tag `v1.0.0` pour la version stable.

## Rendu

Le rendu comprend le lien du dépôt, trois captures de l’historique, un journal des commandes et les réponses aux questions du TP.
