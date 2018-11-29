Documentation utilisateur
=========================

Tout logiciel est développé pour être utilisé, et parfois l'utilisateur a besoin d'une documentation.

La documentation utilisateur a pour principal objectif d'aider l'utilisateur à utiliser le logiciel. Pour autant, il faut bien avoir conscience que la plupart des utilisateurs ne lisent pas la documentation avant de se servir du logiciel. Ils utilisent la documentation quand ils n'arrivent pas à faire ce qu'ils voudraient faire.

La documentation utilisateur est obligatoire mais elle doit cibler le bon besoin de l'utilisateur.

Une documentation est obligatoire car sans elle les utilisateurs n'ont aucun moyen de comprendre comment utiliser le logiciel. Par exemple, si le logiciel s'utilise via la ligne de commande, comment voulez vous que l'utilisateur connaissent toutes les options sans aide (--help) ? En lisant le code ?

Une documentation doit cibler le besoin de l'utilisateur. Il n'y a en effet aucun intérêt à détailler toutes les fonctionnalités du logiciel alors que l'UX les rend accessible du premier coup d'oeil. Par exemple, si le logiciel nécessite la création d'un compte en demandant classiquement un login/password, pensez-vous que l'utilisateur va vraiment lire la documentation pour passer cette étape ? Par contre, si le logiciel peut prendre en entrée des formules (comme excel par exemple), il faut que la documentation explique comment les construire.

Objectif
--------

La rédaction d'une documentation utilisateur est un exercice difficile qui nécessite de trouver le bon niveau de détails.

Une documentation utilisateur doit **au minima expliquer les informations nécessaires** pour utliser le logiciel (options classiquement utilisées, parcours nominal, etc.). Pour certains logiciels, une telle documentation peut être très légère, ce qui est une raison de plus pour la faire correctement.

Idéalement, une documentation utilisateur doit donner **tous les détails des fonctionnalités avancées** du logicel (toutes les options et toutes leurs significations). Sinon, il y a de fortes chances que ces fonctionnalités ne soient jamais utilisées.

Contrôle
--------

Vérifier la documentation du code source ne peut se faire que par l'audit d'un expert.

L'expert va vérfier que la documentation utilisateur donne bien les informations minimales.

Enfin, l'expert peut vérifier que certaines fonctions avancées sont bien documentées.