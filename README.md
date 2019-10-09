Twitter Bot Test
=======
Ceci est un test de bot Twitter fait en ruby à partir de l'API Tweeter et la Gem Tweeter : https://github.com/sferik/twitter#usage-examples

## Methodes

La méthode **login_twitter** permet de se connecter à son api avec les clés et token dans fichier .env qu'il faudra rajouter.

La méthode **send_twitt** envoi un tweet à nombre de journaliste choisis au hasard parmis un array.

La méthode **send_twitt_direct** envoi un tweet.

La méthode **like_bonjour_monde(string, nb)** va liker un nombre de tweets comprenant un hashtag ou un terme en particulier suivant la string choisis. 

La méthode **follow_bonjour_monde(string, nb)** va suivre les utilisateurs qui ont mis dans la string choisis dans leur tweet. Nb définis ce nombre de tweets qui vont être regardé. 

La méthode **follow_hashtag (string, nb)** fait la même chose que la précédente mais jusqu'à atteindre le nombre nb de users demandés.

La méthode **login_twitter_stream** permet de se connecter en accès streamer

La méthode **stream_twitt (string)** . Mets en place un robot qui like et follow les comptes tweetant une string dès l'apparition du Tweet. En Streamant. 
Pour arrêter le programma **ctrl + c**

## Dossiers 

**Lib** comprends les méthodes

**spec** comprends les tests

**gemlife** comprends la version de ruby et les gems indispensable pour faire fonctionner ce programme