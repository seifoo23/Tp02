Pour automatiser les tests du jeu, il est essentiel de mocker certaines interfaces. Voici les trois interfaces clés à mocker :

L’interface De : Cette interface représente le dé utilisé pour générer des nombres aléatoires lors des lancers de dés. 
En mockant cette interface, nous pouvons contrôler les résultats des lancers de dés et simuler différentes situations de jeu de manière reproductible.

L’interface Joueur : Elle représente le joueur et définit les méthodes pour placer des mises, débiter ou créditer de l’argent sur son compte.
 En mockant cette interface, nous pouvons simuler le comportement du joueur et vérifier les interactions avec d’autres composants du jeu.

L’interface Banque : Cette interface gère les fonds du jeu et définit les méthodes pour créditer ou débiter de l’argent.
 En mockant cette interface, nous pouvons simuler le comportement de la banque et vérifier comment elle réagit aux gains et aux pertes des joueurs.

le mocking des interfaces De, Joueur et Banque permet de contrôler les résultats des lancers de dés, de simuler le comportement des joueurs et de la banque,
 et d’automatiser les tests de manière cohérente.