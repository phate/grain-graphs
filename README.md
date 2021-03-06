# Grain Graphs

Grain graphs is a visualization method for OpenMP that connects performance problems to the fork-join program structure resolved into *grains* -- task and parallel for-loop chunk instances created during execution. Grains that suffer crippling problems such as low parallelism, work inflation, and poor parallelization benefit are pinpointed on grain graphs. Since programmers readily identify with the grain-resolved fork-join program structure, problem diagnosis is simplified. In contrast, existing visualizations complicate diagnosis by resolving performance problems from a runtime system or threads perspective that is unfamiliar and unpredictable to programmers.

![](https://github.com/anamud/grain-graphs/wiki/figures/bots-sort-analysis.gif "Click image to zoom-in")

## Documents

See the [wiki](https://github.com/anamud/grain-graphs/wiki) for more information about grain graphs, including use of a proof-of-concept prototype implementation.

## Citation

If you use grain graphs in your work, please cite the debut [paper](http://dl.acm.org/citation.cfm?id=2851156):

    Muddukrishna, Ananya, P. A. Jonsson, A. Podobas, and M. Brorsson,
    "Grain Graphs: OpenMP Performance Analysis Made Easy," in
    Proceedings of the 21st ACM SIGPLAN Symposium on Principles and Practice of Parallel Programming,
    New York, NY, USA, 2016, p. 28:1–28:13.
