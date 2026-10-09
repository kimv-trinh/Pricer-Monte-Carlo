# Pricing d'options par Monte-Carlo

Notebook de valorisation d'options par simulation de Monte-Carlo, en complément d'un pricer analytique (Black-Scholes) et d'un pricer par réseau de neurones. Un bloc de configuration en tête permet de pricer n'importe quel sous-jacent et n'importe quel produit (call ou put, toute moneyness : ITM, ATM, OTM).

## Dépendances

```bash
pip install numpy scipy matplotlib
```

## Utilisation

Ouvrir `Pricing_Monte_Carlo.ipynb` dans Jupyter et exécuter les cellules dans l'ordre. Le notebook est autonome (aucune donnée externe). Pour un nouveau cas, il suffit de modifier le bloc de configuration (Partie I) puis d'appeler la fonction `pricer`.

## Contenu

Options européennes et convergence, réduction de variance, Greeks par trois méthodes, options exotiques (asiatique, barrière), options américaines (Longstaff-Schwartz), fonction `pricer` unifiée, et validation sur tout le spectre de moneyness.

Réalisé par Kim TRINH.
