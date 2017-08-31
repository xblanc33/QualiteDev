 Type | ID 
 ---- | -- 
 Code source | Code-Modif-2 

Les évolutions du code source doivent se faire sur différentes branches
=======================================================================

Toutes les modifications apportées au code source n'ont pas le même objectif, la même portée, le même niveau d'importance. Certaines modifications sont des modifications mineures alors que d'autres des ajouts de nouvelles fonctionnalités ou des corrections de bug importants. 
Certaines sont réalisée quotidiennement et seront peut-être remises en question dans les jours à venir, d'autres finalisent des versions stables du logiciel et seront alors pérenne.

Pour garder traces des différents niveaux d'importance des modifications il faut les séparer en différentes branches de modifications.
Une branche pourra alors contenir toutes les modifications de maintenance alors qu'une autre branche pourra contenir toutes les modifications faites quotidiennement.

Si les évolutions du code source ne sont pas réalisées sur différentes branche il n'est alors pas possible de différencier les différents niveaux d'importrance des modifications. Retrouver certaines versions importantes n'est donc pas possible. Cela nuit ainsi à la qualité du code car on ne peut pas savoir sur quelles version une attention plus importante doit être apportée. 


Objectif
--------
Les évolutions du code source doivent être réalisée sur différentes branches pour différencier leur différents niveaux d'importance.

Cela consiste à utiliser les mécanismes de branche proposés par outil support à la gestion des versions (Git, SVN, etc.), ou, si ces outils ne proposent pas de tels mécanismes, d'utiliser plusieurs dépots ou même de définir un mécanisme propriétaire.

Des modèles de gestion de branches tels que GitFlow peuvent être suivi pour bien identifier toutes les branches support à l'évolution du code source.

Contrôle
--------
Cette pratique peut être prouvée.

La preuve consiste à : 
1. Identifier l'outil ou les mécanismes propriétaires supports à la gestion des branches. 
2. S'assurer que les différents niveaux d'importance du code source sont gérés par des branches différentes.

