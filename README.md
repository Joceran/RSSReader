# RSSReader
Joceran FICHOU--MEUNIER

Amir ROMDHAME

Allan BONHOMME

ESIR2 SI Groupe 2

Rapport [disponible ici](https://github.com/Joceran/RSSReader/blob/master/Compte%20Rendu%20Docker%20RSS.pdf)

# Qu'est ce qui marche ?

Le lancement avec docker-compose up de RSSReaderH, qui retélécharge les sources depuis netflix et les builds depuis le conteneur. Permet d'afficher la page rss.jsp

# Qu'est ce qui ne marche pas

L'ajout de flux RSS ne s'affiche pas mais semble être commun a tout le monde.

L'autre version, avec déjà les sources de présente et ajoutés au conteneur directement ne permet pas d'afficher rss.jsp. Le serveur se lance et les services communiques cependant

Ce n'est pas marqué dans le rapport, mais j'ai pu tester le scale finalement, mais ne se lance pas correctement, seul un des services sur les 5 que je lance de chaque se lance. 

