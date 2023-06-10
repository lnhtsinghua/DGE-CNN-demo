# DGE-CNN-demo
DGE-CNN demo for 2D-to-3D holographic display based on depth gradient extracting module and CNN network\n

"This source code is for training DGE-CNN network to recover depth map from single RGB 2D input"\n
"The output depth map is boundary-enhanced and will be used for layer-based angular spectrum calculation of 3D hologram"\n
"DGE module is packed in loss_gd in utils.py, to generate boundary-enhanced depth maps, train the network with loss_gd"\n

Author: Ninghe Liu (lnh20@mails.tsinghua.edu.cn)\n

# Usage
run train.py to train the DGE-CNN network, you can choose the pretrained network we provided for easy convergence\n
run inference.py to predict the boundary-enhanced depth map for input 2D image\n
run segment.py to conduct pixel-average slicing according to predicted depth map and input 2D image\n

# Data
Download the NYU Depth Dataset V2 Labelled Dataset : http://horatio.cs.nyu.edu/mit/silberman/nyu_depth_v2/nyu_depth_v2_labeled.mat.\n
Download the Make3D Dataset: http://make3d.cs.cornell.edu/data.html\n
Or we have provided our back up NYU Depth Dataset V2 data that goes with our demo\n
Back up link (data and source code): \n

# Reference
N. Liu, Z. Huang, Z. He and L. Cao, "DGE-CNN: 2D-to-3D holographic display based on depth gradient
extracting module and CNN network" Already submitted to Optics Express\n

All rights reserved
