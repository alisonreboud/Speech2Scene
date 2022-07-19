# Speech2Scene
This repository contains the code to produce Stage Directions from Dialogue for movies and series scenes. We run experiments on two datasets. 
[IMSDb dataset](https://www.imdb.com/interfaces/) available from ([see](https://github.com/AdeboyeML/Film_Script_Analysis))


## Data preparation

We run different preprocessing steps explicited in csi_text_separation for the CSI dataset and films_text_separation.ipynb for the IMSDb dataset. 
The output files of these notebooks which are used in the paper are (TBA)



## Finetuning T5
For the Finetuning of T5 experiment, use [Finetuning_T5.ipynb](Finetuning_T5.ipynb)
- The code of this notebook relies on the [Backprop library](https://backprop.readthedocs.io/en/latest) and is an adapatation of their [Finetuning_GettingStarted notebook](https://colab.research.google.com/github/backprop-ai/backprop/blob/main/examples/Finetuning_GettingStarted.ipynb)
