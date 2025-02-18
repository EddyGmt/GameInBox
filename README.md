# GameInBox
*Par Eddy G et Clément B*

## Projet

Projet qui fait référence à la fameuse application Letterbox. Nous permettant de recenser dans un premier temps les jeux auxquels nous 
avons joué mais également lsiter les jeux que l'on veut faire. 
Dans un premier temps, comme toutes applications où nous pouvons faire des reviews, il nous sera
possible de noter les jeux et y laisser des commentaires.
Ensuite sur le long terme nous souhaitons pousser l'aspect social de cette application pour que nos utilistaeurs puissent se créer des communautés,
donc intégrer les abonnements entre user, les messages en temps réels, et autres finctionnalités de la sorte.
Au plaisir de nous suivre dans cette aventure!


## Fonctionnalités

* Nous allons commencer par créer une applcation web et ensuite une epplication mobile sur le long terme.
* Pour le front = React
* Pour le back = Nodejs ExpressJs
* Base de données PostgreSQL
* Conteneur Docker
* CI/CD
* Test unitaire
* (création d'un bot discord pour les push, PR, et mise en place de tickets)

  ## Étapes du projet 
##**TODOLIST**

### Global
Créer un fichier Dockerfile
Créer un fichier de CI/CD
Créer un webhook pour lier le projet au discord 
Adapter l'archtecture hexagonale

### Front
* (Créer Maquette figma)
* Trouver une librairie UI pour le front
* Faire un premier Router 
* Créer des composants qui reveiendront souvent sur notre app

### Back
* Créer serveur Express
* Créer la base de donées Postgres ainsi que les tables dont nous aurons besoin via un ORM
* Faire le router
* Ajouter un swagger pour retrouver nos API plus facilement


#### USER: 
* Inscription
* Connexion 
* Update de son compte
* Noter les jeux
* Faire des reviews sur un jeu 
* Pouvoir commenter les reviews des jeux 

#### ADMIN:
* CRUD USER 
* CRUD JEUX

#### JEUX: 
* Recenser les Jeux joués et à faire liés par un user 

