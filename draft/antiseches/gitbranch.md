# git command

## Gestion des branches

### Création

Montre les branches du répertoire
`git branch`
Pour créer une nouvelle branche
`git checkout -b 'nom-qui-a-du-sens'`


### Déplacement entre branche et principal
Pour se déplacer vers la branche
`git checkout nom-de-la-branche`
ou
`gco nom-de-la-branche`

Pour retourner sur la branche master
`git checkout master`
ou
`gco nom-de-la-branche`

### Lecture et mise-à-jour

Montre si besoin de créer une version sur la branche
`gst`
Montre ce qui a été changé
`git diff`

Ajoute les fichiers à versionner
`git add .`
Ajoute un nom à la version
`git commit -m 'nom-qui-a-du-sens'`

**Met la version à jour *sur la branche***
`git push origin nom-de-la-branche`

### Valider la branche et fusionner sur *master*
Sur github aller sur *compare & pull request*
Commenter et ajouter des captures d'écrans
Bonne pratique (en équipe): on ne fusionne pas ses propres branches mais le code est revu par une autre personne

Retourner sur la branche master
`git checkout master`
ou
`gco nom-de-la-branche`

**Reprendre la code principal sur le local**
`git pull origin master`

**Nettoyer les branches fusionnées**
`git sweep`

### Aide
Pour forcer la suppression d'une branche
`git branch -D nom-de-la-branche`

pour remettre le code principal sur une branche
`git merge master`



