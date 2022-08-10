Tutoriel exercices labyrinthe - Comment modifier les blocs avec la boîte à outils et l'espace de travail
========================================================================================================

Si vous souhaitez ajouter ou supprimer des blocs de votre tâche, vous pouvez le faire en utilisant soit l'**interface utilisateur graphique**, soit les **fichiers XML**. Les blocs spécifiques à un labyrinthe se trouvent dans la catégorie Bibliothèque de blocs, et sont définis dans le fichier **"blocks.js "** (sous YourTask/public/), qui ne doit pas être modifié, sauf si vous souhaitez y ajouter de nouveaux blocs personnalisés.

Pour créer un nouveau bloc personnalisé, veuillez consulter ce tutoriel : https://jobblockly.readthedocs.io/en/latest/BaseBlockly.html#example-create-a-custom-block-if-else

Interface XML
-------------

**Voici l'interface XML où vous pouvez modifier les blocs présents dans votre tâche (remarquez qu'il y a deux fichiers séparés. Un pour la boîte à outils et un pour l'espace de travail):**

.. container:: text-center

    .. image:: ../images/img_fr/maze/xml.JPG
    
Interface graphique
-------------------

**C'est l'interface graphique où vous pouvez modifier les blocs présents dans votre tâche (Les fichiers XML correspondants sont automatiquement mis à jour lorsque vous modifiez l'interface graphique) :**

.. container:: text-center

    .. image:: ../images/img_fr/maze/graphically.JPG
