# Multi-Omics Integration for Personalized Medicine Using MOFA

To run this tutorial, first set up micromamba on your computer using

`"${SHELL}" <(curl -L micro.mamba.pm/install.sh)`

Then, create a new environment with Python 3.11 using the commands

`micromamba create -n ebi_mofa -c conda-forge python==3.11`

`micromamba activate ebi_mofa`

Then, install the required packages using

`pip install mofaflex plotnine gseapy`