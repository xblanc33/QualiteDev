Réaliser des modifications précises
===================================

Chaque modification (commit) embarque plusieurs changements du code source. Ces changements doivent porter sur une et une seule préoccupation.

Un commit qui porte sur une seule préoccupation est cohérent. Il est donc possible de mesurer son apport sur la qualité du code source, et donc sur la qualité du logiciel.

Si un commit porte sur plusieurs préoccupations, il est possible que seule une partie du commit améliore la qualité alors que le reste du commit soit néfaste. Si tel est le cas, il devient alors compliqué d'exploiter pleinement le commit.

Objectif
--------

Chaque commit doit être précis c'est à dire qu'il ne doit porter que sur une seule préoccupation.

Il faut donc faire en sorte que les commits soient précis.

Une possibilité est de systématiquement lier un commit à une tâche, en référençant son identifiant dans le message de commit.

Cependant, cette notion de précision du commit reste subjective et est bien souvent contextuelle.

Contrôle
--------

Vérifier que chaque message de commit fait référence à une tâche.

Vérifier que les modifications sont précises par l'audit d'un expert.

L'expert, en auditant les commit, va pouvoir évaluer leur précision, en regardant par exemple les parties du code impactées par le commit.
