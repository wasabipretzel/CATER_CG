# CATER_CG
New data splits of compositional generalization on CATER dataset

- The newly proposed data split consists of train, val, test, val_swap, and test_swap, all of which are composed of short clips extracted from the CATER video dataset.
- The entire split is structured into three disjoint label sets: A, B, and C. The train, val, and test splits contain clips associated with label sets A and C, while the val_swap and test_swap splits consist of clips associated with label sets B and C.
- Three disjoint label sets can be found in target/cg_disjoint_labels.npy

- The name of each clip is structured as `(CATER video name)__(start frame)__(end frame)__(label of the starting atomic action)__(label of the last atomic action)__(index)`. Therefore, the CATER dataset videos can be segmented into clips by slicing them based on their start and end frames.
