# scdefg
**s**cVI **C**olab **d**ifferential **e**xpression **F**lask **G**UI

This is an experimental app to create a simple GUI to allow people to perform differential expression on any single cell RNA sequencing dataset using [scvi-tools](https://scvi-tools.org). This is a tiny Flask app made to be run from a Google Colab. It uses [ngrok](https://ngrok.com/) to allows you to share the app with an auto generated link to other people. All you need is the filtered gene count matrix (*not* normalized) data in the [anndata .h5ad](https://anndata.readthedocs.io/en/latest/index.html) format and all the rest of the processing is done by scvi in the Colab Notebook. 

Click the button below to open a notebook and run it. It loads an example C. elegans dataset with 100k cells and 169 cell types with data from the data from the CeNGEN project published by[Taylor et al 2020](https://doi.org/10.1016/j.neuron.2018.07.042). See how it works, then try it with your own data and share with your lab friends!

[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Munfred/scdefg/blob/main/scdefg.ipynb)
