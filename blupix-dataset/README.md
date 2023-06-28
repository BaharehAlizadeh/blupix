# Blupix Dataset

## Overview:

| Dataset  | Description | Link | Used in paper |
| ------------- | ------------- | ------------- | ------------- |
| Blupix train v.2021.2  | Contains 800 annotated photos of stop signs for training the object detection model |  | 
| Blupix test v.2020.1  | Contains 186 annotated paired photos of stop signs (before and after a flood) for testing the object detection model | |
| Blupix test v.2021.1  | Contains 225 annotated paired photos of stop signs (before and after a flood) for testing the object detection model| |
| Blupix test v.2022.1  | Contains 300 annotated paired photos of stop signs (before and after a flood) for testing the object detection model | |



## Blupix trainining set
### Blupix train v.2021.2
![img2](blupix-dataset-fig1.png)

## Blupix test set
The dataset is designed for testing the trained model and comprises paired photos of stop signs captured before and after a flood event. It encompasses various information, including the photo name (photo ID), country, state, and city (the location of the stop sign in the photo), longitude and latitude (precise coordinates of the stop sign), source (where the photo was sourced from), date taken (when the photo was captured), date saved (when the photo was added to the dataset), flood name (if known), searching keywords (keywords used to find the photos), post-flood link (link to post-flood photos), Google Street View link (link to pre-flood photo on Google Street View), comment (any additional remarks about the photo), and found by (name of the study personnel who discovered the photo). The last three columns in the dataset indicate the presence of the photo in the three different versions of the dataset.


### Blupix test set versions
- Blupix test v.2020.1
Contains 186 paired photos of stop signs
- Blupix test v.2021.1
Contains 225 paired photos of stop signs
- Blupix test v.2022.1
Contains 300 paired photos of stop signs

Note: The photos in the Blupix dataset are not mutually exclusive, rather they have been cumulated in each version of the dataset. Meaning that, Blupix test v.2021.1 contains all photos in the Blupix test v.2020.1 plus 39 additional photos (186 + 39 = 225). Also, Blupix test v.2022.1 contains all photos in the Blupix test v.2020.1 (and Blupix test v.2021.1) plus 75 additional photos (225 + 75 = 300). 




## Credits:

The Blupix datasets consist of photos and metadata gathered through a collaborative effort involving study personnel, including Dr. Bahareh Alizadeh (Ph.D. graduate from Texas A&M University), and Nathan Young (Ph.D. student of Texas A&M University), as well as contributions from the general public through crowdsourcing.
