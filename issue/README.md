Les issues : 5 pratiques incontournables
========================================

Les issues, c'est quoi ?
------------------------

Une **issue** est l'expression d'un besoin particulier. L'issue est rédigée par le propriétaire ou l'utlisateur du logiciel (ils savent ce qu'ils veulent avoir). Pour autant, l'issue est à destination des développeurs qui vont devoir les comprendre pour les réaliser.

Toutes les méthodes de génie logiciel demandent à ce que les issues soient clairement exprimées. L'objectif étant que les développeurs comprennent les besoins et réalisent le logiciel qui y réponde.

C'est principalement lorsque les besoins sont mal exprimés que les projets logiciels échouent.
Il faut donc prendre une attention toute particulière à la rédaction des issues.

Il existe différentes façons de rédiger une issue selon la méthode suivie :

* Les méthodes mathématiques ou rigoureuses demandent à ce que les issues soient des contraintes rédigées dans un formalisme formel. Cela peut être par exemple une formule de logique booléenne ou même une règle mathématique.
* Les méthodes par modélisation telles que UML proposent des langages adéquats pour rédigier les issues. En UML, on peut par exemple utiliser les diagrammes de cas d'utilisation.
* Les méthodes agiles demandent à ce que les issues soient rédigées en langage naturel sous forme de scénario utilisateur (user story). La rédaction d'un scénario peut suivre un template pré-défini (en tant que <...> je souhaite <...> afin de <...>).
* etc.

Si la rédaction des issues est importante, il en va de même pour leur gestion. La gestion d'une issue permet de suivre son évolution dans le temps. Une issue passe généralement par plusieurs stades :

* en cours de rédaction, lorsque l'issue n'est pas encore pleinement rédigée.
* rédigée et en attente de qualification, lorsque l'issue est rédigée mais qu'elle n'a pas été qualifiée. La qualification permet de préciser le type de l'issue : est-ce une demande de nouvelle fonctionnalité ? une évolution d'une fonctionnalité existante ? une correction de bug ? une optimisation des performances ? etc.
* qualifiée et en attente de planification, lorsque l'issue est validée mais que sa réalisation n'est pas encore planifiée. La planification permet de placer l'issue sur une feuille de route et ainsi de savoir quand elle sera réalisée.
* planifiée, on sait alors quand l'issue sera réalisée.
* testable, lorsque l'issue dispose d'un [test](../test) qui permettra, une fois l'issue réalisée, de vérifier sa réalisation.
* en cours de réalisation, c'est lorsque que les tâches permettant de réaliser l'issue ont démarré.
* réalisée, lorsque toutes les tâches permettant de réaliser l'issue ont été faites.
* testée, lorsque l'issue est réalisée et qu'elle a été testée. En principe on considère que l'issue est testée quand le test a été passé (positif)
* livrée ou déployée, lorsque l'issue est accessible par les utilisateurs. Lorsqu'elle a été intégrée dans une [release](../release)

Qu'est-ce que la qualité des issues ?
-------------------------------------

La qualité du logiciel repose grandement sur la qualité des issues. Si les issues ne sont pas de bonne qualité on dit qu'il y a plus de 80% de chance que le projet n'aboutisse pas.

La qualité de issue se retrouve dans la rédaction et dans le suivi. Il faut en effet que les issues soient parfaitement rédigées mais aussi que leur gestion soit précise.

Liste des bonnes pratiques :
----------------------------

### Rédaction

* [identifier les issues de manière unique](./identifier.md)
* [préciser les issues](./preciser.md)
* [homogénéiser les issues](./homogeneiser.md)

### Gestion des modifications

* [qualifier le type des issues, leur importance et leur difficulté](./qualifier.md)
* [planifier les issues dans le temps](./planifier.md)
* [fermer une issue](./fermer.md)
