**Nom :** Gricourt Paul

**Groupe :** C2

**Année :** Première année

**IUT Le Havre - Cours GIT**

### Compte-rendu TP1 Introduction GIT

## -- 3.2 -- ##
  ## Modifié (modified) ## 
Il a des modification locales, il va falloir le sélectionner (stage) pour ensuite valider (commit) ses modifications.

  ## Sélectionné (staged) ## 
Ses modification ont été sélectionnées (staged) pour être validées (commited).

  ## Validé (commited) ## 
Il est synchrone avec le dépôt et ne requière pas de validation.

## -- 4.1 -- ## 
  Quand on tape git status, ça nous renvoie ceci : 
  
"On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        src/Cryptomonnaie.class

nothing added to commit but untracked files present (use "git add" to track)"

  Ce qui signifie que l'ajout de .gitignore n'a rien fait, c'est pour ça que nous devons le modifier.
  Une fois la commande "*.class" mise dans le fichier .gitignore, cela fait que Git ignore tous les fichiers qui finissent par ".class".


