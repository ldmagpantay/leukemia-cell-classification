![cell image](/resources/leukemia-cell.png)
*img source: https://cdn.the-scientist.com/assets/articleNo/68120/aImg/40254/aml-thumb-l.png*
# <b><font size=10> Leukemia Cell Classification </b></font>

<p><font size=3> Cancer is a disease in which some of the body's cells grow uncontrollably and spread all throughout the other parts of the body. It can start in almost anywhere in the human body. It is commonly caused by changes to human genes that control the way cells function, especially on how they grow and divide (National Cancer Institute). 

According to Centers for Disease and Control Prevention (2021), cancer was the second leading cause of death next to heart disease, in US in year 2019. There are approximately 600,000 cancer deaths. Among children, one of the most common type of cancer is the **Acute Lymphoblastic Leukemia (ALL)** which accounts for approximately 25% of the pediatric cancers. It is cancer of the blood and bone marrow. The bone marrow creates a huge amount of immature lymphocytes (a type of white blood cell) and usually gets worse quickly if not treated (National Cancer Institute). 

The task of identifying immature leukemic blasts from normal cells under the microscope is very challenging due to morphological similarity and thus the ground truth labels were annotated by an expert oncologist. 

The detection problem that I want to solve is the identification of normal cells and cells that were infected with cancer with the implementation of Deep Learning. 

In this work, I've created a classification and object detection model that will detect Leukemic Cell in an image using Deep Learning (transfer-learning based YoloV3 model). The dataset came from *[Kaggle](https://www.kaggle.com/andrewmvd/leukemia-classification)*. It contains different images of cells that have been segmented from microscopic images and representative of images in the real world. It has total of 15,135 images from 118 patients and are labelled as "normal" and "leukemia blast". The size of individual image is 450x450 pixels and was originally in bmp file format. For the purpose of research, the images that will be used in model traning and evaluation were coverted into JPG format. 

Data citation: Gupta, A., & Gupta, R. (2019). ALL Challenge Dataset of ISBI 2019 [Dataset]. The Cancer Imaging Archive. https://doi.org/10.7937/tcia.2019.dc64i46r <p>

This work is documented and published in **2022 International Conference on Decision Aid Sciences and Applications (DASA)**

L. D. C. Magpantay, H. D. Alon, Y. D. Austria, M. P. Melegrito and G. J. O. Fernando, "A Transfer Learning-Based Deep CNN Approach for Classification and Diagnosis of Acute Lymphocytic Leukemia Cells," 2022 International Conference on Decision Aid Sciences and Applications (DASA), 2022, pp. 280-284, [doi: 10.1109/DASA54658.2022.9765000.](https://doi.org/10.1109/DASA54658.2022.9765000)

