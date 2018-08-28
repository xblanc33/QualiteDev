Vers un recueil de bonnes pratiques pour la qualité logicielle
==============================================================

Réaliser un logiciel de qualité est le premier des objectifs que tout développeur a en tête. 
Pour autant, il n'est toujours pas aisé de savoir quoi faire pour réaliser un logiciel de qualité, d'autant plus depuis ces dernières années devant l'abondance de nouvelles technologies.

Afin d'améliorer cette situation, nous une liste minimale de bonnes pratiques visant à améliorer la qualité des développement.

Nous proposons d'organiser les bonnes pratiques sur les 6 artefacts nécessaires à l'élaboration de n'importe quel logiciel : issue, tâches, test, code source, documentation, release.
Nous considérons que ces 6 artefacts sont absoluments nécessaire pour gérer un projet logiciel de qualité [voir plus bas](#pourquoi-6-artefacts-).

L'objectif est ainsi de pouvoir mesurer la qualité logicielle d'un projet en fonciton de ces 6 axes. Vous pourrez ainsi savoir si votre projet est idéal (ou presque), s'il est bien organisé (les issues et les tâches ont une très bonne qualité, par contre le code, les tests, la doc et les release moins), ou s'il est plutôt technique (le code et les tests ont une bonne qualité mais pas les issues, les tâches, la doc et les release).

![qualité du logiciel](radar.png)

Notre approche se veut ouverte. Elle est donc matérialisée par un projet GitHub afin de favoriser tout un chacun à y participer (n'hésitez pas à envoyer vos pull-request). La [méthode employée](./METHODE.md) pour élaborer le recueil est elle aussi ouverte et clairement détaillée permettant de bien mesurer l'apport de chaque pratique listée par le recueil.

Le recueil des bonnes pratiques 
===============================

* DONE [Les bonnes pratiques des issues](./issue/)
* DONE [Les bonnes pratiques des tâches](./tache/)
* DOING [Les bonnes pratiques des tests](./test/)
* TODO [Les bonnes pratiques du code source](./code/)
* TODO [Les bonnes pratiques de la documentation](./doc/)
* TODO [Les bonnes pratiques des release](./release/)



Quelle méthode est employée pour recueillir une bonne pratique ?
================================================================

Notre recueil des bonnes pratique est complètement ouvert. 

Le [guide de rédaction](./METHODE.md) des bonnes pratiques décrit la méthode que nous avons utilisée pour décrire des bonnes pratiques. Cette méthode est elle aussi ouverte.

QUIZZ : Connaissez-vous les bonnes pratiques ? 
==============================================

TODO: Nous comptons proposer un QUIZZ permettant à tout un chacun d'évaluer sa connaissance sur les bonnes pratiques de développement.

Ce qu'est le recueil et ce qu'il n'est pas ?
============================================

Notre recueil a pour objectif de lister toutes les pratiques permettant d'élaborer un logiciel de qualité. Chaque pratique listée par notre recueil est clairement détaillée et sa valeur ajoutée est rigoureusement qualifiée (preuve, indice, impression) permettant ainsi de mesurer son effet.

Notre recueil n'est pas une nouvelle méthode expliquant les différentes étapes à réaliser pour développer un logiciel. Pour autant, certaines pratiques proposées par certaines méthodes améliorant la qualité sont référencées.

Notre recueil n'est pas un nouveau standard de qualité logiciel. La qualité logicielle ayant plusieurs définitions [Wikipedia](https://fr.wikipedia.org/wiki/Qualit%C3%A9_logicielle), notre objectif n'est absolument pas d'en définir une n-ième. L'objectif étant de référencer les bonnes pratiques et de préciser quels aspects elles améliorent.

Pourquoi 6 artefacts ?
======================

Nous considérons que tout logiciel nécessite l'élaboration d'au moins six artefacts :

* Issue
* Tache
* Test
* Code source
* Documentation
* Release

Chacun des ces artefacts est facilement identifiable par des fichiers (même si la documentation peut être incluse dans un fichier de code source, il est facile de la distinguer). 

Chaque artefact a une qualité qui lui est propre. Chaque bonne pratique cible donc un type d'artefact et améliore un aspect de sa qualité.

Chaque artefact est en relation avec les autres artefact. Une bonne pratique ciblant un artefact a donc un effet sur la qualité des autres artefacts en relation. 

Chaque artefact peut être modifié permettant ainsi de faire évoluer le logiciel. Une bonne pratique permet ainsi de préciser la façon dont les modifications doivent être réalisée pour améliorer la qualité d'un artefact.
