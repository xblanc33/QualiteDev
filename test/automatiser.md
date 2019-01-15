Automatiser l'exécution des tests
=================================

Lorsqu'on exécute les tests c'est pour s'assurer qu'on ne trouve pas de nouveau bug. L'objectif est de vérifier la qualité du logiciel avant que l'utilisateur ne l'utilise.

Rendre l'exécution des tests automatisables permet de tester souvent et sans difficulté. Cela permet d'intégrer l'exécution des tests dans la production du logiciel.

On peut même rendre l'exécution des tests bloquante. C'est à dire par exemple rendre impossible la production d'une [release](../release) si certains tests ne passent pas.

Lorsque l'exécution des tests n'est pas automatisée, les développeurs doivent alors se débrouiller seuls pour exécuter les tests. Cela leur demande du temps. De plus, cela leur demande d'être responsable et de savoir quels tests exécuter et quand, ce qui est source d'erreurs.

Objectif
--------

Automatiser l'exécution des tests nécessite de mettre en place une chaîne outillée. Plusieurs outils proposent des solutions plus qu'intéressantes pour répondre à cet objectif.

Bien souvent, il faut choisir un framework de rédaction et d'exécution des tests (tel que JUnit pour Java) et intégrer ce framework dans la chaîne de production (grâce à Jenkins ou Travis par exemple).

Contrôle
--------

Vérifier l'automatisation des tests ne peut se faire que par l'audit d'un expert.

L'expert va devoir vérifier qu'une chaîne de production est en place et qu'elle intègre l'exécution des tests. Il va aussi vérfier que les tests sont bien rédigés en conformité avec le framework de test choisi.
