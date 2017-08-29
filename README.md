Vers un recueil de bonnes pratiques pour la qualité logicielle
==============================================================

Réaliser un logiciel de qualité est le premier des objectifs que tout développeur a en tête. 
Pour autant, et ce presque 50 ans après l'invention du génie logiciel ([L'OTAN Définit le génie logiciel](http://homepages.cs.ncl.ac.uk/brian.randell/NATO/NATOReports/index.html)), il n'est toujours pas aisé de savoir quoi faire pour réaliser un logiciel de qualité.

Afin d'améliorer cette situation, nous proposons ce projet GitHub dont l'objectif est de recueillir les bonnes pratiques visant à améliorer la qualité des 5 artefacts constituant n'importe quel logiciel : code source, test, documentation, build, issue.

Notre approche se veut ouverte. Elle est donc matérialisée par un projet GitHub afin de favoriser tout un chacun à y participer (n'hésitez pas à envoyer vos pull-request). La méthode employée pour élaborer le recueil est elle aussi ouverte et clairement détaillée permettant de bien mesurer l'apport de chaque pratique listée par le recueil.

Le recueil des bonnes pratiques 
===============================

* [Les bonnes pratiques du code source](./code/README.md)
* [Les bonnes pratiques des tests](./test/README.md)
* [Les bonnes pratiques de la documentation](./doc/README.md)
* [Les bonnes pratiques des builds](./build/README.md)
* [Les bonnes pratiques des issues](./issue/README.md)


QUIZZ : Connaissez-vous les bonnes pratiques ? 
==============================================


Questions fréquement posées 
===========================

Ce qu'est le recueil et ce qu'il n'est pas ?
--------------------------------------------

Notre recueil a pour objectif de lister toutes les pratiques permettant d'élaborer un logiciel de qualité. Chaque pratique listée par notre recueil est clairement détaillée et sa valeur ajoutée est rigoureusement qualifiée (preuve, indice, impression) permettant ainsi de mesurer son effet.

Notre recueil n'est pas une nouvelle méthode expliquant les différentes étapes à réaliser pour développer un logiciel. Pour autant, certaines pratiques proposées par certaines méthodes améliorant la qualité sont référencées.

Notre recueil n'est pas un nouveau standard de qualité logiciel. La qualité logicielle ayant plusieurs définitions [Wikipedia](https://fr.wikipedia.org/wiki/Qualit%C3%A9_logicielle), notre objectif n'est absolument pas d'en définir une n-ième. L'objectif étant de référencer les bonnes pratiques et de préciser quels aspects elles améliorent.


Pourquoi 5 artefacts ?
----------------------

Afin de structurer le recueil des bonnes pratiques, nous considérons que tout logiciel est au moins constitué de cinq artefacts :
* Code source
* Test
* Documentation
* Build
* Issue

Chacun des ces artefacts est facilement identifiable par des fichiers (même si la documentation peut être incluse dans un fichier de code source, il est facile de la distinguer). 

Chaque artefact a une qualité qui lui est propre. Chaque bonne pratique cible donc un type d'artefact et améliore un aspect de sa qualité.

Chaque artefact est en relation avec les autres artefact. Une bonne pratique ciblant un artefact a donc un effet sur la qualité des autres artefacts en relation. 

Chaque artefact peut être modifié permettant ainsi de faire évoluer le logiciel. Une bonne pratique permet ainsi de préciser la façon dont les modifications doivent être réalisée pour améliorer la qualité d'un artefact.


Comment savoir si une pratique est bonne ?
------------------------------------------


* preuve de (non) qualité
* indice de (non) qualité
* impression de (non) qualité


Quelle méthode est employée pour recueillir une bonne pratique ?
----------------------------------------------------------------


