#             GLUTcode

## Contenidos
1. [Introducción a la proteína que se estudiará](ntbk/01.%20GLUT1_prot.ipynb)
2. [Alineamiento múltiple de secuencias](ntbk/02.%20Multipleseq_align.ipynb)
3. [Docking Molecular](ntbk/Mol_docking.ipynb)
5. [Simulaciones de dinámica molecular](ntbk/Mol_dynamic_sim.ipynb)

## Consideraciones
>[!Tip]
>:monocle_face: Para utilizar este repositorio debes instalar [Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/install) en tu dispositivo e instalar sus respectivos ambientes.
>Versión de Python: 3.12

### 1st env:
conda create -n [name]\
conda activate [name]\
conda install -c bioconda biopython pandas altair jupyterlab -y\
conda install bioconda/label/cf201901::mafft

### OpenMM env:
conda create -n [name]\
conda activate\
conda install -c conda-forge jupyterlab ipython pandas scikit-learn biopython biopandas -y\
conda install -c conda-forge openmmtools -y\
[Documentación OpenMM](http://docs.openmm.org/latest/userguide/)