# MGIML_WPY
MGIML: Cancer Grading with Incomplete Radiology-Pathology Data via Memory Learning and Gradient Homogenization. 

Abstract: Taking advantage of multi-modal radiology-pathology data with complementary clinical information for cancer grading is helpful for doctors to improve diagnosis efficiency and accuracy. However, radiology and pathology data have distinct acquisition difficulties and costs, which leads to incomplete-modality data being common in applications. In this work, we propose a Memory- and Gradient-guided Incomplete Modal-modal Learning (MGIML) framework for cancer grading with incomplete radiology-pathology data. Firstly, to remedy missing-modality information, we propose a Memory-driven Hetero-modality Complement (MH-Complete) scheme, which constructs modal-specific memory banks constrained by a coarse-grained memory boosting (CMB) loss to record generic radiology and pathology feature patterns, and develops a cross-modal memory reading strategy enhanced by a fine-grained memory consistency (FMC) loss to take missing-modality information from well-stored memories. Secondly, as gradient conflicts exist between missing-modality situations, we propose a Rotation-driven Gradient Homogenization (RG-Homogenize) scheme, which estimates instance-specific rotation matrices to smoothly change the feature-level gradient directions, and computes confidence-guided homogenization weights to dynamically balance gradient magnitudes. By simultaneously mitigating gradient direction and magnitude conflicts, this scheme well avoids the negative transfer and optimization imbalance problems. Extensive experiments on CPTAC-UCEC and CPTAC-PDA datasets show that the proposed MGIML framework performs favorably against state-of-the-art multi-modal methods on missing-modality situations.

This work is early accepted by IEEE TMI, we will publish the source code as soon as possible.
