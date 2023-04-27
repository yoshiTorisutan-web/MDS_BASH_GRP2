# Réponses des exercices pour créer des variables d'environnement concernant Bash et Shell

## Solution 1 : Créer une variable d'environnement pour stocker un message et l'afficher en majuscules

1. Créez une variable d'environnement nommée "MESSAGE".
```
export MESSAGE="Bonjour, comment ça va ?"
```

2. Utilisez la commande "tr" pour convertir le message en majuscules.
```
UPPERCASE_MESSAGE=$(echo $MESSAGE | tr '[:lower:]' '[:upper:]')
```

3. Stockez le message en majuscules dans une nouvelle variable d'environnement nommée "UPPERCASE_MESSAGE".
```
export UPPERCASE_MESSAGE=$UPPERCASE_MESSAGE
```

4. Affichez la valeur de la variable d'environnement "UPPERCASE_MESSAGE" à l'aide de la commande "echo".
```
echo $UPPERCASE_MESSAGE
```

## Solution 2 : Créer une variable d'environnement pour stocker l'âge d'un utilisateur et afficher un message personnalisé
1. Créez une variable d'environnement nommée "USER_AGE".
```
export USER_AGE=22
```

2. Utilisez une structure conditionnelle pour afficher un message personnalisé en fonction de l'âge de l'utilisateur.
```
if [ $USER_AGE -lt 18 ]
then
  echo "Vous êtes encore mineur."
else
  echo "Vous êtes majeur."
fi
```

## Solution 3 : Créer une variable d'environnement pour stocker le chemin d'un fichier et afficher le contenu du fichier
1. Créez une variable d'environnement nommée "FILE_PATH" pour stocker le chemin d'un fichier.
```
export FILE_PATH=/chemin/vers/mon/fichier.txt
```

2. Utilisez la commande "cat" pour afficher le contenu du fichier.
```
cat $FILE_PATH
```
