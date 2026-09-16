# 02 — Ordreflow, transactions et bundles

Les entrées proviennent du mempool Reth, de JSON-RPC et de bundles. Le builder doit gérer nonces, dépendances et transactions déjà présentes afin d’éviter conflits et duplications.

Le champ reverting_tx_hashes permet de retirer certains bundles lorsque leurs transactions ciblées sont déjà incluses. Cette logique protège la cohérence de l’ensemble des ordres.

[Chapitre suivant : simulation →](03-simulation.md)
