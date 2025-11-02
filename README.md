# Pay Me - Application de Score de Jeu de Cartes

Application web interactive pour suivre les scores lors de parties de cartes.

## Fonctionnalités

### Configuration de la partie
- Sélection de la carte de départ (3 à Roi)
- Ajout de joueurs avec leurs initiales
- Support de 2 joueurs ou plus
- Validation des noms de joueurs

### Gestion du jeu
- Affichage de la carte actuelle et du numéro de manche
- Tableau de scores détaillé avec historique complet
- Saisie des scores par manche pour chaque joueur
- Système "Pay Me" pour marquer les manches spéciales
- Calcul automatique des totaux
- Compteur de "Pay Me" par joueur

### Affichage et classement
- Écran de classement en temps réel
- Podium avec médailles (🥇 🥈 🥉)
- Détails des scores par manche
- Écran de fin de partie avec gagnant

### Mode sombre 🌙
- Basculer entre mode clair et mode sombre
- Bouton de bascule dans le header
- Sauvegarde automatique de la préférence
- Transitions fluides entre les modes
- Palette de couleurs optimisée pour chaque mode

### Persistance des données
- Sauvegarde automatique dans le navigateur (localStorage)
- Récupération de la partie en cours au rechargement
- Sauvegarde de la préférence de thème (clair/sombre)

### Options de réinitialisation
- Rejouer avec les mêmes joueurs
- Nouvelle partie complète
- Modal de confirmation pour éviter les erreurs

## Technologies utilisées

- HTML5
- CSS3 avec variables CSS
- JavaScript Vanilla
- LocalStorage API
- Design responsive (mobile et desktop)

## Utilisation

1. Ouvrez `index.html` dans votre navigateur
2. Sélectionnez la carte de départ
3. Ajoutez les joueurs (minimum 2)
4. Démarrez la partie
5. Entrez les scores pour chaque manche
6. Cochez "Pay Me" si nécessaire
7. Passez à la manche suivante
8. Consultez le classement à tout moment
9. Basculez en mode sombre avec le bouton 🌙/☀️

## Fonctionnalités du mode sombre

Le mode sombre a été conçu pour :
- Réduire la fatigue oculaire lors de longues parties
- Améliorer la lisibilité dans les environnements sombres
- Offrir une expérience visuelle moderne et élégante
- Maintenir un contraste optimal pour tous les éléments

### Activation du mode sombre
- Cliquez sur le bouton 🌙 dans le header pour activer le mode sombre
- L'icône change en ☀️ quand le mode sombre est actif
- Votre préférence est sauvegardée automatiquement

## Interface responsive

L'application s'adapte automatiquement aux différentes tailles d'écran :
- Desktop : affichage complet avec grand tableau
- Mobile : interface optimisée avec tableaux défilables

## Licence

Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## Développement

Application développée en une page HTML autonome, sans dépendances externes.
Prête à être déployée sur n'importe quel serveur web statique ou GitHub Pages.
