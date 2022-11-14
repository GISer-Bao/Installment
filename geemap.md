# Install geemap

## **step 1. install geemap**
```
conda create -n gee python=3.8
conda activate gee
conda install geopandas
conda install mamba -c conda-forge
mamba install cartopy scipy geemap pygis localtileserver -c conda-forge
```


## **step 2. install jupyter notebook**

```
conda install jupyter notebook
pip install jupyter_contrib_nbextensions
pip install jupyter_nbextensions_configurator
```

## **reference**

```
geemap:
https://github.com/giswqs/geemap
https://github.com/giswqs/geemap/blob/e742d86cb183ed02913015c0efbf4f72bd68a7bc/examples/notebooks/112_cartoee_basemap.ipynb
https://geemap.org/installation/

jupyter notebook:
https://mp.weixin.qq.com/s/yilS3QdTd7gQ6PMDA_qySQ
https://towardsdatascience.com/jupyter-notebook-extensions-517fa69d2231?gi=9ee8ef8758b9
```
