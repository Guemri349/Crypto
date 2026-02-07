# Crypto & Marchés Financiers — Structure de projet

Ce dépôt fournit une **structure de travail** pour un projet centré sur la crypto et les marchés financiers.
Elle sert de point de départ pour organiser le code, les données, la documentation et les exemples.

## Pourquoi cette structure ?
- **Clarté** : séparer la logique crypto (blockchain, tokens, on-chain) de la logique marchés (prix, indices, FX, taux).
- **Évolutivité** : pouvoir ajouter des modules sans tout mélanger.
- **Pédagogie** : faciliter l’apprentissage pour un·e débutant·e.

## Arborescence
```
.
├── data/                # Jeux de données (bruts, nettoyés, cache API)
├── docs/                # Notes, glossaire, guides
├── examples/            # Exemples d’utilisation / notebooks / scripts
├── src/
│   ├── crypto/          # Modules liés à la crypto (on-chain, tokens, exchange)
│   ├── markets/         # Modules liés aux marchés (prix, volumes, macro)
│   └── shared/          # Utilitaires communs (dates, config, validation)
└── tests/               # Tests unitaires et d’intégration
```

## Prochaines étapes suggérées
1. Ajouter un **glossaire** et des notes de base dans `docs/`.
2. Créer un premier module dans `src/crypto/` (ex. récupération de prix via API).
3. Ajouter un exemple simple dans `examples/`.
4. Écrire un test minimal dans `tests/`.

## Repères pédagogiques (débutant·e)
- **Crypto** : blockchain, tokenomics, wallets, exchanges, on-chain vs off-chain.
- **Marchés financiers** : prix, volume, liquidité, volatilité, indicateurs macro.
- **Data pipeline** : ingestion → nettoyage → analyse → visualisation.

---
Si tu veux, je peux ensuite créer des **modules concrets** (API, calculs, backtests) ou un **glossaire**.
