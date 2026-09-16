# 05 — Relays et boucle live

En mode live, rbuilder soumet les blocs aux relays MEV-Boost. La configuration décrit endpoints, priorités, source d’état, IPC du mempool et événements de payload.

Le binaire test-relay reproduit l’API de relay et valide localement les blocs reçus. Cette frontière permet de tester un builder sans envoyer de blocs à un relay de production.

[Chapitre suivant : observation →](06-observation.md)
