Mettre à jour les tests
========================

Les tests (unitaire ou de validation) ciblent tous une partie du logiciel. Or, cette partie va certainement évoluer au fil du temps, nécessitant irrémédiablement de se poser la question de l'évolution des tests.

Un test doit évoluer au même rythme que le logiciel !

Les tests doivent rester au contact de leur cible. De fait, à chaque évolution du logiciel, il faut s'assurer que les tests sont toujours à jour.

Si un test n'évolue pas alors que la partie du logiciel qu'il teste évolue, il y a de forte chance qu'il soit moins efficace. Attention, cela ne veut pas dire qu'un test doit forcément évoluer si le code qu'il cible évolue. Il y a des évolutions du code qui ne nécessitent pas d'évolution des tests. Néanmoins, il faut bien faire attention lors des évolutions du code à vérifier que les tests n'ont pas besoin d'évoluer eux aussi.

Lorsqu'aucun contrôle n'est fait quant à la mise à jour des tests, ceux-ci deviennent irrémédiablement obsolètes. In fine, le logiciel est mal testé et les bugs apparaissent !  

Objectif
--------

Il faut mettre à jour les tests quand les changements dans le code le nécessite.

Cela veut dire qu'à chaque fois qu'une évolution est apportée au code, il faut s'assurer de l'évolution des tests.

L'approche Test Driven Development ou même Test First va plus loin et préconise de réaliser la création/modification des tests avant de faire les évolutions du code. Ainsi, on s'assure que les tests sont toujours à jour.

Contrôle
--------

La qualité de la mise à jour des tests ne peut se faire que par l'audit d'un expert.

L'expert va auditer les tests et vérifier qu'ils sont bien à jour vis à vis du code qu'ils testent.

A la limite, on peut automatiser la levée d'indices permettant de penser que des tests ne sont plus à jour. Cela peut se faire en regardant la couverture pour les tests unitaires. En effet, si la couverture baisse après une évolution de code, il est possible que cela vienne des tests qui ne seraient plus à jour. On peut aussi regarder les dates des évolutions apportées sur le code et sur les tests. Si on voit que les tests n'évoluent peu, comparaitivement au code, cela peut être un indice sur la mauvaise mise à jour des tests.
