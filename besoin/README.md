Les besoins : 6 pratiques incontournables
========================================

Les besoins, c'est quoi ?
------------------------

Un **besoin** est une demande de la maîtrise d'ouvrage. Le besoin est rédigée par le propriétaire ou l'utilisateur du logiciel (ils savent ce qu'ils veulent avoir). Pour autant, le besoin est à destination des développeurs qui vont devoir les comprendre pour les réaliser.

Toutes les méthodes de génie logiciel demandent à ce que les besoins soient clairement exprimés. L'objectif étant que les développeurs comprennent les besoins et réalisent le logiciel qui y réponde.

C'est principalement lorsque les besoins sont mal exprimés que les projets logiciels échouent.
Il faut donc prendre une attention toute particulière à la rédaction des besoins.

Il existe différentes façons de rédiger un besoin selon la méthode suivie :

* Les méthodes mathématiques ou rigoureuses demandent à ce que les besoin soient des contraintes rédigées dans un formalisme formel. Cela peut être par exemple une formule de logique booléenne ou même une règle mathématique.
* Les méthodes par modélisation telles que UML proposent des langages adéquats pour rédiger les besoins. En UML, on peut par exemple utiliser les diagrammes de cas d'utilisation.
* Les méthodes agiles demandent à ce que les besoins soient rédigées en langage naturel sous forme de scénario utilisateur (*user story*). La rédaction d'un scénario peut suivre un template pré-défini (en tant que <...> je souhaite <...> afin de <...>).
* etc.

Si la rédaction des besoins est importante, il en va de même pour leur gestion. La gestion d'un besoin permet de suivre son évolution dans le temps. Un besoin passe généralement par plusieurs stades :

* en cours de rédaction, lorsque le besoin n'est pas encore pleinement exprimé.
* rédigé et en attente de qualification, lorsque le besoin est rédigé mais qu'il n'a pas été qualifié. La qualification permet de préciser le type du besoin : est-ce une demande de nouvelle fonctionnalité ? une évolution d'une fonctionnalité existante ? une correction de bug ? une optimisation des performances ? etc.
* qualifié et en attente de planification, lorsque le besoin est validé mais que sa réalisation n'est pas encore planifiée. La planification permet de placer le besoin sur une feuille de route et ainsi de savoir quand il sera réalisé.
* planifié, on sait alors quand le besoin sera réalisée.
* testable, lorsque le besoin dispose d'un [test](../test) qui permettra, une fois le besoin réalisé, de vérifier sa réalisation.
* en cours de réalisation, c'est lorsque que les tâches permettant de réaliser le besoin ont démarré.
* réalisé, lorsque toutes les tâches permettant de réaliser le besoin ont été faites.
* testé, lorsque le besoin est réalisé et qu'il a été testé. En principe on considère que le besoin est testé quand le test a été passé (positif)
* livré ou déployé, lorsque le besoin est accessible par les utilisateurs. Lorsqu'il a été intégré dans une [release](../release)

Qu'est-ce que la qualité des besoins ?
-------------------------------------

La qualité du logiciel repose grandement sur la qualité des besoins. Si les besoins ne sont pas de bonne qualité on dit qu'il y a plus de 80% de chance que le projet n'aboutisse pas.

La qualité des besoins se retrouve dans la rédaction et dans le suivi. Il faut en effet que les besoins soient parfaitement rédigés mais aussi que leur gestion soit précise.

Liste des bonnes pratiques :
----------------------------

### Rédaction

* [identifier les besoins de manière unique](./identifier.md)
* [préciser les besoins](./preciser.md)
* [homogénéiser les besoins](./homogeneiser.md)

### Gestion des modifications

* [qualifier le type des besoins, leur importance et leur difficulté](./qualifier.md)
* [planifier les besoins dans le temps](./planifier.md)
* [clore un besoin](./fermer.md)
