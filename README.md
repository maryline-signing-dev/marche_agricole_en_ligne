# MAVUNO — Marché agricole en ligne

Application  Flask + SQLite destinée à mettre en relation des producteurs de la Menoua et du Moungo avec des acheteurs. Elle comprend le catalogue public, les commandes, les espaces producteur et administration, les prix du marché et les statistiques.

## 1. Fonctionnalités

- Catalogue public des annonces actives, filtres par produit et lieu, tri par prix.
- Détail d’annonce et formulaire de commande avec montant estimé calculé en direct.
- Validation serveur du stock et du montant ; le prix transmis par le navigateur n’est jamais utilisé comme source de vérité.
- Espace producteur : connexion, création/modification/désactivation de ses annonces, traitement des commandes reçues.
- Espace administrateur distinct : gestion des  produits et des comptes producteurs.
- Statistiques : prix moyen par produit et semaine, volume livré par produit, producteurs les plus actifs, taux d’acceptation des commandes.

## 2. Prérequis

- Python 3.11 ou plus récent 
- `pip` et un environnement virtuel.
- Aucune base externe n’est nécessaire : SQLite est inclus avec Python.