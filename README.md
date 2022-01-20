# Colin2MNI
I havn't been easily able to find a transformation between Colin27_t1_tal space and MNI_152_2mm space. Thought I would share one. The inverse is too large, but you can generate one using invwarp. For example: 

invwarp --ref=/Users/alex/Downloads/mni_colin27_1998_nifti/colin27_t1_tal_lin.nii --warp=/Users/alex/Downloads/mni_colin27_1998_nifti/my_nonlinear_transf --out=/Users/alex/Downloads/mni_colin27_1998_nifti/my_nonlinear_transf_inverted

