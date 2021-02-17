CAS GÉNÉRAL
===========
Trois niveaux d'acteurs sont à considérer au sein du système: un visiteur, un administrateur et un super administrateur. La hiérarchisation permet que chaque niveau ait accès aux droits du niveau immédiatement inférieur. De ce fait, un super administrateur sera également un administrateur et un visiteur en plus de son niveau direct.
Pour commencer, le visiteur aura des droits d'accès très restreints:
-   Parcourir le webmap: Le visiteur pourra voir l'ensemble des informations géotechniques disponibles sur la carte.
-   Changer de fond de carte: Afin de mieux illustrer le contexte marquant l'intérêt du visiteur, une variété de fonds de carte sera accessible sur le site. Ainsi, l'utilisateur pourra puiser dans le champs de choix qui lui seront proposés.
-   Visionner les données enregistrées: En cliquant sur une légende précise, le visiteur pourra voir les données qui ont été préalablement enregistrées dans la base de données.
-   Effectuer des recherches: Deux options s'offrent aux utilisateurs. Ces derniers pourront afficher tous les résultats au cours de la rechercherche, ou encore ils pourront se fixer des filtres capables de mieux limiter les plages des résultats.
-   Accéder aux résultats d'un test: Une fois les résultats obtenus, le visiteur pourra soit simplement les afficher, soit les imprimer.

De son côté, l'administrateur s'occupe de la gestion des informations au sein de la base de données. En plus des droits de visiteur, ce type d'utilisateur peut:
-   Ajouter des informations géotechniques: L'admin pourra ajouter des informations dans la bdd, qui seront reflétées sur la carte. 
-   Modifier les informations qu'il avait préalablement enregistrées: Il ne pourra modifier que les informations qu'il avait lui-même ajoutées.
-   Supprimer les informations qu'il avait préalablement enregistrées: Tout comme il en est pour la modification, il ne pourra supprimer que les informations qu'il avait lui-même ajoutées.
-   Ajouter un fond de carte
-   Modifier un fond de carte
-   Supprimer un fond de carte
Évidemment, aucune de ces actions ne saura avoir lieu tant que l'administrateur ne se sera pas authentifié.

En dernier lieu, le super administrateur jouera surtout un rôle de gestionnaire en ressources humaines. Une fois authentifié, en plus des droits d'accès d'un simple administrateur, cet utiliateur pourra:
-   Ajouter des utilisateurs
-   Modifier les utilisateurs
-   Afficher les informations relatives aux différents utilisateurs, pouvant ainsi retracer toutes les actions posées par un utilisateur du système.
-   Supprimer ou désactiver un utilisateur: La différence se fait remarquer par le fait que le super admin peut supprimer complètement un utilisateur ainsi que toutes les informations y relatives ou simplement désactiver le compte d'un utilisateur sans, pour autant, éliminer ses données.