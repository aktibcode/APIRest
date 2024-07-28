A-  Ce que vous visez

    Dans ce point de contrôle, vous exécuterez une série d'instructions guidées pour créer une API REST en manipulant votre base de données avec mongoose.

    PS : n'oubliez pas de commenter votre code avant de le soumettre.

B-  Instructions

    1-  Démarrer un nouveau projet Node JS avec ' npm init '

    2-  Installez la mangouste et express et .env

    3-  Configurer les variables d’environnement avec .env

    4-  Lancer un serveur avec express dans le fichier server.js

    5-  Connectez votre base de données localement ou avec mongo atlas

    6-  La structure du dossier devrait être comme ceci :

        config/.env 

        Serveur.js

    7-  Créez un dossier de modèles et un fichier User.js dedans 

    8-  Dans User.js, vous devez définir un schéma mongoose et exporter le modèle, vous l'utiliserez dans le server.js

    9-  La structure du dossier doit être comme ceci : 

        config/.env 

        modèles/User.js

        Serveur.js

    10- Dans le server.js créez quatre routes : 

       OBTENIR : RETOURNER TOUS LES UTILISATEURS 

       POSTE : AJOUTER UN NOUVEL UTILISATEUR À LA BASE DE DONNÉES 

       PUT : MODIFIER UN UTILISATEUR PAR ID 

       SUPPRIMER : SUPPRIMER UN UTILISATEUR PAR ID 

NB : dans chaque fonction de rappel, vous utiliserez des méthodes mongoose pour manipuler vos données et les renvoyer dans la réponse 

    11- Utilisez le facteur pour tester chaque itinéraire.

                 

  Liens utiles : 

    1-  .env : https://www.npmjs.com/package/dotenv
    2-  Express js : https://expressjs.com/
    3-  Req.params et req.query : https://coursework.vschool.io/express-params-and-query/
    4-  Mangouste : https://mongoosejs.com/
    5-  API REST : https://www.youtube.com/watch?v=SLwpqD8n3d0