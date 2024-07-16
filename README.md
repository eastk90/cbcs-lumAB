# cbcs-lumAB
Image Analysis-based Identification of High Risk ER-Positive, HER2-Negative Breast Cancers

Authors: Dong Neuck Lee, Yao Li, Linnea T. Olsson, Alina M. Hamilton, Benjamin C. Calhoun, Katherine A. Hoadley, J.S. Marron, Melissa A. Troester

## Data Structure
### data_dir/clinical_vars.csv
Subject-level clinical variables. Columns should contain subj_id, pam50_type, er_status, and her2_status.

### data_dir/patch_features.csv
patch-level image features extracted using VGG16. 'image' and 'patch_idx' are core, and patch indices. Columns 'feat_0', 'feat_1', ..., 'feat_510', 'feat_511' are image features.


