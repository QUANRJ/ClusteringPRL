# Clustering for Protein Representation Learning
This is the official implementation of "Clustering for Protein Representation Learning" (Accepted at CVPR 2024).

![](framework.pdf)

>[Clustering for Protein Representation Learning]([https://arxiv.org/abs/2403.16646](https://openaccess.thecvf.com/content/CVPR2024/papers/Quan_Clustering_for_Protein_Representation_Learning_CVPR_2024_paper.pdf)) <br>
>[Ruijie Quan](https://scholar.google.com/citations?user=WKLRPsAAAAAJ&hl=en), [Wenguan Wang](https://sites.google.com/view/wenguanwang), [Fan Ma](https://scholar.google.com/citations?user=FyglsaAAAAAJ&hl=en), [Hehe Fan](https://scholar.google.com/citations?user=hVuflMQAAAAJ&hl=en), [Yi Yang](https://scholar.google.com/citations?hl=zh-CN&user=RMSuNFwAAAAJ&view_op=list_works)
>

## Abstract

Protein representation learning is a challenging task that aims to capture the structure and function of proteins from their amino acid sequences. Previous methods largely ignored the fact that not all amino acids are equally important for protein folding and activity. In this article, we propose a neural clustering framework that can automatically discover the critical components of a protein by considering both its primary and tertiary structure information. Our framework treats a protein as a graph, where each node represents an amino acid and each edge represents a spatial or sequential connection between amino acids. We then apply an iterative clustering strategy to group the nodes into clusters based on their 1D and 3D positions and assign scores to each cluster. We select the highest-scoring clusters and
use their medoid nodes for the next iteration of clustering, until we obtain a hierarchical and informative representation of the protein. We evaluate on four protein-related tasks: protein fold classification, enzyme reaction classification, gene ontology term prediction, and enzyme commission number prediction. Experimental results demonstrate that our method achieves state-of-the-art performance.


## Code

Coming soon...

## Citation

If you find this work useful in your research, please star our repository and consider citing:

```
@inproceedings{quan2024clustering,
  title={Clustering for protein representation learning},
  author={Quan, Ruijie and Wang, Wenguan and Ma, Fan and Fan, Hehe and Yang, Yi},
  booktitle={CVPR},
  year={2024}
}
```
