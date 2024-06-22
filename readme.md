
# Tic-Tac-Toe avec Pygame et Algorithme Minimax

## Auteurs

Ce projet a été réalisé par :

- [Barfoud Fatima Zohra]
- [Bouchkara Ikrame]
- [Bahafid Zineb]

Etudiantes en Master ILSI à la Faculté des Sciences et Techniques Errachidia (FSTE)

## Description du Projet

Ce projet est un jeu de Tic-Tac-Toe développé en utilisant Pygame, une bibliothèque Python pour le développement de jeux. L'algorithme Minimax est intégré pour permettre à l'ordinateur de jouer de manière optimale contre un joueur humain.

## Fonctionnalités

- **Interface Graphique:** Une interface utilisateur simple et intuitive créée avec Pygame.
- **Tour par Tour:** Les joueurs alternent leurs tours, l'humain jouant avec "X" et l'ordinateur avec "O".
- **Algorithme Minimax:** Utilisé pour calculer le meilleur coup possible pour l'ordinateur afin de minimiser la chance de défaite et maximiser la chance de victoire.
- **Indication de Fin de Jeu:** Un message visuel est affiché lorsqu'un joueur gagne ou s'il y a égalité.
- **Redémarrage du Jeu:** Appuyez sur la touche "R" pour réinitialiser le jeu et recommencer une nouvelle partie.

## Comment Jouer

1. Installez Pygame en utilisant la commande suivante:
   \`\`\`sh
   pip install pygame
   \`\`\`
2. Exécutez le fichier du jeu \`tictactoe.py\` en utilisant Python:
   \`\`\`sh
   python tictactoe.py
   \`\`\`
3. Cliquez sur une cellule vide pour jouer votre tour en tant que "X".
4. Attendez que l'ordinateur joue son tour en tant que "O".
5. Continuez à jouer jusqu'à ce qu'un joueur gagne ou qu'il y ait égalité.
6. Appuyez sur la touche "R" pour recommencer une nouvelle partie.

## Explication de l'Algorithme Minimax

L'algorithme Minimax est une méthode récursive utilisée dans la théorie des jeux et l'intelligence artificielle pour déterminer le meilleur coup à jouer. Voici comment il fonctionne :

1. **Évaluation des Coups:** L'algorithme évalue tous les coups possibles disponibles sur le plateau.
2. **Maximisation et Minimisation:** 
   - Si c'est le tour de l'ordinateur (joueur maximisant), il choisit le coup qui maximise son score.
   - Si c'est le tour de l'humain (joueur minimisant), il choisit le coup qui minimise le score de l'ordinateur.
3. **Fonction de Score:** 
   - Si l'ordinateur gagne, le score est positif (ex. +1).
   - Si l'humain gagne, le score est négatif (ex. -1).
   - Si c'est une égalité, le score est neutre (0).
4. **Récursivité:** L'algorithme continue d'explorer les coups possibles de manière récursive jusqu'à atteindre une condition de fin de partie (victoire, défaite, égalité).

L'objectif de l'algorithme Minimax est de garantir que l'ordinateur joue de manière optimale, minimisant les pertes face à un adversaire parfait.

## Installation et Exécution

1. Clonez ce dépôt ou téléchargez les fichiers sources.
2. Installez Pygame:
   \`\`\`sh
   pip install pygame
   \`\`\`
3. Exécutez le fichier \`tictactoe.py\`:
   \`\`\`sh
   python tictactoe.py
   \`\`\`


