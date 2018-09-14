# Bitcoin Graph study with NetworkX

This is my University work, made to study a realistic Graph. The one I've chosen is the Bitcoin Alpha Graph.

## Getting Started

To download my repo:

```
git clone https://github.com/riki95/Bitcoin-Graph-study-with-NetworkX
```

The program was written in Python and compiled with Python 3.6 so you need it to run it.
The program needs a graph in input which is a csv file and I used the Bitcoin Alpha Dataset.

### Bitcoin Alpha Dataset

The [Bitcoin Alpha Dataset](https://snap.stanford.edu/data/soc-sign-bitcoin-alpha.html) is a csv file that consists on 4 columns:
```
SOURCE, TARGET, RATING, TIME
```

I've decided to only study Source, Target and Rating because Time was not so important to care about.
You can just download my repo and you will find the dataset with the first row removed (it was the one with the Column's names) or you can download it from the official website.

## Reproduce experiments

Reproducing experiments is very easy, running this command on terminal is enough:

```
python bitcoin_graph_analysis.py
```
You will see the analysys on the terminal or you can export it to a file modifing the parameter **file** inside the Python script.

You can modify the Graph in input and the analysis is quite the same. Obviously you have to adapt some methods. 

## Plots

Thanks to this script you will be able to draw your graph:

![Bitcoin Graph Image](https://i.imgur.com/fN9NB5U.png)

You can modify colors, nodes, scales and so on. You can also draw histograms:

![Diameter Historgram](https://i.imgur.com/aplPStE.png)

This has been done with Matplotlib and it is very useful if you need to plot degrees or something like that.

## Authors

* **Riccardo Basso** - *Università degli studi di Genova*
