
Classification of Malignant Mesothelioma

Pretrained ResNet -18, ResNet - 34, EfficientNet - B1 models were finetuned to classy mesothelioma cancer using histology whole slide images. The size of each whole slide image can ranges from 1gb - 3gb and can consume heavy computational power. Therefore, it is ideal to extract patches from each whole slide image using sliding window method and implement deep learning models on top of it after stain normalisation and tissue segmnetation. 

Tissue segmentation is seperating the white background and tissue sections in an image by using several imageprocessing techniques. Biopsy images comes in different colors due to staining intensity of Hematoxilyn and Eosin while preparing the tissue section after paraffin embedding. However, with the presence of different staining intensities, deep learning model may not generalise well on similar patterns with different colors. Therefore, Normalising the staining intensity of whole slide images is the most common method in image classification using whole slide images.
