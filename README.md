# ISLESChallenge
ISLES Challenges top entries

## ISLES 2018

| Author(s)    | Dim            | Network        | Loss Function | Augmentation | Dice coef(%)|
| :---         |     :---:      |    :---:      |     :---:      |     :---:    |        ---: |
| Tao Song  | 3D    |  U-shape network with atrous convolution   |Jaccard(IOU) + binary cross  entropy |random rotations, random crop and radial distortion|55.86|
| Pengbo Liu    | 2D       | Residual U-Net      | weighted cross-entropy loss + generalized dice loss | yes| 55.23|
| Yu Chen, Yuexiang Li, and Yefeng Zheng |2.5D | Ensemble,  U-Net + others| | | | 
| Xiaojun Hu, Weilin Huang, Sheng Guo, and Matthew R. Scott | 3D | deep residual + refinement module| Focal loss|yes | 52.26| 
| Albert Cl`erigues, Sergi Valverde, Jose Bernal, Kaisar Kushibar, Mariano Cabezas, Arnau Oliver, and Xavier Llad ́o |  | U-Net| | mid-sagital mirroring and elastic deformation| | 
