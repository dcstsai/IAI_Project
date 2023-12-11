# 95891 Introduction to Artificial Intelligence - Group Project
### What To Buy: A Recommendation System for Amazon Based on Co-Purchasing Behavior

**I. Team Members**

David Tsai (chishiut), Judy Tsai (weiyit), Lili Chen (lilichen), Yilin Lyu (yilinlyu), Abigail Zhang (tianaiz)

**II. Project Description**

Our goal is to analyze and leverage the co-purchasing behavior of Amazon customers to make product recommendations and uncover patterns and insights related to product associations. This can help find potential sales boost opportunities and improve customer’s shopping experience.

**III. Our Approach**

We divide our groups into two subteams based on the models we use. The GNN team (David, Judy, and Lili) uses the graph neural network (GNN) model and the ML team (Yilin and Abigail) focuses on machine learning models. The two teams then work together to analyze the results.

**IV. Data Sources**

The datasets are available at Stanford Large Network Dataset Collection: https://snap.stanford.edu/data/

We use the following datasets for this project:
1. Amazon product co-purchasing network
- https://snap.stanford.edu/data/amazon0302.html
- https://snap.stanford.edu/data/amazon0312.html
- https://snap.stanford.edu/data/amazon0505.html
- https://snap.stanford.edu/data/amazon0601.html
2. Amazon product co-purchasing network metadata, including title, salesrank, etc.
- https://snap.stanford.edu/data/amazon-meta.html

All datasets, including the ones we preprocessed, are available at: https://drive.google.com/drive/folders/1upHgc2Mli8AeIidkWyZ8vGL46W3P7B8q?usp=sharing


**V. References**
- Introduction to GNN https://distill.pub/2021/gnn-intro/
- PyG - a library built upon PyTorch to train GNNs https://pyg.org/
- Recommender systems with GNNs https://medium.com/stanford-cs224w/recommender-systems-with-gnns-in-pyg-d8301178e377
- An implementation using the same dataset we use https://wandb.ai/manan-goel/gnn-recommender/reports/Recommending-Amazon-Products-using-Graph-Neural-Networks-in-PyTorch-Geometric--VmlldzozMTA3MzYw
- Paper by Amazon https://www.amazon.science/publications/recommending-related-products-using-graph-neural-networks-in-directed-graphs
- Building Recommender System with GNN - Part2: LightGCN Self-Supervised Learning https://www.youtube.com/watch?v=h1zxhx815Fk
- Graph Convolutional Networks https://tkipf.github.io/graph-convolutional-networks/
- GraphSMOTE: Imbalanced Node Classification on Graphs with Graph Neural Networks https://arxiv.org/abs/2103.08826
- PyG Colab Notebooks - Link Predictions on MovieLens https://colab.research.google.com/drive/1xpzn1Nvai1ygd_P5Yambc_oe4VBPK_ZT?usp=sharing#scrollTo=Ogh615ka9I2c
- Graph Neural Network Series | Node Embedding https://medium.com/the-modern-scientist/graph-neural-networks-series-part-3-node-embedding-36613cc967d5
- Inductive Representation Learning on Large Graphs https://arxiv.org/abs/1706.02216
- Link Prediction Based on Graph Neural Networks https://papers.nips.cc/paper/2018/file/53f0d7c537d99b3824f0f99d62ea2428-Paper.pdf
- GraphSAGE: Scaling up Graph Neural Networks https://mlabonne.github.io/blog/posts/2022-04-06-GraphSAGE.html
- DGL: Link Prediction Using Graph Neural Networks https://docs.dgl.ai/en/0.8.x/tutorials/blitz/4_link_predict.html
- Application of Machine Learning to Link Prediction https://cs229.stanford.edu/proj2016/report/JulianLu-Application-of-Machine-Learning-to-Link-Prediction-report.pdf
- Collaborative Filtering - Recommendation system through ML https://developers.google.com/machine-learning/recommendation/collaborative/basics
- Recommendation system design https://www.itransition.com/machine-learning/recommendation-systems#:~:text=Recommendation%20engines%20in%20this%20category,survey%20customers'%20perceptions%20of%20products
- Prediction on co-purchasing on the same dataset (Logistic regression, KNN, Decision Tree, Adaboost etc) https://cseweb.ucsd.edu/classes/sp15/cse190-c/reports/sp15/039.pdf
- Matrix Factorization Techniques for Recommender Systems https://ieeexplore.ieee.org/document/5197422
- Collaborative Filtering for Implicit Feedback Datasets https://ieeexplore.ieee.org/document/4781121
- Fast Matrix Factorization for Online Recommendation with Implicit Feedback https://arxiv.org/abs/1708.05024
- Wu, Q., Zhang, H., Gao, X., Yan, J., & Zha, H. (2021, July). Towards open-world recommendation: An inductive model-based collaborative filtering approach. In International Conference on Machine Learning (pp. 11329-11339). PMLR. https://proceedings.mlr.press/v139/wu21j.html


