 Type | ID | Importance
 ---- | -- | --
 Code source | Code-Modif-3 | Conseillée

Chaque modification (commit) doit porter sur une seule préoccupation
====================================================================

Chaque modification (commit) embarque plus plusieurs changements dans le code source. Ces changements doivent porter sur une et une seule préoccupation. 

Un commit qui porte sur une seule préoccupation est cohérent. Il est donc possible de mesurer son apport sur la qualité du code source.
Si un commit porte sur plusieurs préoccupation, il est possible que seule une partie du commit améliore la qualité alors que le reste du commit soit néfaste. Si tel est le cas, il devient alors compliqué d'exploiter pleinement le commit. 



Objectif
--------

Chaque commit doit être cohérent c'est à dire qu'il ne doit porter sur une seule préoccupation (correction d'un bug, ajout d'une fonctionnalité, refactoring, etc.).

Il faut donc faire en sorte que les commits soient cohérent. Malheureusement, cette notion de cohérence du commit ne peut être mesurée que subjectivement et est bien souvent contextuelle. Voilà pourquoi cette pratique est vivement conseillée et non pas incontournable.

Contrôle
--------
Cette pratique ne peut pas être prouvée et il n'est pas possible de disposer d'indices permettant de mesurer son application. Il est donc possible que d'avoir des impressions quant à son suivie.

Pour collecter des impressions il faut observer plusieurs commit et manuellement vérifier qu'ils ne portent que sur une et une seule préoccupation. 

