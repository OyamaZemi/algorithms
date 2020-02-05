Sparse matrix 用の GTH アルゴリズム
===================================

Sparse matrix (疎行列) に対する GTH アルゴリズムを実装する．
[Fill-in](http://en.wikipedia.org/wiki/Sparse_matrix#Reducing_fill-in)
の問題があるからけっこうたいへんなはず．

Dense matrix (密行列) 用のコードは
[gth_solve.py](https://github.com/QuantEcon/QuantEcon.py/blob/master/quantecon/markov/gth_solve.py)
にある．

必要な知識

* GTH アルゴリズム
* Sparse matrix format
  * [Sparse matrices (scipy.sparse)](http://docs.scipy.org/doc/scipy/reference/sparse.html)
