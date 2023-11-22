# SAT4pKa
Graph Transformer Based Transfer Learning for Aqueous pKa Prediction of Organic Small Molecules
The acid-base dissociation constant (pKa) is an essential physicochemical parameter that indicates the extent of proton dissociation. However, accurately predicting pKa values is still challenging due to limited data availability for organic small molecules in aqueous solutions. In this work, we propose an open-source pKa prediction tool based on Graph Transformer, which combines the graph neural network and transformer to take both local and global information into account. To address the limitation of data scarcity, the experimental dataset is expanded, while transfer learning is employed by pre-training on the ChEMBL (computational) dataset and fine-tuning on the experimental dataset. The performance and generalization of the obtained models are comprehensively evaluated on both internal and external test sets. 
