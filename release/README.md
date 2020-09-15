Les releases : 5 pratiques incontournables
============================================

Les releases, c'est quoi ?
------------------------

Une **release** regroupe tous les fichiers nécessaires à l'installation et à l'exécution du logiciel.

Ces fichiers sont pour la plupart issus du code source mais d'autres fichiers de configuration sont bien souvent aussi nécessaires à l'exécution d'un logiciel.

Enfin, la release est l'artefact qui sera livré pour être installé et utilisé. La release doit donc contenir les documentations [utilisateur](../doc/utilisateur.md) et [administrateur](../doc/administrateur.md).

Qu'est-ce que la qualité d'une release ?
----------------------------------------

Une release dure dans le temps. Certains utilisateurs utiliseront la dernière release sortie alors que d'autres préfèreront utiliser des releases un peu plus vielles.

Une release de qualité est donc une release qui dure dans le temps. Il faut donc être capable d'identifier la "date de sortie" d'une release. Savoir quelles fonctionnalités elle supporte. Et pouvoir facilement l'installer.

Enfin, il faut être capable de suivre les évolutions des releases (les archiver et automatiser leur production).

Liste des bonnes pratiques :
----------------------------

### Rédaction et syntaxique

* [horodater les relases](horodater.md)
* [faire le lien avec les issues](lier.md)
* [faciliter l'installation](installer.md)

### Gestion des modifications

* [archiver les relases](archiver.md)
* [automatiser la production des releases](automatiser.md)
* [choisir une politique d'identifiant de version](versioning.md)
