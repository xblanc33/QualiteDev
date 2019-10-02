Organiser les évolutions
========================

Toutes les modifications apportées au code source doivent être versionnées. Une modification est alors un commit archivé par un gestionnaire de configuration (i.e. Git).

Tous les commits sont effectués dans le contexte d'une [tâche](../tache) pour réaliser une ou plusieurs [issues](../issue).

De fait, effectuer une tâche et même réaliser une issue vont nécessiter plusieurs commits par plusieurs développeurs, à des moments différents.

Un développement de qualité nécessite l'isolation du contexte afin de bien regrouper tous les commits qui partagent un même objectif.

Le regroupement peut se faire par issue par exemple. Dans ce cas, tous les commits qui visent la réalisation de l'issue sont regroupés dans un même contexte. Il peut aussi se faire par période visant la réalisation d'un ensemble d'issues.

Plusieurs mécanismes proposés par les gestionnaires de configuration sont exploitables pour identifier clairement l'isolation du contexte. On peut par exemple exploiter le concept de branche et ainsi construire une branche par contexte. On peut aussi exploiter le concept de message associé au commit et mettre un mot clé sur tous les commits d'un même contexte.

Sans isolation du contexte, il n'est alors pas possible de différencier les commits apportés au code source. Cela nuit ainsi à la qualité du code car on ne peut pas savoir quelles sont les intentions des commits. Il devient alors quasiment impossible de [suivre les tâches](../tache/suivre.md) et de gérer la [planification des issues](../issue/planification.md).  

Objectif
--------

Le code source doit être versionné. Cela consiste à utiliser des outils de gestion de configuration (tels que Git).
Une modification devient alors un commit.

Les commits du code source doivent être cloisonnés.
La façon dont cloisonner les commits (par issue, par ensemble d'issues, etc.) doit être définie en amont et connue de tous les développeurs.

Contrôle
--------

Cette pratique peut être automatisée lorsque l'utilisation des mécanismes supports (branches, etc.) sont rendus obligatoires.

Sinon, la vérification doit être faite par un expert qui doit auditer les commits.
