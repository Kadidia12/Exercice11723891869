Git Worktrees

 Un worktree est un répertoire de travail séparé qui vous permet de travailler sur une branche différente tout en conservant le répertoire principal intact.
Création d’un Worktree
Utilisez la commande suivante pour créer un worktree pour une branche spécifique :


Exemple :

bash
Copier le code
git worktree add .
Gestion des Worktrees
Supprimer un Worktree : Utilisez la commande suivante pour supprimer un worktree sans affecter la branche :

bash
Copier le code
git worktree remove <path>
Exemple :

bash
Copier le code
git worktree remove ../feature-xyz
Lister les Worktrees Actifs : Utilisez la commande suivante pour voir tous les worktrees associés à votre dépôt :

bash
Copier le code

git worktree list
Les git worktrees permettent de gérer plusieurs branches simultanément en utilisant des répertoires de travail distincts, améliorant ainsi la productivité et l'organisation.

