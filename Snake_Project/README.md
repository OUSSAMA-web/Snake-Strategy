Les fichiers sources se trouvent dans le dossier "src".
Les fichiers éxécutables se trouvent dans le dossier "build".

1) Lancer les programmes

Veuillez lancer en premier server.jar avant client.jar (car celui-ci essaie de se connecter automatiquement)

Par défaut, le port du serveur est "1234" vous pouvez le changer en ligne de commande :
EXEMPLE : javaw -jar server.jar 443

Part défaut, l'IP du client est "localhost" et son port est "1234"
Il est également possible de changer l'IP et/ou le port pour le client :

EXEMPLE : javaw -jar client.jar 127.0.0.1 443
		  javaw -jar client.jar 127.0.0.1
		  
Vous observerez que le serveur est "actif" par défaut, vous pouvez cliquer sur le bouton pour le rendre inactif.
Un fichier "logs.txt" est également créer et vous pourrez consulter les diverses actions des clients sur celui-ci.
Avant de fermer le serveur, assurez vous de l'avoir rendu inactif, cela permet de bien enregistrer les logs.
	  
2) Gameplay

Utilisez les flêches directionnelles pour changer de direction, en cas de mort appuyer sur la touche "ENTRÉE" pour ressusciter. 
Appuyer sur une flêche directionnelle vous procure également un boost de vitesse.
Votre score est visible sur le titre de la fenêtre du jeu, un fruit mangé est un score de 10 points.

3) Amusez-vous ! 

