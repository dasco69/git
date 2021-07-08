# git



### ### Configuration

```
git config help
```

### ### Ajout de fichier

```
git add <file>
git add --all
or
git add .
```

### ### Status

```
git satus
```

### ### Mettre en staging

```
git add .
git commit -m 'message'
```
***Tips***
```
git commit -a -m 'message
```
### ### Revenir en arrière

```
git checkout <id commit> <file>
```
Au lieu de supprimer le commit de l’historique du projet, elle détermine comment annuler les changements introduits par le commit et ajoute un nouveau commit avec le contenu ainsi obtenu. Ainsi, Git ne perd pas l’historique, lequel est important pour l’intégrité de votre historique de révision et pour une collaboration fiable.
```
git revert
```
### ### Création de branche

```
git checkout -b <nom de la branche>
```
### ### Changement de branche

```
git checkout <branch>
```
### ### Revenir à la branche précedente

```
git checkout -
```

### ### Voir les logs => afficher les derniers commits

```
git log
```
### ### Voir les différence sur un fichier

En revanche si on veut comparer en partant de ce qui est stage il faudra rajouter —cachedou —staged
```
git diff
```
### ### Comparer des commits

```
git diff <commit>           # comparera l'état actuel au commit <commit>
git diff <commit>..<commit> # Permet de comparer les fichier entre 2 commits
```


### ### Reset

Comme si nous n’avions pas mis en staging le fichier
```
git reset HEAD <file>
or
git reset -- <file>
```
virer le staging 
```
git reset
```
via le mode —hard => ATTENTION pas possible de revenir sur la commande
```
git reset --hard
```
  
