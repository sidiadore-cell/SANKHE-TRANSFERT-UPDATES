# Liste de contrôle avant publication

- [ ] Compiler la version Windows depuis le code source validé.
- [ ] Vérifier le lancement, les opérations et les rapports.
- [ ] Créer une copie isolée de la base SQLite de test ; ne jamais tester sur la base de production.
- [ ] Comparer les soldes Wave, Orange Money et espèces avant/après mise à jour.
- [ ] Vérifier les dettes ouvertes, remboursements, clients, historiques et opérations annulées.
- [ ] Vérifier qu'une mise à jour échouée restaure les fichiers applicatifs précédents.
- [ ] Confirmer que les données utilisateur sont hors du dossier remplacé.
- [ ] Créer un paquet qui ne contient aucune base de données ni secret.
- [ ] Publier le paquet dans une GitHub Release versionnée.
- [ ] Calculer le SHA-256 du paquet publié et le reporter dans le manifeste.
- [ ] Ajouter une signature numérique vérifiable par le programme de mise à jour.
- [ ] Tester téléchargement, vérification, installation et retour arrière sur un PC de test.
- [ ] Activer `updateAvailable` uniquement après validation complète.
