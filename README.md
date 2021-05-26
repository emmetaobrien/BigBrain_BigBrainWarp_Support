# BigBrain 3D ROIs

## BigBrain

The BigBrain is the brain of a 65 years old man with no neurological or psychiatric
diseases in clinical records at time of death. The brain was embedded in parafin and
sectioned in 7404 coronal histological sections (20 microns), stained for cell bodies.
The BigBrain is the digitized reconstruction of the hi-res histological sections 
(20 microns isotropic).

## Dataset content

This dataset contains MSM spherical transformations to resample labels and fields between the BigBrain surace to/from 3 other mahor referece surfaces: FreeSurfer's fsaverage, Human Connectome Project's (HCP) fs_LR, and CIVET's MNI152. This dataset has been derived from the BigBrain release 2015 
published in the [BigBrain Project website](https://bigbrainproject.org).

 The required files and some examples are provided here to illustrate how to use these transformations. Instructions are detailed to guide you through the conversion, mapping, and visualization steps. Using these examples, you should be able to resample any set of labels or field of your choosing (.annot, .label.gii, .shape.gii, .txt) between the BigBrain surface to/from the fsavg, fs_LR, and CIVET MNI152 surface templates. These transformations will also be included in the [BigBrainWarp Project](https://bigbrainwarp.readthedocs.io/en/latest/), a toolbox which aims to enable integration of BigBrain with neuroimaging and other neurobiological modalities.

You will need to install the following tools:

- [FreeSurfer](https://surfer.nmr.mgh.harvard.edu/fswiki/DownloadAndInstall)

- [HCP workbench](https://www.humanconnectome.org/software/get-connectome-workbench)

- [MSM](https://github.com/ecr05/MSM_HOCR): You do not need to install MSM, but it was used to produce the transformation spheres provided in this release.

Note: The brain-view surface viewer is part of the MNI CIVET tools and is difficult to install. You may alternately use [BrainBrowser](https://natacha-beck.github.io/brainbrowser/BrainBrowserSurfaceUI/) for visualizing .obj and .txt.



## Reference and more information

- [Lewis, L.B., Lepage, C.Y., Glasser, M.F., Coalson, T.S., Van Essen, D.C., and A.C. Evans: OHBM 2020 poster](https://drive.google.com/file/d/1vAqLRV8Ue7rf3gsNHMixFqlLxBjxtmc8/view?usp=sharing)

- [Slides for BigBrain Workshop Talk](https://drive.google.com/file/d/11dRgtttd2_FdpB31kDC9mUP4WCmdcbbg/view?usp=sharing)

The BigBrain dataset is the result of a collaborative effort between the
teams of Dr. Katrin Amunts and Dr. Karl Zilles (Forschungszentrum Jülich)
and Dr. Alan Evans (Montreal Neurological Institute). 

Amunts, K. et al.: "BigBrain: An Ultrahigh-Resolution 3D Human
Brain Model", Science (2013) 340 no. 6139 1472-1475, June 2013.
[https://www.sciencemag.org/content/340/6139/1472.abstract](https://www.sciencemag.org/content/340/6139/1472.abstract)

For more information please visit the [BigBrain Project website](https://bigbrainproject.org).