Le test : 6 pratiques incontournables
=====================================

Le test, c'est quoi ?
---------------------

Un **test** est une suite d'actions que le système va effectuer pour rendre un résultat (**résultat obtenu**) qu'on espère conforme au **résultat attendu**.

Si le **résultat obtenu (RO)** est différent du **résultat attendu (RA)**, c'est qu'il y a une erreur. Le principe du test est de révéler les erreurs dans un logiciel.

Un bon test est donc un test qui révèle une erreur avant que le logiciel ne soit en production, permettant ainsi la correction de l'erreur avant que l'utilisateur ne s'en aperçoive.

Pour autant, certains tests permettent aussi de vérifier une idée, une conception, un usage. L'objet de ces tests est moins de révéler des erreurs que de s'assurer que le logiciel fonctionne comme on voudrait qu'il fonctionne.

On peut effectuer des tests à différents niveaux sur le logiciel. Pour autant, il y a classiquement trois principaux niveaux de test :

* Les tests unitaires ciblent des morceaux du code source (fonction, classe, etc). Leur objectif étant de révéler une erreur dans dans morceau du code source.
* Les tests d'intégration ciblent les communications entre des modules du logiciel. Leur objectif étant alors de révéler une erreur lors de la communication entre les modules testés.
* Enfin les tests de validation ciblent des fonctionnalités réalisées par le logiciel pour l'utilisateur. Leur objectif étant alors de révéler que la fonctionnalité se déroule sans erreur quelque soit le comportement de l'utilisateur.

En plus de ces tests dits fonctionnels, car ils ciblent le comportement de l'application, il est aussi possible de tester les aspects non-fonctionnels d'un logiciel tels que la performance par exemple.

Qu'est-ce que la qualité du test ?
----------------------------------

Un logiciel de qualité doit être testé, c'est une évidence.

Sans test, il y a fort à parier que le logiciel ne s'exécute pas comme on le voudrait et qu'il contienne de nombreux bugs.

Des trois niveaux (unitaire, intégration, validation), nous privilégions les niveaux :

* unitaire (**Unit Test**)
* validation (**Validation Test** ou même parfois **E2E Test**)

Le niveau intégration est plus complexe à mettre en oeuvre et ne peut pas entrer dans une pratique incontournable.

Un logiciel bien testé doit donc avoir :

* Des tests unitaires. Pour mesurer la qualité des tests unitaires, on utilise souvent le concept de couverture du nombre de lignes de code. On peut en effet mesurer combien de lignes de code sont ciblées par au moins un test unitaire. Ainsi, on peut savoir le pourcentage de lignes couvertes. Par exemple, un taux de couverture de 20% signifie que seule une ligne sur cinq du logiciel est testée. C'est peu. On privilégie bien souvent un taux minimal de 80%.
* Des tests de validation (ou E2E). Pour mesurer la qualité des tests de validation, il faut les rapprocher des [tests des issues](validation.md). En effet, les tests de validation doivent s'assurer que toutes les issues ont bien été réalisées comme on le souhaitait.

Sans ces tests, cela veut dire qu'aucun effort n'a été fait pour s'assurer que le logiciel ne contient pas de bug et qu'il est conforme aux besoins exprimés.

Enfin, un logiciel bien testé doit suivre l'exécution des tests. Il faut savoir à tout moment quels tests ont été réalisés et quel est le dernier résultat des tests. Sans cette connaissance, il est impossible de savoir quand et dans quelle mesure le logiciel a été testé.

De fait, il est aussi important d'automatiser au maximum l'exécution des tests pour pouvoir les exécuter aussi souvent que possible, et sans aucune difficulté.

Liste des bonnes pratiques :
----------------------------

### Rédaction et syntaxique

* [tester unitairement](unit.md)
* [tester les issues](validation.md)
* [tester contre les régressions](regression.md)

### Gestion des modifications

* [mettre à jour](update.md)
* [suivre les résultats des tests](suivre.md)
* [automatiser l'exécution des tests](automatiser.md)
