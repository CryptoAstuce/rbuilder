# 01 — Le rôle de rbuilder

rbuilder est un block builder Ethereum écrit en Rust pour MEV-Boost. Il reçoit ordreflow, transactions et bundles, puis cherche un bloc rentable et valide à proposer aux relays.

Le dépôt organise le binaire live, le backtesting, les algorithmes de construction et le relais de test. Cette séparation permet d’étudier la construction sans confondre recherche et production.

[Chapitre suivant : ordreflow →](02-ordreflow.md)
