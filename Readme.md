# Documentation du tuto github avec git

# initialisation du depot

""" bash
git init """

# Si on veut changer le type de connection

# en Https il faut changer :

/\*
url = git@github.com:Robert-1956/Git_Tuto.git en https://github.com/Robert-1956/Git_Tuto.git
dans le fichier .git/config
\*/
#Rediger un commit
....
Titre du commit

Description de notre commitavec des informations sur l'evolution du projet
# Envoyer un commit sur le depot distant
....
bash
git add .
git commit -m "Titre du commit"
git push origin main
....