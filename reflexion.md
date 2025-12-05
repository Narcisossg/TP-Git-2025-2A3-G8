On a tous fait des modifications sur nos branches, on a fusionné nos branches et résolu les conflits puis on est revenu à la première modif.


git fetch télécharge le contenu du dépôt distant sans changer l'état du dépôt local.
git pull télécharge le contenu du dépôt distant et change directement l'état du dépôt local pour que l'état des deux dépôt correspondent.

On veut faire git fetch quand on ne veut pas obtenir le contenu du dépôt distant sans avoir de conflit. (on est entrain de modifier quelque chose en local)
Alors que git pull fait un git fetch et un git merge ce qui peut créer des conflits.



git revert, annule le dernier commit en en créant un autre commit inverse par dessus.
git reset déplace le HEAD pour réécrire l'historique des commit, donc il supprime et remplace.

si on a un depot partagé c'est dangereux de faire git reset par soucis de confidencialité


