#### Dask
1. How to read file in bytes?
   - `dask.bag.read_text()` cannot do this
   - `dask.bytes.read_bytes()` ? No. [Check this](http://dask.pydata.org/en/latest/bytes.html)
   - Current solution is: `with open file` > `file.readlines()` > `dask.bag.from_sequence()`
2. Cannot save huge `dask.bag` data to textfile using `dask.bag.to_textfiles()`. Why???
