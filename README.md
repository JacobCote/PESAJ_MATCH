



# PROGRAMME DE MATCH 
## Utilisation 
On doit configurer les paramètres pour le match dans le fichier config.ini

### paramètres
[NOM_FICHIERS]
donne le chemin d'accès de tous les fichiers pour le match de données

ex: 

FICHIER1: presaj_data/PRESAJ_T1(n=3056).csv


[T]
Suffixe a mettre pour les différents temps de mesure

ex:

Fichier1: T1

Fichier2: T2
...

[CODE_LENGTH]
le nombre de colonnes(variable) que le code a.

ex :

CODE_LENGTH: 11

[START_CODE]
Donne le l'indice de la colonne ou le code commence. Doit être indiqué pour chaq'un
des temps de mesure même si ils commencent tous au même indice.

ex:

START1: 11

START2: 18
...

[WEIGHTS_SCORE]
Poids pour chaque variables dans le code pour le match. 
La somme des poids doit égalé à 100. Toutes les variables du code doivent avoir un poids

ex:

SCORE_MATCH1: 9

SCORE_MATCH2: 9 
...

[PARAMETRES]
Le CUT_OFF_SCORE est le seuile pour qu'un match soit accepté.
Ce score est calculé en fonction des poids
Le MATCH_T2 permet de refaire un match à partir du temp de mesure 2 pour récupérer le 
plus de match possible. Seulement les match complet seront gardé afin de ne pas introduire
de doublons dans le jeu de données.

ex :

CUT_OFF_SCORE: 80

MATCH_T2: TRUE

# Étapes pour utiliser le programme 
## si première fois :
### Installer  GIT
Suivre les étapes pour Windows : https://www.git-scm.com/download/win

Suivre les étapes pour Mac : https://www.git-scm.com/download/mac

### Installer python 
Suivre les étapes pour Windows : https://www.digitalocean.com/community/tutorials/install-python-windows-10

Suivre les étapes pour Mac : https://www.dataquest.io/blog/installing-python-on-mac/

## lancer le programme

### windows 
click droit sur le fichier run_match.exe -> run as administrator

### Mac



Si vous avez des questions, vous pouvez communiquer avec moi :
jacobcote@hotmail.com


