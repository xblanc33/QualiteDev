Tester Les Issues (test de validation)
======================================

Chaque [issue](../issue) doit disposer d'un test de validation qui va décrire précisément le résultat attendu et surtout comment on va pouvoir le vérifier.

En effet, du point de vue de l'utilisateur, un logiciel est un peu comme une boite noire avec qui on peut interagir pour bénéficier de services.

Un test de validation va s'assurer que cette vision de boite noire et de services correspond bien à ce qui est décrit par les issues. Un test de validation va donc simuler le comportement d'un utilisateur et va vérifier que le comportement du logiciel est bien conforme à ce qui est attendu.

Ne pas disposer de test de validation laisse les développeurs dans l'interprétation. Sans test, ils n'ont pas de définition précise de ce qu'ils doivent faire et surtout pas de moyen leur permettant de vérifier qu'ils ont bien réalisé les issues.

Sans test, un développeur n'a pas d'autre choix que de décider lui-même du niveau attendu. Une fois qu'il pense avoir terminé son travail, il devra attendre que le propriétaire vérifie sa réalisation. C'est évidemment contre productif et source de nombreux soucis.

Objectif
--------

Cette pratique vise à ce que chaque issue dispose de tests de validation (un ou plusieurs). Un test d'issue est souvent appelé un test d'acceptabilité. Il précise le niveau d'exigence permettant d'accepter la réalisation de l'issue.

Disposant de ce test, le développeur pourra réaliser son travail et vérifier qu'il a atteint le niveau attendu par le test.

Les tests de validation dépendent fortement du type d'issue. Quand il s'agit de réalisation de nouvelle fonctionnalité ou d'évolution de fonctionnalité existante, le test peut correspondre à un test End To End (E2E). Ce genre de test précise le comportement d'un utilisateur du logiciel et pose des contraintes quant aux résultats attendus (visibles par l'utilisateur). Si au contraire, l'issue est une correction de bug, le test peut être un test de non-régression qui va vérifier que le bug a bien disparu.

Contrôle
--------

Le contrôle de cette pratique ne peut se faire que par un audit.

L'audit va vérifier que chaque issue dispose de son test. Une analyse approfondie du test permet de s'assurer que celui-ci joue son rôle et permet ainsi au développeur de savoir s'il a bien réalisé l'issue.
