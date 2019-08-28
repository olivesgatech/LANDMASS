# Large North-Sea Dataset of Migrated  Aggregated Seismic Structures (LANDMASS)

At the [Center for Energy and Geo Processing (CeGP)](https://cegp.ece.gatech.edu/) and at the [OLIVES lab](https://ghassanalregib.com/), we have been working on creating big datasets for post-migrated seismic volumes.
The LANDMASS dataset is now available for development, testing, and benchmarking of various techniques aimed towards seismic applications such as retrieval, classification, machine learning … etc.

## Datasets in LANDMASS
#### LANDMASS-1
LANDMASS-1 contains 17667 small “patches” of size 99×99 pixels. It includes: 
* 9385 Horizon patches,
* 5140 chaotic patches,
* 1251 Fault patches, and
* 1891 Salt Dome patches.

The images have values in the range [-1,1]

Sample images: 

|Chaotic|Fault|Horizon|Salt Dome|
|:--:|:--:|:--:|:--:|
|![](https://github.com/olivesgatech/LANDMASS/blob/master/figures/LANDMASS1_Chaotic_Normalized.png)| ![](https://github.com/olivesgatech/LANDMASS/blob/master/figures/LANDMASS1_Faults_Normalized.png) | ![](https://github.com/olivesgatech/LANDMASS/blob/master/figures/LANDMASS1_Horizon_Normalized.png) | ![](https://github.com/olivesgatech/LANDMASS/blob/master/figures/LANDMASS1_SaltDome_Normalized.png)|

#### LANDMASS-2
LANDMASS-2 contains 4000 images of size 150x300 pixels. It includes: 
* 1000 Horizon images,
* 1000 chaotic images,
* 1000 Fault images, and
* 1000 Salt Dome images.

The images have values in the range [-1,1]


Sample images: 

|Chaotic|Fault|Horizon|Salt Dome|
|:--:|:--:|:--:|:--:|
|![](https://github.com/olivesgatech/LANDMASS/blob/master/figures/LANDMASS2_Chaotic_Normalized.png)| ![](https://github.com/olivesgatech/LANDMASS/blob/master/figures/LANDMASS2_Faults_Normalized.png) | ![](https://github.com/olivesgatech/LANDMASS/blob/master/figures/LANDMASS2_Horizon_Normalized.png) | ![](https://github.com/olivesgatech/LANDMASS/blob/master/figures/LANDMASS2_SaltDome_Normalized.png)|


## Folder Structure: 
```bash
LANDMASS
├── LANDMASS1
│   ├── chaotic
│   │   ├── chaotic_0001.mat
│   │   ├── chaotic_0002.mat
│   │   ├── ...
│   │   └── chaotic_5140.mat
│   ├── fault
│   │   ├── fault_0001.mat
│   │   ├── fault_0002.mat
│   │   ├── ...
│   │   └── fault_1251.mat
│   ├── horizon
│   │   ├── horizon_0001.mat
│   │   ├── horizon_0002.mat
│   │   ├── ...
│   │   └── horizon_1891.mat
│   └── salt dome
│   │   ├── saltdome_0001.mat
│   │   ├── saltdome_0002.mat
│   │   ├── ...
│   │   └── saltdome_5140.mat
├── LANDMASS2
│   ├── chaotic
│   │   ├── chaotic_0001.mat
│   │   ├── chaotic_0002.mat
│   │   ├── ...
│   │   └── chaotic_1000.mat
│   ├── fault
│   │   ├── fault_0001.mat
│   │   ├── fault_0002.mat
│   │   ├── ...
│   │   └── fault_1000.mat
│   ├── horizon
│   │   ├── horizon_0001.mat
│   │   ├── horizon_0002.mat
│   │   ├── ...
│   │   └── horizon_1000.mat
│   └── salt dome
│   │   ├── saltdome_0001.mat
│   │   ├── saltdome_0002.mat
│   │   ├── ...
│   │   └── saltdome_1000.mat
├── SAMPLES
│   ├── LANDMASS1_Chaotic_Normalized.png
│   ├── LANDMASS1_Fault_Normalized.png
│   ├── LANDMASS1_Horizon_Normalized.png
│   ├── LANDMASS1_SaltDome_Normalized.png
│   ├── LANDMASS2_Chaotic_Normalized.png
│   ├── LANDMASS2_Fault_Normalized.png
│   ├── LANDMASS2_Horizon_Normalized.png
│   └── LANDMASS2_SaltDome_Normalized.png
└── README
```


## Download 
In order to receive the download link, please fill out this [FORM](https://goo.gl/forms/at44srIuVaT6sYye2) to submit your information and agree the conditions of use. These information will be kept confidential and will not be released to anybody outside the CeGP administration team.

## Citation 

If you intend to use this dataset, we ask you to please cite it in your work as:

```BibTex:
@webpage{LANDMASS,
	Author = {Yazeed Alaudah and Ghassan AlRegib},
	Title = {LANDMASS Seismic Dataset},
	Url = {https://github.com/olivesgatech/LANDMASS},
	Year = {2015}}
```

## Related publications: 
* Y. Alaudah and G. AlRegib, "A Curvelet-Based Distance Measure for Seismic Images," in IEEE International Conference on Image Processing (ICIP), Québec City, Canada, Sep. 27-30 2015. [PDF][Code]
* Y. Alaudah, M. Alfarraj, and G. AlRegib, "Structure Label Prediction Using Similarity-Based Retrieval and Weakly-Supervised Label Mapping," in Geophysics, 2018. [PDF]
* M. Alfarraj, Y. Alaudah, Z. Long, and G. AlRegib, "Multiresolution Analysis and Learning for Computational Seismic Interpretation," in The Leading Edge, 2018. [PDF][Code]
* Z. Long, Y. Alaudah, M.A. Qureshi, Y. Hu, Z. Wang, M. Alfarraj, G. AlRegib, A. Amin, M. Deriche, S. Al-Dharrab, and H. Di, "A Comparative Study of Texture Attributes for Characterizing Subsurface Structures in Seismic Volumes," in Interpretation, vol. 6, no. 4, pp. 1055-1066, Oct. 2018. [PDF][Code]
* Z. Long, Y. Alaudah, M. Qureshi, M. Farraj, Z. Wang, A. Amin, M. Deriche, and G. AlRegib, "Characterization of Migrated Seismic Volumes Using Texture Attributes: A Comparative Study," in Expanded Abstracts of the SEG Annual Meeting, New Orleans, LA, Oct. 18-23 2015. [PDF][Code]
* Y. Alaudah, S. Gao, and G. AlRegib, "Learning to Label Seismic Structures With Deconvolution Networks and Weak Labels," in Expanded Abstracts of the SEG Annual Meeting, Anaheim, CA, Oct. 14-19 2018. [PDF]
