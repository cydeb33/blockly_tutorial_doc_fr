Tutoriel exercices labyrinthes - Paramètres de la carte 
=======================================================

Modifier la carte
-----------------

Vous pouvez définir votre propre carte pour chaque exercice. Pour ce faire, il vous suffit de modifier le contenu du fichier maze.config.json qui se trouve dans "YourTask/public/maze.config.json".

L'image ci-dessous montre le contenu du maze.config.json.

.. container:: text-center

    .. image:: ../images/img_fr/maze/maze_config.JPG

Ce maze.config.json donne la carte montrée ci-dessous :

.. container:: text-center

    .. image:: ../images/img_fr/maze/maze_config_example.JPG

Si vous souhaitez modifier la disposition de la carte, comme créer de nouveaux chemins, ajouter des obstacles, etc., vous devez modifier l'élément **"layout "**. **"layout "** est un tableau de tableaux. Chaque tableau représente une carte que l'élève doit résoudre dans cet exercice. La signification des nombres trouvés dans le tableau se trouve dans l'élément **"squareType "** (que vous ne devriez pas avoir à modifier, sauf si vous ajoutez de nouveaux types d'éléments au labyrinthe. Nous allons les passer en revue plus en détail ici :



* **0** est une tuile vide (qui peut être peuplée aléatoirement avec un décor non interactif) où le personnage ne peut pas aller.

* **1** est une tuile ouverte où le personnage peut marcher.

* **2** est la tuile où le personnage commence le jeu.

* **3** est l'objectif à atteindre pour gagner la partie.

* **4** est une tuile avec un obstacle qui tuera le personnage s'il marche dessus.

* **5** est une valeur spéciale utilisée si vous voulez que les tuiles de départ et d'arrivée soient les mêmes.

Si vous souhaitez augmenter ou diminuer la vitesse d'animation du personnage, mettez à jour l'élément **"animationSpeed "**.

Si vous souhaitez modifier l'orientation du personnage au début de la tâche, mettez à jour l'élément **"startDirection "**. Le personnage est actuellement orienté vers le SOUTH, vous pouvez mettre WEST, NORTH ou EAST.

Cartes multiples
----------------

Vous pouvez ajouter autant de cartes que vous le souhaitez dans l'élément **"layout "**, comme le montre l'image ci-dessous.

Nos deux cartes ne seront, bien entendu, pas affichées en même temps. Elles sont là pour s'assurer que l'étudiant ne code pas en dur la solution à la carte qu'il voit. Vous pouvez ajouter autant de cartes que vous le souhaitez, avec un minimum d'une.

Lorsqu'un étudiant soumet son code, la correction testera chaque carte individuellement (dans l'ordre). Si elles passent toutes, l'étudiant a réussi.

.. container:: text-center

    .. image:: ../images/img_fr/maze/double_layout.JPG


Dans notre exemple, cela ressemblera à ceci (avec seulement la carte de gauche affichée) :

.. container:: text-center

    .. image:: ../images/img_fr/maze/multiple_maze.JPG


