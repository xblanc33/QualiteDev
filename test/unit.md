Tester Unitairement
===================

Quelle que soit l'architecture du logiciel et quelles que soient les technologies employées, il y a toujours un niveau d'unité élémentaire (minimale) dans la structuration de votre code. Cela peut être la classe si votre code suit le paradigme objet ou la fonction s'il suit le paradigme fonctionnel.

L'unité élémentaire c'est l'entité la plus petite qu'il est possible de tester pour s'assurer qu'il n'y a pas de bug. On peut tester une classe ou une méthode, pas une ligne de code et encore moins une instruction!

Un test unitaire (Unit Test) a pour objectif de révéler les bugs dans une unité élémentaire.
Tester unitairement votre code revient à tester toutes les unités dans l'objectif de révéler les erreurs qu'elles contiennent.

Lorsqu'un test unitaire révéle un bug, c'est que la source du bug se trouve dans l'unité élémentaire. Il reste alors à diagnostiquer la raison du bug et à le corriger.

Les tests unitaires permettent de cloisonner les tests et de les affecter à des petites parties du code. Sans test unitaire, il est beaucoup plus difficile de savoir d'où viennent les bugs, et donc très difficile de les corriger.

Objectif
--------

La rédaction de test unitaire n'est pas simple. Un test unitaire de qualité va chercher à révéler un bug. Il va donc bousculer le code pour trouver les failles et ainsi révéler les bugs.

Un test unitaire ne cherche pas à montrer que le code fonctionne, il cherche à trouver les failles ! Un test unitaire va donc chercher évidemment à vérifier le comportement nominal, mais il va aussi chercher les cas critiques ("aux limites", mal défini, pré-requis non vérifé), là où se cachent très souvent les bugs.

Un test unitaire doit tester l'unité qu'il cible, et uniquement celle-ci. Si cette unité exploite d'autres unités, il faut que le test s'en isole en utilisant des bouchons par exemple.

Enfin, les tests unitaires de qualité ont pour objectif de tester tout le code, l'intégralité. Pour ce faire, la notion de couverture de code est intéressante car elle permet de mesurer la proportion de lignes de code courvertes par les tests.

Contrôle
--------

La qualité des tests unitaires ne peut se faire que par l'audit d'un expert.

L'expert, en auditant les tests unitaires, va vérifier que ceux-ci testent bien les limites du code (et pas les comportements nominaux) et que le test cible uniquement l'unité.

La notion de couverture par contre peut être contrôlée automatiquement car il existe plusieurs outils qui effectuent cette mesure automatiquement.
