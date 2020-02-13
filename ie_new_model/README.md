## Random forest model on iris dataset

Tingting Sun

Usage
To install the library:
```
$ pip install .
```
Basic usage:

```
>>> from ie_rf_iris.model_rf import train_and_persist, predict
>>> train_and_persist()
>>> predict({
...     "0": 5.0,
...     "1": 4.2,
...     "2": 1.4,
...     "3": 0.3
... })
```
Result:0
