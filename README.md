# Large North-Sea Dataset of Migrated  Aggregated Seismic Structures (LANDMASS)

At the Center for Energy and GeoProcessing (CeGP), we have been working on creating big datasets for post-migrated seismic volumes.
The LANDMASS dataset is now available for development, testing, and benchmarking of various techniques aimed towards seismic applications such as retrieval, classification, machine learning … etc.

# Datasets in LANDMASS
## LANDMASS-1
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

## LANDMASS-2
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


# Folder Structure: 
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


# Download 
In order to receive the download link, please fill out this [FORM](https://goo.gl/forms/at44srIuVaT6sYye2) to submit your information and agree the conditions of use. These information will be kept confidential and will not be released to anybody outside the CeGP administration team.

