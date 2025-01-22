# CATER_CG
New data splits of compositional generalization on CATER dataset

- The newly proposed data split consists of train, val, test, val_swap, and test_swap, all of which are composed of short clips extracted from the CATER video dataset.
- The entire split is structured into three disjoint label sets: A, B, and C. The train, val, and test splits contain clips associated with label sets A and C, while the val_swap and test_swap splits consist of clips associated with label sets B and C.
- Three disjoint label sets can be found in split_info/task1_cg/disjoint_set_labels.json, task2_cg/disjoint_set_labels.json
