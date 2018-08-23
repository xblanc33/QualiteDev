Homogénéiser
============

Les besoins d'un logiciel sont exprimés par ses issues. Il n'est pas rare qu'un nouveau projet soit constitué d'une bonne cinquantaine d'issues (voir même beaucoup plus pour les gros projets).

De fait, les issues doivent être relativement homogènes en terme de couverture des besoins. En d'autres mots, chaque issue doit couvrir à peu près la même proportion de besoins.

Si les issues ne sont pas homogènes cela veut donc dire qu'il y a des grosses issues et des petites issues. Cela va créer un déséquilibre dans la gestion des issues car irrémédiablement les grosses issues vont demander beaucoup plus d'énergie que les toutes petites.

Objectif
--------

Il faut cibler la granularité permettant de rédiger des issues homogènes. Ce niveau de granularité permet de savoir à quel niveau de décomposition des besoins correspond une issue.

En effet, les besoins sont bien souvent décomposables en sous besoins. On peut alors considérer au moins deux alternatives complètement opposées pour définir les issues leur correpsondant :

* une seule issue qui traite le besoin très général
* une issue par sous-besoin.

Par exemple, en considérant un logiciel qui gère des contacts personnels (nom, prénom, tel, adresse mail), on aurait alors ces deux alternatives :

* gérer l'ajout, la modification, la suppression de contacts personnels (nom, prénom, tel, adresse mail)

ou:

* gérer l'ajout d'un contact personnel (nom, prénom, tel, adresse mail)
* modifier un contact personnel existant
* supprimer un contact personnel existant

Sur ce simple exemple, on voit qu'on peut avoir soit 1 issue ou soit 3 pour un besoin. Mais quel est la meilleure alternative ?

L'objectif de l'homogénéisation des issues permet de répondre a cette question en regardant l'intégralité des issues et en choisissant un même niveau de granularité.

C'est en effet en regardant l'intégralité des issues qu'on arrive à voir si les issues sont homogènes. Si certaines issues sont trop grosses (trop générale) ou d'autres trop petites (trop centrée sur un sous-besoin particulier), c'est que les issues ne sont pas homogènes. 

Il faut alors rendre l'ensemble des issues homogènes.

Contrôle
--------

Vérifier que les issues sont homogènes ne peut se faire que par l'audit d'un expert.

L'expert, en auditant les issues, va mesurer l'homogénéité de l'ensemble des issues.