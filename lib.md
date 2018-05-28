#### `MeCab`: the Japanese language text segmentation engine
*Alternatives: [janome](https://github.com/mocobeta/janome), [kuromoji](https://github.com/atilika/kuromoji)*
  - `Installation`
    - [Ubuntu 14.04 に Mecab と mecab-python3 をインストール](https://qiita.com/elm200/items/2c2aa2093e670036bb30)
    - *Use [janome](https://github.com/mocobeta/janome) instead if you find the dependencies annoying*
  - `Debug`
    - [surface 読み取れない！](https://shogo82148.github.io/blog/2015/12/20/mecab-in-python3-final/)

#### `Dask`: parallel and scalable pandas-like computation engine
  - `dask.bag.map(func)`:  don't use inner functions in `func`
  - creating `dask.bag`: use parameter `npartitions` if not parallelized automatically
