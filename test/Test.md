Recueil de bonnes pratiques pour le test
===============================================

Le test, c'est quoi ?
----------------------------

Un test cherche à révéler une erreur dans un logiciel. 
Un bon test est donc un test qui révèle une erreur avant que le logiciel ne soit en production, permettant ainsi la correction de l'erreur avant que l'utilisateur ne s'en apperçoive.

Il y a trois principaux types de test : Les tests unitaires, les tests d'intégration et les tests de validation : 
* Les tests unitaires ciblent des morceaux du code source (fonction, classe, etc). Leur objectif étant de révéler une erreur dans dans morceau du code source.
* Les tests d'intégration ciblent les communications entre des modules du logiciel. Leur objectif étant alors de révéler une erreur dans lors de la communication entre les modules testés.
* Enfin les tests de validation ciblent des fonctionnalités réalisées par le logiciel pour l'utilisateur. Leur objectif étant alors de révéler que la fonctionnalité se déroule sans erreur quelque soit le comportement de l'utilisateur.

En plus de ces tests dit fonctionnels car ils ciblent le comportement de l'application, il est aussi possible de tester les aspects non-fonctionnels d'un logiciel tels que la performance par exemple.

Qu'est-ce que la qualité du test ?
----------------------------------

La couverture est l'aspect principal de la qualité d'un test.
Par couverture on entent que le test couvre tous les comportements possibles de l'élément testé.
Celle-ci se mesure différemment selon le type de test.

Liste des bonnes pratiques :
----------------------------

### Gestion des modifications
* _[Versionner les tests](./pratiques/Test-Modif-1-versioner.md)_
* _[Contrôler les modifications des tests](./pratiques/Test-Modif-2-modifications.md)_
* _[Suivre les résultats des tests](./pratiques/Test-Modif-3-suivie.md)_

### Rédaction et syntaxique

* _[Couverture des tests unitaires](./pratiques/Test-Redac-1-tu.md)_
* _[Couverture des tests d'intégration](./pratiques/Test-Redac-2-ti.md)_
* _[Couverture des tests de validation](./pratiques/Test-Redac-3-tv.md)_
* _[Couverture des tests non-fonctionnels](./pratiques/Test-Redac-3-tnf.md)_

### Architecture et Conception
* _[Organiser les tests](./pratiques/Test-Archi-1-organiser.md)_
* _[Concevoir un logiciel testable](./pratiques/Test-Archi-2-testable.md)_
* _[Tester la non-régression](./pratiques/Test-Archi-3-non-regression.md)_

