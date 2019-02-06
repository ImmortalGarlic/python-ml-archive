#### `Requests`: HTTP for humans
  - Disable `requests.get(url, verify=False)` warning: requests.packages.urllib3.disable_warnings()

#### `MeCab`: the Japanese language text segmentation engine
*Alternatives: [janome](https://github.com/mocobeta/janome), [kuromoji](https://github.com/atilika/kuromoji)*
  - `Installation`
    - [Install MeCab and mecab-python3 on Ubuntu 14.04](https://qiita.com/elm200/items/2c2aa2093e670036bb30)
      - WARNING: This does not work!
    - [INSTALL MECAB-PYTHON3 THE RIGHT WAY!](https://pypi.org/project/mecab-python3/)
    - *Use [janome](https://github.com/mocobeta/janome) instead if you find the dependencies annoying*
  - `Debug`
    - [Cannot get surface element!](https://shogo82148.github.io/blog/2015/12/20/mecab-in-python3-final/)

#### `Dask`: parallel and scalable pandas-like computation engine
  - `dask.bag.map(func)`:  don't use inner functions in `func`
  - creating `dask.bag`: use parameter `npartitions` if not parallelized automatically
  - [Comparison between Dask and Ray](https://github.com/ray-project/ray/issues/642)

#### `Sklearn`: machine learning in Python
  - [`linear regressor` vs `sgdregressor` in sklearn](https://sdsawtelle.github.io/blog/output/week2-andrew-ng-machine-learning-with-python.html)
