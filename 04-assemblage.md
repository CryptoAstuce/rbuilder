# 04 — Assemblage du bloc

La construction part d’un événement de payload envoyé par le client de consensus. Elle combine état Reth, transactions, bundles, contraintes de gas et règles de validité avant de produire un payload.

Plusieurs algorithmes peuvent être branchés : le dépôt expose des traits et des sinks pour remplacer la politique de construction. L’assemblage reste soumis à la validation du nœud d’exécution et du relay.

[Chapitre suivant : relays →](05-relays.md)
