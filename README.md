# EI_group4

## notre moteur de recherche : 
pour l'executer, il faut placer le dossier dezippé datascience.stackexchange.com à la racine du projet. /
le fichier principale : Search_engine_final.ipynb /
la fonction de recherche d'appelle CobraSearch, une cellule pour avoir une interface graphique tkinter est disponible vers la fin du notebook


## Idées pour le moteur de recherche :
 - La requête donne une note à chaque document
 - La note est calculée à partir du contenu, des tags, votes, commentaires et de l'utilisateur qui a publié le document
 - La composante de la note à partir du contenu est calculée avec la similarité cosinus
 - Giving more weight to the posts of the users that have the most badges
 - Giving more weight to the posts that have the most votes
 - Giving more weight to the posts that have the most comments
 - Giving more weight to the title of the posts
 - Check matches with the tags of the posts
