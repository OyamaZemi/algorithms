非復元抽出
==========

n 個の整数 0, ..., n-1 から k 個の整数を重複なしでランダムに抽出する．

Python 標準ライブラリの [random.sample](https://docs.python.org/2.7/library/random.html#random.sample)
にあるアルゴリズムそのままで書いた[コード](https://github.com/QuantEcon/QuantEcon.py/blob/42697210bc975734885aee3cc43507aa14c22e06/quantecon/random_mc.py#L169)があるが，\
それ以外にもたくさんあるはずなので，いろいろ実装してパフォーマンスを比較してみる．

* `random.sample` のコードは IPython Notebook で

  ```python
  import random
  random.sample??
  ```

  とすると見られる．

* [`np.random.choice(n, k, replace=False)`](http://docs.scipy.org/doc/numpy/reference/generated/numpy.random.choice.html)
  はちょっと遅い．
