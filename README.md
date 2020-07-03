## Replication of SeER: An Explainable Deep Learning MIDI-based Hybrid Song Recommender System in TensorFlow2.

## You can directly modify these notebooks in Google Colab.

## I have tried my best to replicate [SeER: An Explainable Deep Learning MIDI-based Hybrid Song Recommender System](https://arxiv.org/abs/1907.01640) paper. 


### Preprocessing_MIDI_Dataset.ipynb
- To my extent I tried my best to replicate their dataset preparation procedure.
- The statistics that I got had a low variation with respect to papers published values.

### TO DO:

- Model testing by running for multiple epochs.
- NDCG, MAP@K scores 
- Implementing attention instead of LSTM and see the results.
- Explainabilty part of the paper.

Unfortunately, at this time I am unable to further implement it and get first results.
Due to high computation costs.

As per my knowledge this is the first replication and publicly available copy of their paper. So, please take the validity of code with caution.

Please see the original author's paper and I thank them for researching on a unique method for recommendations.

````
@article{DBLP:journals/corr/abs-1907-01640,
  author    = {Khalil Damak and
               Olfa Nasraoui},
  title     = {SeER: An Explainable Deep Learning MIDI-based Hybrid Song Recommender
               System},
  journal   = {CoRR},
  volume    = {abs/1907.01640},
  year      = {2019},
  url       = {http://arxiv.org/abs/1907.01640},
  archivePrefix = {arXiv},
  eprint    = {1907.01640},
  timestamp = {Mon, 08 Jul 2019 14:12:33 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1907-01640.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
````