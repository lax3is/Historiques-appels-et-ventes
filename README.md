# Historique de appels et ventes - Extension Odoo

Cette extension Tampermonkey améliore l'interface d'Odoo en ajoutant des fonctionnalités pour visualiser l'historique des tickets et des ventes.

## Fonctionnalités

- **Historique des tickets** : Affiche l'historique complet des tickets d'un client
- **Produits du client** : Liste tous les produits associés au client
- **Thème clair/sombre** : Support du mode sombre et clair
- **Filtres** : Possibilité de filtrer les tickets par équipe et de rechercher dans l'historique
- **Copie d'URL** : Permet de partager facilement la vue des produits

## Installation

1. Installez l'extension [Tampermonkey](https://www.tampermonkey.net/) dans votre navigateur
2. Cliquez sur le lien suivant pour installer le script : [Installer le script](https://raw.githubusercontent.com/lax3is/Historiques-appels-et-ventes/refs/heads/main/Historiqueappelsventes.js)
3. Confirmez l'installation dans Tampermonkey

## Utilisation

### Historique des tickets
- Cliquez sur le bouton "Historique des tickets" dans l'interface Odoo
- Utilisez les filtres pour rechercher des tickets spécifiques
- Basculez entre le thème clair et sombre selon vos préférences

### Produits du client
- Cliquez sur le bouton "Produits du client" pour voir tous les produits associés
- Utilisez le bouton de copie d'URL pour partager la vue
- Filtrez les produits par type et utilisez la recherche

### Fonctionnalités avancées
- **Clic droit sur le bouton Produits** : Lance un diagnostic en cas de problème
- **Paramètre URL** : Ajoutez `showProducts=true` à l'URL pour afficher automatiquement les produits
- **Thème adaptatif** : Le script s'adapte automatiquement au thème d'Odoo

## Compatibilité

- Testé sur Odoo 16.0
- Compatible avec les navigateurs modernes (Chrome, Firefox, Edge)
- Nécessite une connexion à l'instance Odoo de Winprovence

## Mise à jour

Le script se met à jour automatiquement via Tampermonkey. Vous pouvez aussi :
- Vérifier manuellement les mises à jour dans Tampermonkey
- Visiter le [dépôt GitHub](https://github.com/lax3is/Historiques-appels-et-ventes) pour les dernières versions

## Support

En cas de problème :
1. Vérifiez la console du navigateur pour les messages d'erreur
2. Utilisez la fonction de diagnostic (clic droit sur le bouton Produits)
3. Créez une issue sur GitHub si le problème persiste

## Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.
