# textmining-hazardouswate

Living review framework for better policy design and management of hazardous waste

Author: Uyen Le

The project developed a living review framework to assess the Australian hazardous waste management domain literature during 2022-2023 period. The framework involved class merging using BERTopic, supervised text classification using XGBoost, keyword extraction and unsupervised LDA topic modelling.

The framework is illustrated as follows:

![living review](https://github.com/uyenlk/textmining-hazardouswate/assets/134372504/3fc7f793-0e0a-43b4-a9c8-61f5d012422a)

As part of the project, we published 3 datasets: 

(1) labelled_data_global.csv: This data set includes 126 labelled global articles which was manually labelled by a hazardous waste domain expert. This multi-class data set involves 8 different waste classes: soil, soil and chemical, water, water and chemical, air, air and chemical, chemical, metal

(2)labelled_data_merge.csv: This data set includes 126 labelled global articles from labelled_data_global set after class merging and only involves 5 classes: soil. water, air, chemical, metal 

(3)audatafinal.csv: This data set includes 678 Australian articles labelled with high confidence using XGBoost trained on labelled_data_merge set


