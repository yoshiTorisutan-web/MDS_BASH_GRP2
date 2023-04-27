# IV - Gestion de fichiers et de répertoires

Dans ce chapitre, nous allons explorer les commandes de base pour la gestion de fichiers et de répertoires sous Linux. Nous allons voir comment naviguer dans les répertoires, créer et supprimer des fichiers et des répertoires, copier et déplacer des fichiers, rechercher des fichiers, et gérer les permissions d'accès.

## 1\. Les commandes pour naviguer dans les répertoires
----------------------------------------------------

La commande `cd` permet de changer de répertoire. Par exemple, pour accéder au répertoire `/home/user`, saisissez :
```bash
cd /home/user
```

La commande `ls` affiche la liste des fichiers et des répertoires du répertoire courant. Par exemple :
```bash
ls
```

La commande `pwd` affiche le chemin absolu du répertoire courant. Par exemple :
```bash
pwd
```

## 2\. La création, suppression, copie et déplacement de fichiers et de répertoires
--------------------------------------------------------------------------------

La commande `mkdir` permet de créer un nouveau répertoire. Par exemple :
```bash
mkdir monnouveaurepertoire
```

La commande `rmdir` permet de supprimer un répertoire vide. Par exemple :
```bash
rmdir monancienrepertoire
```

La commande `cp` permet de copier un fichier. Par exemple :
```bash
cp monfichier.txt monnouveaufichier.txt
```

La commande `mv` permet de déplacer un fichier ou de le renommer. Par exemple :
```bash
mv monfichier.txt /home/user/ mv monfichier.txt monnouveaunom.txt
```

La commande `rm` permet de supprimer un fichier. Par exemple :
```bash
rm monfichier.txt
```

## 3\. La recherche de fichiers avec la commande find
--------------------------------------------------

La commande `find` permet de rechercher des fichiers dans une hiérarchie de répertoires. Par exemple, pour rechercher tous les fichiers `.txt` dans le répertoire `/home/user` :
```bash
find /home/user -name "*.txt"
```

## 4\. Les permissions d'accès aux fichiers et aux répertoires
-----------------------------------------------------------

Les permissions d'accès aux fichiers et aux répertoires sont contrôlées par les commandes `chmod` et `chown`. La commande `chmod` permet de changer les permissions de lecture, d'écriture et d'exécution pour le propriétaire, le groupe et les autres utilisateurs. Par exemple, pour donner la permission de lecture et d'écriture au propriétaire pour le fichier `monfichier.txt` :
```bash
chmod u+rw monfichier.txt
```

La commande `chown` permet de changer le propriétaire et le groupe d'un fichier ou d'un répertoire. Par exemple, pour changer le propriétaire du fichier `monfichier.txt` en `user` :
```bash
chown user monfichier.txt
```

## 5\. Les archives et les compressions de fichiers
------------------------------------------------

Les archives et les compressions de fichiers sont couramment utilisées pour regrouper des fichiers et des répertoires en un seul fichier compressé. Les commandes correspondantes n'ont pas de réponse spécifique, car elles dépendent de la situation et des besoins de l'utilisateur.