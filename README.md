# git


### Configuration
```
git config help
```

### Ajout de fichier
```
git add {file}
git add .
```

### Status
```
git satus
```

### Mettre en staging
```
git add .
git commi -m 'message'
```
**Tips**
```
git commit -a -m 'message
```

### Création de branche
```
git checkout -b {nom de la branche}
```
### Changement de branche
```
git checkout {branch}
```
### Revenir à la branche précedente
```
git checkut -
```

### Voir les logs => afficher les derniers commits
```
git log
```
### Voir les différence sur un fichier
En revanche si on veut comparer en partant de ce qui est stage il faudra rajouter --cachedou --staged
```
git diff
```
### Comparer des commits
```
git diff <commit>           # comparera l'état actuel au commit <commit>
git diff <commit>..<commit> # Permet de comparer les fichier entre 2 commits
```


