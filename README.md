# Local installation

1. Get Anaconda from [here](https://docs.continuum.io/anaconda/install)

2. Create new enviroment and install psi4

    ```shell
    conda create -p conda psi4=1.4rc2 python=3.8 -c psi4/label/dev
    conda activate ./conda
    conda install matplotlib
    ```

3. Verify it works

    ```shell
    which psi4
    psi4 --version
    psi4 --test # optional might take some time
    ```

# Workshop Agenda

1. Introduction to Python and NumPy

    * [getting started](intro/getting_started.ipynb)

2. Computational methods:

    * Molecules - Quantum Chemistry

        * [Hatree-Fock](tcs/rhf_psi4numpy.ipynb)

        * MP2 (simplest correlation method)

    * Bulk Material - Condense Matter Physics

        * [H&uuml;ckel method](tcs/huckel.ipynb)

        * [Tight-bonding](tcs/tight_bonding.ipynb)