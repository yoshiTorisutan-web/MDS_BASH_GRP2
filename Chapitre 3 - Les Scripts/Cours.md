# Scripts en Bash

Bash est un interpréteur de commandes qui est utilisé pour exécuter des scripts sur les systèmes d'exploitation basés
sur Unix. Les scripts en bash sont des programmes écrits dans le langage de script bash. Ils sont souvent utilisés pour
automatiser des tâches répétitives et pour traiter des fichiers en masse.

## Comment écrire un script bash

Pour écrire un script bash, vous pouvez utiliser n'importe quel éditeur de texte. Par exemple, vous pouvez utiliser Vim,
Nano ou Emacs. Les scripts en bash ont généralement l'extension de fichier ".sh". Par exemple, "script.sh".

## Comment exécuter un script bash

Pour exécuter un script bash, vous devez d'abord rendre le script exécutable. Vous pouvez le faire en utilisant la
commande suivante :

```
chmod +x script.sh
```

Ensuite, vous pouvez exécuter le script en tapant :

```
./script.sh
```

## Variables en bash

En bash, vous pouvez utiliser des variables pour stocker des valeurs. Les variables sont des noms que vous assignez à
des valeurs. Par exemple, vous pouvez créer une variable "nom" et lui assigner une valeur "Alice" de la manière
suivante :

```
nom="Alice"
```

Vous pouvez utiliser la variable dans votre script en l'entourant de "$". Par exemple, vous pouvez afficher la valeur de
la variable "nom" en tapant :

```
echo $nom
```

## Boucles en bash

En bash, vous pouvez utiliser des boucles pour exécuter des instructions plusieurs fois. Il existe plusieurs types de
boucles en bash, mais les plus courantes sont "for" et "while". Voici un exemple de boucle "for" qui affiche les nombres
de 1 à 10 :

```
for i in {1..10}
do
    echo $i
done
```

## Conditions en bash

En bash, vous pouvez utiliser des conditions pour exécuter des instructions en fonction de certaines conditions. Il
existe plusieurs types de conditions en bash, mais les plus courantes sont "if" et "case". Voici un exemple de
condition "if" qui affiche "Bonjour" si le nom est "Alice" :

```
if [ $nom == "Alice" ]
then
    echo "Bonjour"
fi
```

Voilà quelques notions de base pour les scripts en bash. Bonne chance pour écrire vos propres scripts !







