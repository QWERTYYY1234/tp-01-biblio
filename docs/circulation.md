# Circulation de l'information : groupe [nom du groupe]

À compléter par le groupe en séance 1. Chaque section est rédigée et poussée par un membre différent.

## 1. Rôles
Rédigé par : @QWERTYYY1234

Dans notre groupe de trois, chacun est tour à tour auteur et relecteur. Nous sommes tous les trois mainteneurs : nous trions les issues ensemble et nous décidons du merge à deux au moins. L'auteur d'un changement ne le valide jamais seul.

## 2. Où circule chaque information
Rédigé par : @QWERTYYY1234

| Information | Qui la produit | Qui la valide | Où elle est stockée | Durée de vie |
|---|---|---|---|---|
| Code source | L'auteur du changement | Un autre membre relit la PR, le mainteneur merge | Git, dépôt GitHub | Toute la vie du projet |
| Bug signalé | Toute personne qui le constate | Mainteneur (tri, labels, fermeture) | Issue GitHub, modèle Signaler un bug | Jusqu'à sa résolution, puis archivée |
| Décision technique | Le groupe | Un autre membre, via une PR | docs/adr/ du dépôt, avec un lien depuis l'issue ou la PR | Tant que la décision reste valable |
| Documentation d'installation | L'auteur, via une PR | Un autre membre | README du dépôt | Toute la vie du projet |
| Question rapide entre membres | N'importe quel membre | Personne | Discord | Quelques heures |
| Compte rendu de réunion | Un membre à tour de rôle | Le groupe | Wiki GitHub du dépôt | Toute la durée du projet |
## 3. Règles de l'équipe
Rédigé par : @QWERTYYY1234

- Titre d'issue : ce qui se passe, et où. Pas de « urgent » dans le titre.
- Labels : bug, enhancement, question, securite ; l'urgence passe par un label de priorité.
- Tri : le mainteneur pose les labels et cherche les doublons, y compris dans les issues fermées.
- Assignation : une seule personne responsable par issue.
- À partir de la séance 2 : aucun push direct sur main, tout passe par une pull request relue.