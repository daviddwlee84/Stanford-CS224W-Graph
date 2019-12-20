# Stanford CS224W Machine Learning with Graphs

The course notes about Stanford CS224n Machine Learning with Graphs Fall 2019

* [CS224W Fall 2019](http://web.stanford.edu/class/cs224w/)
  * [videos](http://snap.stanford.edu/class/cs224w-videos-2019/)

## Schedule

| Week             | Lectures                                                                                                                                                                                      | Assignments               |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- |
| 2019/12/23~12/29 | [Introduction; Structure of Graphs](#lecture-1-introduction-structure-of-graphs), [Properties of Networks and Random Graph Models](#lecture-2-properties-of-networks-and-random-graph-models) | [Homework 0](#homework-0) |

## Recitation

### SNAP.py

* [video](http://snap.stanford.edu/class/cs224w-videos-2019/CS224W_-_Recitation_Session_on_9_27_2019_(Fri)_default_b2b0dfcf.mp4)
* [slides](CourseMaterials/Recitation/CS224W-snappy-tutorial(2019).pdf)

### Linear Algebra, Probability, and Proof Techniques

* [video](http://snap.stanford.edu/class/cs224w-videos-2019/CS224W_on_9_26_2019_(Thu)_default_20ab4bd0.mp4)
* [slides](CourseMaterials/Recitation/CS224W_LinAl_Prob_Proof(2019).pdf)

## Lectures

### Lecture 1: Introduction; Structure of Graphs

* [video](http://snap.stanford.edu/class/cs224w-videos-2019/CS224W_on_9_24_2019_(Tue)_default_2dfd20e9.mp4)
* [slides](CourseMaterials/Introduction/01-intro.pdf)
* reading
  * [Chapter 1 from Easley and Kleinberg: Overview](CourseMaterials/Introduction/networks-book-ch01.pdf)
  * [Random graphs with arbitrary degree distributions and their applications](CourseMaterials/Introduction/Random_graphs_with_arbitrary_degree_distributions_and_their_applications.pdf)

### Lecture 2: Properties of Networks and Random Graph Models

* [video](http://snap.stanford.edu/class/cs224w-videos-2019/CS224W_on_9_26_2019_(Thu)_default_20ab4bd0.mp4)

## Assignments

### Homework 0

* [Instruction](Assignments/Homework2019/hw0-bundle/hw0.pdf)

```sh
# Install SNAP.py
pip install snap-stanford

# Wikipedia voting network
# http://snap.stanford.edu/data/wiki-Vote.html
wget http://snap.stanford.edu/data/wiki-Vote.txt.gz
gunzip wiki-Vote.txt.gz

# Stack Overflow network
wget http://snap.stanford.edu/class/cs224w-data/hw0/stackoverflow-Java.txt.gz
gunzip stackoverflow-Java.txt.gz
```

### Homework 1

* [Instruction](Assignments/Homework2019/hw1-bundle/hw1.pdf)

### Homework 2: Node Classification, TransE, GNN Expressiveness and Training

* [Instruction](Assignments/Homework2019/hw2-bundle/hw2.pdf)

### Homework 3

* [Instruction](Assignments/Homework2019/hw3-bundle/hw3.pdf)

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
