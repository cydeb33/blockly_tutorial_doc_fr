Block tutorial - First steps
============================


Getting started - Creating your course
--------------------------------------

Welcome to this Blockly block tasks tutorial.

This tutorial is intended to help you navigate through the information needed to create blockly block tasks.

To create your own course, please contact: contact@inginious.org


Student interface on INGInious
------------------------------

Let's start this tutorial by explaining what your students will be handling.

All blockly tasks block oriented are defined as in the image below, which represents a basic task.


* At the top of the image you can see the title and context of the task.
* **TOOL BOX**: To complete the task, the student has a set of blocks, present in the **ToolBox**, the student can drag and drop blocks from the **ToolBox** to the **Workspace**. When you set up the task as a teacher, you decide which blocks are available in the **toolbox**.
* **WORKSPACE**: **Workspace** is where the blocks are placed to solve the task. When setting up the task as a teacher, you decide which blocks are available in the **workspace**.
* The **"Run Code"** button allows the student to run the blocks in the workspace. To run the code multiple times, the student must press the button again when it says **"Restart "** and then **"Run Code "** again.
* 2. The three buttons **"Blocks / Split / Text "** allow the student to show/hide an interface, showing the Python code equivalent to the blocks currently in the **workspace**. The **"Split "** button displays the interface on the right. By default it is set to **"Blocks "**, which shows only the blocks. The interface showing the code is not editable.
* 3. The interface showing the Python code equivalent of the blocks in the workspace.
* 4. In order to test his solution, the student must press **"Submit"**. Pressing **"Run Code "** only shows the effect of the blocks. The **"Submit"** button triggers the evaluation scripts, showing the feedback you decided to set based on the student's response (the evaluation system is discussed in more detail later in this tutorial).
* 5. The submission history at the bottom left allows the student to find their previous attempts and run them again.
* 6. This shows some information about the task and the student's progress.

.. container:: text-center

    .. image:: ../images/img_en/block/interface_en.JPG

The button **"Restart "**


.. container:: text-center

    .. image:: ../images/img_en/block/restart_en.JPG
    
Submitting and grading
----------------------
    
As explained earlier, pressing **"Run Code "** only runs the code so that the student can see what the character does as a result.

To evaluate the code the student has written, the student must press **"Submit "**. Their code is then sent to a script that tests the code, in this case a Python file called **"student.py "** that sends a message to a **"run "** file, then the **"run "** file will send a message to the student. These files should already be fully functional in the basic tasks you downloaded and you should not have to modify them.

When a student submits their code, the correction will test if the student's code matches the solution. If the tests are all correct the student has passed and will receive positive feedback. In our example it will look like this:

.. container:: text-center

    .. image:: ../images/img_en/block/passed_en.JPG

If an instance has failed, negative feedback is given and the failed instance is displayed:

.. container:: text-center

    .. image:: ../images/img_en/block/error_en.JPG
