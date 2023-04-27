# IV - **(Réponses)** Gestion de fichiers et de répertoires

### 1.  Écrivez la commande pour naviguer dans le répertoire `/home/user/documents` en utilisant la commande `cd`.
```bash
cd /home/user/documents
```
### 2.  Quelle commande affiche la liste des fichiers et des répertoires dans le répertoire courant ?
```bash
ls
```
### 3.  Écrivez la commande pour créer un nouveau répertoire appelé `nouveaurepertoire`.
```bash
mkdir nouveaurepertoire
```
### 4.  Écrivez la commande pour supprimer le répertoire vide `ancienrepertoire`.
```bash
rmdir ancienrepertoire
```
### 5.  Écrivez la commande pour copier le fichier `monfichier.txt` dans un nouveau fichier appelé `nouveaufichier.txt`.
```bash
cp monfichier.txt nouveaufichier.txt
```
### 6.  Écrivez la commande pour déplacer le fichier `monfichier.txt` dans le répertoire `/home/user`.
```bash
mv monfichier.txt /home/user
```
### 7.  Écrivez la commande pour renommer le fichier `monfichier.txt` en `nouveaunom.txt`.
```bash
mv monfichier.txt nouveaunom.txt
```
### 8.  Écrivez la commande pour supprimer le fichier `monfichier.txt`.
```bash
rm monfichier.txt
```
### 9.  Écrivez la commande pour rechercher tous les fichiers `.txt` dans le répertoire `/home/user`.   
```bash
find /home/user -name "*.txt"
```
### 10.  Écrivez la commande pour donner la permission de lecture et d'écriture au propriétaire pour le fichier `monfichier.txt`.
```bash
chmod u+rw monfichier.txt
```