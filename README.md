# Stanford CS224W Machine Learning with Graphs

The course notes about Stanford CS224n Machine Learning with Graphs Fall 2019

* [CS224W Fall 2019](http://web.stanford.edu/class/cs224w/)
  * [videos](http://snap.stanford.edu/class/cs224w-videos-2019/)

> ~~but it didn't release the latest (2019) videos~~
>
> * you have to purchase the course ($5200): [Machine Learning with Graphs | Stanford Online](https://online.stanford.edu/courses/cs224w-machine-learning-graphs)

## Schedule

* [ ] Link Prediction (current ~11:00)
* [X] Graph Representation Learning

## Recitation

### SNAP.py

* Material
  * Fall 2019 Lecture 7
    * [slides](CourseMaterials/Recitation/CS224W-snappy-tutorial(2019).pdf)
  * **Autumn 2018 Lecture 8**
    * [slides](CourseMaterials/Recitation/SNAP.PY-recitation(2018).pdf)
    * [video](http://snap.stanford.edu/class/cs224w-videos-2018/180928-cs224w-rs-720.mp4)

### Linear Algebra, Probability, and Proof Techniques

* Material
  * Fall 2019 Lecture 7
    * [slides](CourseMaterials/Recitation/CS224W_LinAl_Prob_Proof(2019).pdf)
  * **Autumn 2018 Lecture 8**
    * [slides](CourseMaterials/Recitation/proofs-recitation(2018).pdf)
    * [video](http://snap.stanford.edu/class/cs224w-videos-2018/181005-cs224w-rs-720.mp4)

## Lecture

> * I'll using the previous course materials:
>   * [**Stanford CS224W: Analysis of Networks (Autumn 2018)**](http://snap.stanford.edu/class/cs224w-2018/index.html) - videos in `RESOURCES -> Lectures`
>   * [Stanford CS224W: Analysis of Networks (Autumn 2017)](http://snap.stanford.edu/class/cs224w-2017/)
>     * [Handouts](http://snap.stanford.edu/class/cs224w-2017/handouts.html)
>     * [CS224W Social and Information Network Analysis Autumn 2017 Videos archive](http://snap.stanford.edu/class/cs224w-videos-2017/)

### Link Prediction

> The more general one (normal graph not limited to knowledge graph)

* Material
  * **Autumn 2018 Lecture 8**
    * [slides](CourseMaterials/LinkPrediction/08-SBM(2018).pdf)
    * [video](http://snap.stanford.edu/class/cs224w-videos-2018/181018-cs224w-720.mp4)

> Notes
>
> * Local structure: Link prediction via proximity
>   * different scoring function
> * Global structure: Stochastic Blockmodels (SBM)

### Graph Representation Learning

* Material
  * Fall 2019 Lecture 7
    * [slides](CourseMaterials/GraphRepresentationLearning/07-noderepr(2019).pdf)
  * **Autumn 2018 Lecture 9**
    * [slides](CourseMaterials/GraphRepresentationLearning/09-node2vec(2018).pdf)
    * [video](http://snap.stanford.edu/class/cs224w-videos-2018/181023-cs224w-720.mp4)
    * [video (youtube)](https://www.youtube.com/watch?v=YrhBZUtgG4E)
  * Autumn 2017 Lecture 19
    * [slides](CourseMaterials/GraphRepresentationLearning/19-node2vec(2017).pdf)
    * [video](http://snap.stanford.edu/class/cs224w-videos-2017/171205-cs224w-720.mp4)
* Additional
  * SNAP: [WWW 2018 Tutorial](https://www2018.thewebconf.org/program/tutorials-track/) [Representation Learning on Networks](http://snap.stanford.edu/proj/embeddings-www/) (Professor Jure Leskovec)
    * Part 0: Intro [slides](CourseMaterials/GraphRepresentationLearning/nrltutorial-part0-intro.pdf)
    * Part 1: Node embeddings [slides](CourseMaterials/GraphRepresentationLearning/nrltutorial-part1-embeddings.pdf)
    * Part 2: Graph neural networks [slides](CourseMaterials/GraphRepresentationLearning/nrltutorial-part2-gnns.pdf)
    * Part 3: Applications [slides](CourseMaterials/GraphRepresentationLearning/nrltutorial-part3-applications.pdf)
* Other
  * [Graph Node Embedding Algorithms (Stanford - Fall 2019) - YouTube](https://www.youtube.com/watch?v=7JELX6DiUxQ)

> Notes
>
> * Node Embedding: $\operatorname{similarity}(u, v) \approx z_v^Tz_u$
>   * shallow encoding
> * Define node similarity:
>   * Random Walk
>     * optimize softmax: negative sampling
>     * Other way to random walk
>       * node2vec: a 2nd-order random walk
>         * BFS & DFS vs. return parameter p, in-out parameter q
> * Graph Embedding:
>   * Sum/Average of all nodes embedding
>   * Create super-node that spans the graph and then embed that node
>   * Anonymous Walk Embedding

### Link Analysis: PageRank

* Material
  * Fall 2019 Lecture 11
    * [slides](CourseMaterials/PageRank/11-pagerank(2019).pdf)
  * Autumn 2018 Lecture 3
    * [slides](CourseMaterials/PageRank/03-pagerank(2018).pdf)
    * [video](http://snap.stanford.edu/class/cs224w-videos-2018/181002-cs224w-720.mp4)

## Assignment

### 2019 Homework

#### 2019 Homework 0

* [Instruction](Assignments/Homework2019/hw0-bundle/hw0.pdf)

```sh
# Install SNAP.py
pip install snap-stanford
# (alternative)
# wget http://snap.stanford.edu/snappy/release/snap-stanford-5.0.0-5.0-macosx10.14.4-x64-py3.7.tar.gz
# wget http://snap.stanford.edu/snappy/release/beta/snap-5.0.9-64-3.0-macosx10.9.5-x64-py3.6.tar.gz
# uncompress...
# install... (recommend the first one)
# python3 -m pip install .
# python3 setup.py install

# Wikipedia voting network
# http://snap.stanford.edu/data/wiki-Vote.html
wget http://snap.stanford.edu/data/wiki-Vote.txt.gz
gunzip wiki-Vote.txt.gz

# Stack Overflow network
wget http://snap.stanford.edu/class/cs224w-data/hw0/stackoverflow-Java.txt.gz
gunzip stackoverflow-Java.txt.gz
```

#### 2019 Homework 1

* [Instruction](Assignments/Homework2019/hw1-bundle/hw1.pdf)

> TODO

#### 2019 Homework 2: Node Classification, TransE, GNN Expressiveness and Training

* [Instruction](Assignments/Homework2019/hw2-bundle/hw2.pdf)

#### 2019 Homework 3

* [Instruction](Assignments/Homework2019/hw3-bundle/hw3.pdf)

> TODO

## Related Resources

### SNAP - Stanford Network Analysis Project

* [SNAP: Stanford Network Analysis Project](http://snap.stanford.edu/)
  * [github snap-stanford](https://github.com/snap-stanford)
  * [tutorial](https://snap.stanford.edu/snappy/doc/tutorial/index-tut.html)

* [gnuplot](http://www.gnuplot.info/) - for plotting structural properties of networks (e.g., degree distribution)
  * [gnuplot - Browse /gnuplot at SourceForge.net](https://sourceforge.net/projects/gnuplot/files/gnuplot/)
* [GraphViz](https://www.graphviz.org/) for drawing and visualizing small graphs

### Others' Course Notes

* [LFhase/Learning_CS224w](https://github.com/LFhase/Learning_CS224w)

---

## Other Notes

* [python setup.py uninstall - Stack Overflow](https://stackoverflow.com/questions/1550226/python-setup-py-uninstall)
* [python - Can I force pip to reinstall the current version? - Stack Overflow](https://stackoverflow.com/questions/19548957/can-i-force-pip-to-reinstall-the-current-version)
