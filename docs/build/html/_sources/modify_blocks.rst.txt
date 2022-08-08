Maze tutorial - How to modify the blocks with the toolbox & workspace
=====================================================================

If you wish to add or remove blocks from your task, you can do so using either the **graphical user interface** or the **XML files**. The blocks that are specific to a maze can be found under the Block Library category, and are defined in the file **"blocks.js"** (under YourTask/public/), which should not be modified, except if you want to add new custom blocks to it.

To create a new custom block please refer to this tutorial : https://jobblockly.readthedocs.io/en/latest/BaseBlockly.html#example-create-a-custom-block-if-else

XML interface
-------------

**This is the XML interface where you can modify the blocks present in your task (notice that there are two separate files. One for the toolbox and one for the workspace):**

.. container:: text-center

    .. image:: ../images/img_en/maze/XML_edit.JPG
    
Graphical interface
-------------------

**This is the graphical user interface where you can modify the blocks present in your task (The corresponding XML files are automatically updated when you modify the graphical interface) :**

.. container:: text-center

    .. image:: ../images/img_en/maze/blockly_factory_graphically.JPG
