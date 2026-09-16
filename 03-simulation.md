# 03 — Simulation et sélection

L’algorithme inclus trie les ordres selon prix du gaz effectif ou profit total, puis tente de les exécuter. Une tentative peut échouer : la sélection doit donc conserver un état de travail isolé et poursuivre avec les candidats compatibles.

Les outils debug-order-input et debug-order-sim rendent visibles les entrées et la simulation. Le backtesting rejoue des données historiques pour comparer une stratégie à un bloc réellement publié.

[Chapitre suivant : assemblage →](04-assemblage.md)
