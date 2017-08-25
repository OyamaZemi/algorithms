Nash 均衡の計算
==============

標準形ゲームの Nash 均衡計算アルゴリズムを実装する．

* 2人ゲーム  
  * von Stengel, B. (2007)
    "[Equilibrium Computation for Two-Player Games in Strategic and Extensive Form](http://www.maths.lse.ac.uk/personal/stengel/TEXTE/agt-stengel.pdf)"
  * Avis, D., G. Rosenberg, R. Savani, and B. von Stengel (2010)
    "[Enumeration of Nash Equilibria for Two-Player Games](http://www.maths.lse.ac.uk/personal/stengel/ETissue/ARSvS.pdf)"

  * Nash 均衡を1つ求める

    * Lemke-Howson
      * [QuantEcon.py #268](https://github.com/QuantEcon/QuantEcon.py/pull/268)

  * Nash 均衡をすべて求める

    * Support enumeration
      * [QuantEcon.py #263](https://github.com/QuantEcon/QuantEcon.py/pull/263)
      * [Games.jl #26](https://github.com/QuantEcon/Games.jl/pull/26)

    * Vertex enumeration
      * [QuantEcon.py #326](https://github.com/QuantEcon/QuantEcon.py/pull/326)
      * [Polyhedra.jl](https://github.com/JuliaPolyhedra/Polyhedra.jl)

    * lrsNash
      * [lrs](http://cgm.cs.mcgill.ca/%7Eavis/C/lrs.html)
      * [LRSLib.jl](https://github.com/JuliaPolyhedra/LRSLib.jl)

* N人ゲーム

  * Nash 均衡を1つ求める

    * McLennan-Tourky  
      McLennan, A. and R. Tourky (2006)
      "[From Imitation Games to Kakutani](http://cupid.economics.uq.edu.au/mclennan/Papers/kakutani60.pdf)"
      * [QuantEcon.py #273](https://github.com/QuantEcon/QuantEcon.py/pull/273)

    * Simplicial subdivision
      * G. van der Laan and A. J. J. Talman (1982)
        "[On the Computation of Fixed Points in the Product Space of Unit Simplices and an Application to Noncooperative N Person Games](https://scholar.google.com/scholar?cluster=123786532926491999)"
      * G. van der Laan, A. J. J. Talman, and L. van der Heyden (1987)
        "[Simplicial Variable Dimension Algorithms for Solving the Nonlinear Complementarity Problem on a Product of Unit Simplices Using a General Labelling](https://scholar.google.com/scholar?cluster=16246388050012211834)"

    * Govindan-Wilson
      * S. Govindana and R. Wilson (2003)
        "[A global Newton method to compute Nash equilibria](http://www.sciencedirect.com/science/article/pii/S002205310300005X)"
      * S. Govindana and R. Wilson (2004)
        "[Computing Nash equilibria by iterated polymatrix approximation](http://www.sciencedirect.com/science/article/pii/S0165188903001088)"

    * McKelvey-Palfrey
      * McKelvey, R. D. and Palfrey, T. R. (1995)
        "[Quantal Response Equilibria for Normal Form Games](http://www.sciencedirect.com/science/article/pii/S0899825685710238)"
