# LES VARIABLES D'ENVIRONNEMENT

## Introduction
Les variables d'environnement sont des variables spéciales qui sont utilisées par le système d'exploitation pour stocker des informations sur l'environnement dans lequel les programmes s'exécutent. Ces variables peuvent être utilisées pour stocker des informations telles que le chemin d'accès à un répertoire, le nom de l'utilisateur actuel, ou toute autre information que vous souhaitez stocker pour une utilisation ultérieure.

Pour créer une variable d'environnement dans Bash ou Shell, vous devez utiliser la syntaxe suivante :
```
NOM_DE_LA_VARIABLE=valeur_de_la_variable
```

Pour lire une variable d'environnement dans Bash  ou Shell, vous devez utiliser la syntaxe suivante :
```
echo $NOM_DE_LA_VARIABLE
```

Vous pouvez également utiliser la commande "export" pour rendre la variable disponible pour tous les processus en cours d'exécution :

```
export NOM_DE_LA_VARIABLE
```