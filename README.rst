RadicalML: Machine Learning for Radical Species
======================================================================

**RadicalML** is a Python-based framework for the **modeling of radical species properties** using **Machine Learning (ML)**.

Installation
------------

``RadicalML`` can be installed using conda/mamba package managers.

.. code-block:: bash

    git clone https://github.com/KagakuAI/RadicalML.git
    conda env create -f RadicalML/conda/radical_linux.yml
    conda activate radical

The installed ``RadicalML`` environment can then be added to the Jupyter platform:

.. code-block:: bash

    conda install ipykernel
    python -m ipykernel install --user --name radical --display-name "radical"
