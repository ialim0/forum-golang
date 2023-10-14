# Forum-advanced-features

# Auteurs
* Mouhamadoufadilou Diop - [mouhamadoufadiop](https://learn.zone01dakar.sn/git/mouhamadoufadiop)
* Abdou Khadre Wade - [serwade](https://learn.zone01dakar.sn/git/serwade)
* Alimoudine Idrissou - [ialimoud](https://learn.zone01dakar.sn/git/ialimoud)

#  Comment utiliser notre projet :

    - Cloner ou télécharger ce repo
    - Lancez le programme ~/main.go avec la commande go run main.go
    - Ouvrez votre navigateur et allez sur la page : localhost:8080/
    

#  Fonctionnalités du projet :

    - Creer un compte
    - Creer un topic, et/ou creer un commentaire dans ce topic
    - Ajouter un commentaire sur le topic d'un autre utilisateur
    - Ajouter un like ou un dislike aux topics et aux commentaires
    - Rechercher et filtrer dans les topics, filtrer dans les commentaires
    - Pouvoir changer de username et addresse mail, pouvoir supprimer son compte
    - Voir le profil d'un autre utilisateur et pouvoir lui envoyer un message prive
    - Pouvoir modifier et supprimer un topic ou un comment s'il vous appartient

## Usage
  
To run the web-site on local machine:

- Download the repository

- Run with a command `./run.sh`

- Open [http://localhost:8080/](http://localhost:8080/) in browser

- Register or login with a test user(test@gmail.com, 1234)

- Stop with a command `./stop.sh`

To work with a Docker manually:

- Build image with `sudo docker build -t forum .`

- Run image with `docker container run -p 8080:8080 forum:latest`

You can login with other profiles as well:

- cowboy@gmail.com blacksheep

- snaphappyphotographer@email.com ZoomZoomZap

- rodeoqueen@email.com kingtomyqueen

## Implementation details

- SQL3

- Adaptive web-design
