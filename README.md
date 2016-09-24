# Children in Kolding

Analysis of [Hack4DK](https://hack4.dk/) [dataset](https://docs.google.com/spreadsheets/d/1hDJItyQqaeRTbo30C1y4fHPzp4Q4tlQHoCCKSJwv2iQ/edit#gid=0)
of health care data of children in Kolding, Denmark.

Data set provided by Kolding Stadsarkiv.

## Data set description

https://docs.google.com/presentation/d/15mj11bR5NTpB5tvF5AZXkwjRH3NxtHrbv-iioq51flQ/edit#slide=id.g172c4c7fcc_0_151

Data license: TODO

## Running the analysis

After [cloning this repository](https://help.github.com/articles/cloning-a-repository/),
the first step is to download and install [Anaconda (Python 3.5 version)](https://www.continuum.io/downloads).
Then set up a virtual environment to run the analysis in:

```
$ conda env create -f environment.yml
```

And activate the environment by executing:

```
Linux, OS X: $ source activate boern_kolding

Windows: $ activate boern_kolding
```

Afterwards, the jupyter notebook can be run by executing:

```
$ jupyter notebook children_kolding.ipynb
```


