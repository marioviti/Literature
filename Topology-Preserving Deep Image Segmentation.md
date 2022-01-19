
## 2.1 Topology and Persistent Homology

d-dimension topological structure: homology class, equivalence class of d-manifolds.

* 0-dim manifold: connected components
* 1-dim manifold: handles (closed loops) (locally a line)
* 2-dim manifold: non intersecting closed surfaces (locally a plane)

[Topology refresher](https://bjlkeng.github.io/posts/manifolds/)

For a domain X one can count the number of topology structure in the same homology class (Betti Number)
e.g. for 2d images (X) number of connected components (0-dim manifolds) + number of handles (1-dim manifolds)

Using this as loss is hard to backpropagate.
Persistent homology: capture all homology structures on continuous maps using different thresholds (component tree?) 
this information is summarized int e persistence diagram.
filtration: monotonically increasing thresholds sets of trhesholded likelihood maps 
as alpha increases the topology changes -> some structure are born some are killed




![image](https://user-images.githubusercontent.com/3719845/150150961-481ef4a4-d2e4-4bfa-ab20-64fe774932ae.png)

[paper](https://github.com/marioviti/Literature/blob/main/topoprese.pdf)
