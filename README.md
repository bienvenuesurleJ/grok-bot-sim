# Grok Bot — bot de trading en simulation

Application autonome (un seul fichier `index.html`) : un bot de trading à 6 agents IA qui collaborent, en **simulation** uniquement.

- Données de marché **réelles** et publiques (API DexScreener, lecture seule, paires Solana).
- Portefeuille **fictif** : aucun wallet, aucune clé, aucun ordre réel.
- Les gains et pertes viennent uniquement des vrais mouvements de prix, frais DEX, frais réseau et slippage compris.
- Si le flux de données se coupe, la session se met en pause au lieu d'afficher de faux chiffres.

Ouvre `index.html` dans Chrome, Safari ou Firefox, puis appuie sur **Démarrer**.
Raccourcis : Espace = démarrer/pause · R = réglages · Échap = fermer · 1–4 = onglets du journal.
