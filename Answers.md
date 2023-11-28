# Validation and Verification: Practical Session #1

## Exercice 1

Voici l'article choisi pour le bug : https://www.igen.fr/domotique/2023/01/une-faille-permettait-de-transformer-un-google-home-mini-en-micro-espion-134715. Ce bug concernait les produits Google Home, les enceintes connectées de Google. Par ce bug, un utilisateur externe au réseau wifi de l'enceinte pouvait s'y connecter et en prendre le contrôle. Ce bug est dit global car il exploite des intéractions entre les composants qui n'ont pas été pensées. 

Pour reproduire le bug, il fallait attaquer le réseau Wifi auquel l'appareil était connecté pour le déconnecter. Ensuite, l'attaquant devait se connecter à l'enceinte pour ensuite réussir à y lier son compte Google. Une fois cette étape réussie, l'attaquant pouvait envoyer toutes sortes d'ordres à l'enceinte depuis son smartphone par l'application Google : écouter les micros, manipuler les objets connectés à l'enceinte, récupérer certaines informations et ce par le biais d'injection de routines ou de petites application dans le Google Home. 

Ce bug représente donc une énorme faille de sécurité pour les utilisateurs du Google Home. Heureusement, celui qui a découvert la faille a prévenu Google, se faisant alors rétribué d'une prime de 100 000 dollars. A mon sens, ce bug aurait pu être évité si Google n'avait pas récupéré un OS non adapté (celui des télés Chromecast) comme base de l'OS du Google Home. Les ingénieurs Google aurait aussi pu mettre ce bug en évidence par certains tests d'intrusion sur ce scénario précis.

## Exercice 2  

Parmi les bugs résolus rapportés par Apache, nous avons choisi celui-ci : [https://issues.apache.org/jira/projects/COLLECTIONS/issues/COLLECTIONS-802?filter=doneissues] On avait une classe AbstractReferenceMap<K,V> ayant un itérateur ReferenceBaseIterator. Le bug venait de la méthode hasNext() de l'itérateur qui ne fonctionnait pas correctement. En effet, le code changeait l’état 

## Exercice 3

## Exercice 4

## Exercice 5


Author : Alexandre LECOMTE et Sterenn LE HIR
