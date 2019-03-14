# ISLESChallenge
ISLES Challenges top entries

## ISLES 2018

| Author(s)    | Dim            | Network        | Loss Function | Augmentation | Dice coef(%)|
| :---         |     :---:      |    :---:      |     :---:      |     :---:    |        ---: |
| Tao Song  | 3D    |  U-shape network with atrous convolution   |Jaccard(IOU) + binary cross  entropy |random rotations, random crop and radial distortion|55.86|
| Pengbo Liu    | 2D       | Residual U-Net      | weighted cross-entropy loss + generalized dice loss | yes| 55.23|
| Chen et al|2.5D | Ensemble,  U-Net + others| | | | 
| Hu et al| 3D | deep residual + refinement module| Focal loss|yes | 52.26| 
| Clerigues et al|  | U-Net| | mid-sagital mirroring and elastic deformation| | 


## ISLES 2017

| Author(s)    | Dim            | Network        | Loss Function | Augmentation | Dice coef(%)|
| :---         |     :---:      |    :---:      |     :---:      |     :---:    |        ---: |
| Choi et al | 3D| residual U-Net + SPP |  | | 31|
|Monteiro et al | 3D| U-shaped | cross entropy + soft dice loss + CRF | | 30|
|Lucas et al | 3D| U-Nets | weighted dice loss  | | 29|
|Robben et al | 3D| DeepMedic like |  | elastic deformations + flips along the x-axis| 27|
