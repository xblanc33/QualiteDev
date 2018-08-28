Les évolutions du code source doivent se faire sur différentes branches
=======================================================================

Toutes les modifications apportées au code source sont effectuées dans le contexte d'une [tâche](../tache) pour réaliser une ou plusieurs [issues](../issue).

De fait, effectuer une tâche et même réaliser une issue va nécessiter plusieurs modifications par plusieurs développeurs, à des moments différents.

Un développement de qualité nécessite l'isolation du contexte afin de bien regrouper toutes les modifications qui partagent un même objectif.

Le regroupement peut se faire par issue par exemple. Dans ce cas toutes les modifications qui vise la réalisation de l'issue sont regroupées dans un même contexte. Il peut aussi se faire par période englobant visant la réalisation d'un ensemble d'issues.

Plusieurs outils sont exploitable pour identifier clairement l'isolation du contexte. On peut par exemple exploiter le concept de branche proposé par les gestionnaires de version et ainsi construire une branche par contexte. On pourrait alors avoir une branche regroupant tous les commits ciblant un même ensemble d'issues.

Sans isolation du contexte il n'est alors pas possible de différencier les modifications apportées au code source. Cela nuit ainsi à la qualité du code car on ne peut pas savoir quelles sont les intentions des modifications apportées. Il devient alors quasiement impossible de [suivre les tâches](../tache/suivre.md) et de gérer la [plannification des issues](../issue/planification.md).  

Objectif
--------

Les évolutions du code source doivent être cloisonnées.

Cela consiste à utiliser les mécanismes proposés par les outils supports à la gestion des évolutions (tels que Git).

La façon dont cloisonner les modifications (par issue, par ensemble d'issue, etc.) doit être définie en amont et connue de tous les développeurs.

Contrôle
--------

Cette pratique peut être automatisée lorsque l'utilisation des mécanismes supports (branches, etc.) sont rendus obligatoire.

Sinon, il la vérification doit être faite par un expert qui doit auditer les commits.
