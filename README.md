# Tweet like a future president

[Camille Francon](https://github.com/camillefrancon) and [Khaled Larbi](https://github.com/khaledlarbi) - Ensae

For this project, we tried to simulate tweets like some of the candidates for the 2022 French presidential election. We selected 5 candidates: Le Pen, Macron, Mélenchon, Pécresse, Zemmour (candidates with the highest results in the polls in March 2022).

In order to generate these tweets, we used the Twitter API and Twippy.

For the generation of tweets, we compared two methods:
- a from scratch model: LSTM.
- a pre-trained model on a large set of French: GPT-2.

This directory contains several files : 
- `colab` : a notebook allowing to test our results and to see the whole set of our tests. You can also find it [here](https://colab.research.google.com/drive/1gSDT18h14hxE9IFE_kEPZ6-Zxzg6JP6A?usp=sharing).
- `rapport` : a report in pdf format.
- `get_tweets` : the code that allowed us to retrieve the tweets.

