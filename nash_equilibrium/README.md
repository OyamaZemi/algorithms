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
      * [scipy.spatial.ConvexHull](https://docs.scipy.org/doc/scipy/reference/generated/scipy.spatial.ConvexHull.html)
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
      G. van der Laan, A. J. J. Talman, and L. van der Heyden (1987)
      "[Simplicial Variable Dimension Algorithms for Solving the Nonlinear Complementarity Problem on a Product of Unit Simplices Using a General Labelling](https://scholar.google.com/scholar?cluster=16246388050012211834)"