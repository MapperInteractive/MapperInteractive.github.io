## Mapper Interactive Documentation

The Mapper algorithm is a method for topological data analysis first proposed by Gurjeet Singh, Facundo Mémoli and Gunnar Carlsson in 2007 [^1]. Mapper Interactive is a web-based visualization tool for high-dimensional data analysis build upon the Mapper algorithm. It is an open source software and is released under the MIT License.


Please find the source code on [GitHub](https://github.com/MapperInteractive/MapperInteractive).

### Installation
```shell
git clone git@github.com:MapperInteractive/MapperInteractive.git
cd MapperInteractive
python3 run.py
```

You can view the page at [http://0.0.0.0:8080/](http://0.0.0.0:8080/) (If possible, please use Chrome).

### Dependencies
This software requires [Kepler Mapper](https://kepler-mapper.scikit-tda.org/), [scikit-learn](https://scikit-learn.org/stable/), [NetworkX](https://networkx.github.io/) and [flask](https://flask.palletsprojects.com/en/1.1.x/) to run.

If you do not have these packages installed, please use the following command to intall them.

```bash
pip install scikit-learn
pip install kmapper
pip install networkx
pip install flask
```

To perform linear regression, please also make sure you have [statsmodels](https://www.statsmodels.org/stable/index.html) installed.
```bash
pip install statsmodels
```