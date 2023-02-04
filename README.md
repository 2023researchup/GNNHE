
## GNNHE--Combining GNN and Heuristic Encoding.


About
-----
We conduct experiments on four link prediction datasets from  Open Graph Benchmark (OGB). ComRH outperforms the top competitors on four OGB benchmark datasets by large margins, gaining new state-of-the-arts, 

96.2\% Hits@20 on ogbl-ddi, 

58.1\% Hits@50 on ogbl-collab, 

63.5\% Hits@100 on ogbl-ppa, 

88.6\% MRR on ogbl-citation2. 

Further empirical study shows that the link heuristics can boost the prediction performance on sparse graphs and representation learning contributes more on very dense graphs.

Requirements
------------

Latest tested combination: Python 3.8.5 + PyTorch 1.10.0 + PyTorch\_Geometric (cuda 102+PyTorch1.10.0) + OGB 1.3.1.

Install python basic libraries 

Install [PyTorch](https://pytorch.org/)

Install [PyTorch\_Geometric](https://pytorch-geometric.readthedocs.io/en/latest/notes/installation.html)

Install [OGB](https://ogb.stanford.edu/docs/home/)

<!-- Usages -->
------
<!-- 
### Contents description

    main_pred.py, utils.py, models.py -->
    






