# Resolution-Algorithm
Ce projet est une implémentation en Python de l'algorithme de résolution pour la logique propositionnelle. L'algorithme de résolution est une méthode efficace pour déterminer la validité des formules propositionnelles.

La fonction negation prend en entrée une formule propositionnelle et renvoie sa négation.

La fonction convertir_formule prend en entrée une formule propositionnelle et renvoie une chaîne de caractères qui peut être utilisée par Sympy pour la convertir en une expression utilisable par l'algorithme.

La fonction obtenir_clauses prend en entrée une formule propositionnelle et renvoie un ensemble de clauses dans la forme normale conjonctive (CNF).

La fonction est_clause_vide vérifie si une clause est vide.

La fonction simplification prend en entrée deux clauses et renvoie leur résolvante, qui est une clause obtenue en appliquant la règle de simplification entre les deux clauses.

La fonction chercher_clauses_resolvantes prend en entrée un ensemble de clauses et renvoie l'ensemble des clauses résolvantes obtenues en appliquant la règle de résolution sur toutes les paires de clauses.

La fonction est_formule_valide prend en entrée une formule propositionnelle et renvoie True si la formule est valide et False sinon.

Pour utiliser le programme, il suffit de saisir une formule propositionnelle et d'appeler la fonction est_formule_valide avec cette formule en entrée. Le programme affichera La formule est valide. si la formule est valide et La formule n'est pas valide. sinon.

Exemple :

Entrez une formule propositionnelle : ~A v A La formule est valide.

Remarques :

Le programme ne supporte que les opérateurs logiques & (et), v (ou), ~ (non), -> (implication) et <=> (équivalence).
Les variables propositionnelles doivent être des lettres majuscules.
Les parenthèses sont obligatoires pour indiquer l'ordre des opérations.
Le programme utilise la bibliothèque Sympy pour la conversion de la formule en CNF.
