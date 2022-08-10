Tutoriel sur les blocs - Premiers pas
=====================================


Démarrage - Création de votre cours
-----------------------------------

Bienvenue dans ce tutoriel de tâches Blockly.

Ce tutoriel a pour but de vous aider à naviguer dans les informations nécessaires à la créations de tâches blockly.

Pour la création de votre propre cours, veuillez contacter : contact@inginious.org

Interface étudiant sur INGInious
--------------------------------

Commençons ce tutoriel en expliquant ce que vos étudiants vont devoir manipuler.

Toutes les tâches blockly axées blocs sont définies comme dans l'image ci-dessous, qui représente une tâche basique.


* En haut de l'image, vous pouvez voir le titre et le contexte de la tâche.
* **BOÎTE À OUTILS** : Pour réaliser la tâche, l'élève dispose d'un ensemble de blocs, présents dans la **boîte à outils**, l'élève peut glisser et déposer des blocs de la **boîte à outils** vers **l'espace de travail**. Lorsque vous configurez la tâche en tant qu'enseignant, vous décidez quels blocs sont disponibles dans la **boîte à outils**.
* **ESPACE DE TRAVAIL** : **L'espace de travail** est l'endroit où les blocs sont placés pour résoudre la tâche. Lors de la mise en place de la tâche en tant qu'enseignant, vous décidez quels blocs sont disponibles dans **l'espace de travail**.
* Le bouton **"Exécuter le code"** permet à l'étudiant d'exécuter les blocs présents dans **l'espace de travail**. Pour exécuter le code plusieurs fois, l'élève doit appuyer à nouveau sur le bouton lorsqu'il est indiqué **"Redémarrer "** puis **"Exécuter le code "** à nouveau.
* 2. Les trois boutons **"Blocks / Split / Text "** permettent à l'étudiant d'afficher/masquer une interface, montrant le code Python équivalent aux blocs actuellement présents dans **l'espace de travail**. Le bouton **"Split "** affiche l'interface sur la droite. Par défaut, il est réglé sur **"Blocs "**, ce qui ne montre que les blocs. L'interface montrant le code n'est pas modifiable.
* 3. L'interface montrant l'équivalent du code Python des blocs dans l'espace de travail.
* 4. Afin de tester sa solution, l'étudiant doit appuyer sur **Soumettre**. Le fait d'appuyer sur **"Exécuter le code"** ne fait que montrer l'effet des blocs. Le bouton **Soumettre** déclenche les scripts d'évaluation, montrant le feedback que vous avez décidé de définir en fonction de la réponse de l'étudiant (le système d'évaluation est abordé plus en détail plus loin dans ce tutoriel).
* 5. L'historique des soumissions en bas à gauche permet à l'étudiant de retrouver ses tentatives précédentes et de les ré-exécuter.
* 6. Ceci montre quelques informations sur la tâche et la progression de l'étudiant.


.. container:: text-center

    .. image:: ../images/img_fr/block/interface_fr.JPG

Le bouton **"Redémarrer "**


.. container:: text-center

    .. image:: ../images/img_fr/block/restart_fr.JPG

Soumission et évaluation
------------------------

Comme expliqué précédemment, le fait d'appuyer sur **"Exécuter le code "** ne fait qu'exécuter le code afin que l'étudiant puisse voir ce que le code fait en conséquence.

Pour évaluer le code écrit par l'étudiant, ce dernier doit appuyer sur **"Soumettre"**. Son code est ensuite envoyé à un script testant le code, ici un fichier Python appelé **"student.py "** qui envoie un message à un fichier **"run "**, puis le fichier **"run "** enverra un message à l'étudiant. Ces fichiers devraient déjà être entièrement fonctionnels dans les tâches de base que vous avez téléchargées et vous ne devriez pas avoir à les modifier.

Lorsqu'un étudiant soumet son code, la correction testera le code de l'étudiant. S'il a réussi il recevra un feedback positif. Dans notre exemple, cela ressemblera à ceci :

.. container:: text-center

    .. image:: ../images/img_fr/block/passed_fr.JPG

Si une évaluation a échoué, un feedback négatif est donné et l'instance qui a échoué est affichée :

.. container:: text-center

    .. image:: ../images/img_fr/block/error_fr.JPG
