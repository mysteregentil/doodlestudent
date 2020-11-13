# Doodle in quarkus

Ce repository est une application de type doodle développée avec quarkus.io pour le back et angular pour le front. 

Elle initialise automatiquement un pad pour la réunion et un salon de discussion. 

Le but est de faire travailler les étudiants sur la partie déploiement de ce type d'application dite cloud native. 

Votre mission est de mettre en production une telle application en permettant 
- qu'à chaque commit sur ce repository, si les tests passent, alors nous déployons automatiquement une nouvelle version dans un contexte (Continuous Deployement)
- que l'application doit être monitorer finement. 
- que l'application redémarre automatiquement en cas de crash du serveur ou de crash d'un des services de l'application. 
- que Les accès doivent http doivent utiliser https. 


Une démo de l'application est accessible [ici](https://doodle.diverse-team.fr).

Une vidéo de l'application est accessible [ici]().


Un descriptif du cours, des TPs et des étapes du projet est lui accessible [ici](https://hackmd.diverse-team.fr/s/SJqu5DjSD)