# MEMO GIT / GITHUB

####Add commit message

```bash
$ git commit -m “Commit message” -a

-m = commit message is going to follow

-a = commit should include **a**ll files
```

####Push to server

```bash

$ git push
```

####Pushing to server (ex Github)

```bash
$ git remote add “remote name → origin” ssh://git-server

$ git remote -v
```

### 1.4

####Création du fichier mémo

### 1.5

> partie 1

```bash
commit 7915688760945176d435406b18fb450089d5476e (HEAD -> main, origin/main)
Author: Ezra Strikwerda <ezra@strikwerda.fr>
Date:   Wed May 17 15:15:09 2023 +0200

    Commit of recipe and realisation files
```

> partie 2

En exécutant 'git checkout' pour revenir à une étape antérieure le contenu dans le dossier change immédiatement.

En utilisant 'git checkout main' on revient à l'état d'avant, c'est à dire, la dernirère version.

**Screenshot of tag:**

<p align="center">
  <img src="http://i.imgur.com/uppJjda.png" />
</p>

### 1.6

-placeholder-

### 1.7

-placeholder-

### 1.8

> Etape 1

Commit après avoir résolu le conflit:

```bash
commit 606857c185e03115f2aca633dbdfd11152323983 (HEAD -> main)
Merge: ed53f37 91c464c
Author: Ezra Strikwerda <ezra@strikwerda.fr>
Date:   Mon May 22 11:01:48 2023 +0200

    Merge branch 'main' after conflict
```

> Etape 2

L'utilisation de Git avec VSCode, très facile, mais c'est quand même bien de connaître la façon terminal pour avoir une meilleure compréhension de ce qui se passe quand on click sur un bouton dans VSCode.

### 1.9

Maintenant qu'on peut plus se connecter à Github avec un simple mot de passe via le terminal j'ai créé une clé SSH au tout début du module pour pouvoir utiliser le terminal.

```bash
user@user-HP-ProDesk-600-G3-SFF:~/Documents/recette-cookie$ git remote -v
origin	git@github.com:Adrew-Kirts/recette-cookie.git (fetch)
origin	git@github.com:Adrew-Kirts/recette-cookie.git (push)
```

### 2.1

Crééé une nouvelle branch "recipe_history"

- Créé un fichier, pushé avec commit message "xxxxxx fixes #1"
  ! Important: entre fixes et #nr il faut un espace !

### 2.2

Un conflit dans Git survient quand deux branches distinces on modifié la même ligne dans un fichier, ou quand un fichier a été supprimé dans une branche, mais modifié dans l'autre.

---
