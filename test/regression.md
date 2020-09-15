_Test de non régression_
==========================

A chaque fois qu'une issue de dysfonctionnement est remontée, il est important de créer
un test qui permet de reproduire le problème identifié. Si il n'est pas possible de 
reproduire de manière automatique le problème, alors il sera de toute façon difficile 
de s'assurer que le problème est réglé.

Automatiser la reproductibilité d'un dysfonctionnement est aussi un bon moyen d'identifier
des conditions manquantes dans l'issue.

Objectif
--------

Tous les dysfonctionnements remontés dans les issues doivent être testés individuellement
pour s'assurer que dans les développements futurs ces problèmes ne réapparaîtront pas (tests de non-régression).

Un moyen simple de s'assurer de cela est de créer pour chaque dysfonctionnement un test qui le reproduit dont le nom fait référence à l'issue qui l'a remonté.

Contrôle
--------

Les tests de non-régression sont facilement identifiables par leur nom, qui fait référence à des issues.

Il est donc possible de compter ces tests et de comparer ce nombre aux dysfonctionnements remontés dans les issues.

Le nombre de tests doit augmenter au cours de la maintenance du logiciel. Si ce n'est pas le cas, il y a de fortes chances que cette bonne pratique soit ignorée.
