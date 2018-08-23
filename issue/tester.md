Tester les issues
=================

Les issues décrivent ce que veut voir réaliser le propriétaire du logiciel. Il faut qu'elles soient précises afin que les développeurs comprennent le résultat attendu.

Afin de s'assurer que leur réalisation sera bien effecuée, chaque issue doit disposer d'un test qui va décrire plus précisément le résulat attendu et surtout comment on va pouvoir le vérifier.

Ne pas disposer de test laisse les développeurs dans l'interprétation. Sans test ils n'ont pas de définition précise de ce qu'ils doivent faire et surtout pas de moyen leur permettant de vérifier qu'ils ont bien terminé leur travail.

Sans test, un développeur n'a pas d'autre choix que de décider lui-même du niveau attendu. C'est à lui de préciser le **definition of done**. Une fois qu'il pense avoir terminé son travail, il devra attendre que le propriétaire vérifie sa réalisation. C'est évidement contre productif et source de nombreux soucis.

Objectif
--------

Cette pratique vise à ce que chaque issue dispose de tests (un ou plusieurs). Un test d'issue est souvent appelé un test d'acceptabilité. Il précise le niveau d'exigence permettant d'accepter la réalisation de l'issue.

Disposant de ce test, le développeur pourra réaliser son travail et vérifier qu'il a atteind le niveau attendu par le test.

Les tests d'issue dépedent fortement du type d'issue. Quand il s'agit de réalisation de nouvelle fonctionnalité ou d'évolution de fonctionnalité existante, le test peut correspondre à un test End To End (E2E). Ce genre de test précise le comportement d'un utilisateur du logiciel et pose des contraintes quant aux résultats attendus (visibles par l'utilistaeur). Si au contraire, l'issue est une correciton de bug, le test peut être un test de non-regression qui va vérifier que le bug a bien disparu.

Contrôle
--------

Le contrôle de cette pratique ne peut se faire que par un audit.

L'audit va vérifier que chaque issue dispose de son test. Une analyse approfondie du tests permet de s'assurer que le test joue son rôle et permet ainsi au développeur de savoi s'il a bien réalisé l'issue.
