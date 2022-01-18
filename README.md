# Music Recommender System Conditioned on Lyrics and Metadata

***By Eric Bezzam and Vidit Vidit***

We investigate the integration of lyrics into a 
music recommender system. From a learned
lyrical embedding space, we retrieve similar songs and are also able to condition on
metadata such as genre and various acoustic features. The lyrical embedding space is
trained by finetuning a language model on
various downstream tasks, e.g. genre classification, and determining clusters within this
space. These clusters are then used to look for
similar songs.

***This project was done for the EPFL Doctoral Course "Deep Learning For Natural
Language Processing" (EE-608).***

Code can be found in the `notebooks` folder, with a demo in 
[`notebooks/5_recommendation_demo.ipynb`](https://github.com/ebezzam/lyrics-mir/blob/main/notebooks/5_recommendation_demo.ipynb).

A report summarizing our work and results can be found in `report.pdf`.

Finetuned models and pre-computed embeddings and clusterings can be downloaded [here](https://drive.switch.ch/index.php/s/bzD51pQFdPeDOvx) and placed in the `notebooks` folder.
