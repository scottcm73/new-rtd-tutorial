getting_started
===============

.. _install_python_open3dd_package:

Install Python Open3D Package
-----------------------------

First, follow these instructions to install the Python Open3D package. Open your Terminal (Mac) or Command Prompt (PC). According to the documentation, the package requires Python 3.8 or lower. If you have a higher version of Python, you will likely need to install 3.8 or lower on your system to install the package.

If you have more than one version of Python, the highest version will be the default unless you specifically change it (which you don't want to do). So, to install the Open3D python package with the 3.8 version of Python, try the command:

.. code-block::console
    
   py -3.8 -m pip install open3d

This command should associate the python 3.8 version with the Python Open3D package.

.. _clone_python_open3d_repository:

Clone Python Open3D Repository
------------------------------

For this tutorial, you will need to have the package's repository. I recommend navigating to your desktop to clone the repository.

For example:
For PC:

.. code-block:: console

    cd OneDrive\Desktop 

For Mac:

.. code-block:: console

    cd desktop 

Make a new directory.

.. code-block:: console

    mkdir open3dgit

Then, open the folder you created.

.. code-block:: console

    cd open3dgit

Now, clone the repository. 

.. code-block:: console

    git clone -b v0.13.0 git@github.com:isl-org/Open3D.git

for SSH

    or 

.. code-block:: console

    git clone -b v0.13.0 https://github.com/isl-org/Open3D.git

for https

Make sure you have the “-b v0.13.0” after git clone (like the commands above) to ensure that you are cloning the correct version.