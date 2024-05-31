# GNN-heterograph
This was a fun project I did to train myself in GNNs. This code is built based of off DeepSnap tutorials (https://snap.stanford.edu/deepsnap/notes/colab.html) and a Stanford course on Machine learning with grapgs, CS224W (https://snap.stanford.edu/class/cs224w-2021/).
This code creates a directed bi-partite heterogeneous graph. The message passing layer passes the messages from the source nodes to the destination nodes through the directed edges where they are then aggregated and classified. The node-embeddings are also returned for further analysis using UMAP.
