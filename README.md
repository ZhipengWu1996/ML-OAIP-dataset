# ML-OAIP-dataset
ML-OAIP is the first multimodal remote sensing dataset for semantic segmentation and height estimation that integrates high-resolution SAR interferometric phase images, optical imagery, and SAR amplitude images.

*Introduction*\
ML-OAIP dataset consists of 80 high-resolution optical images (2048 × 2048 pixels), repeat-pass SAR Single Look Complex(SLC) data of the same area, and corresponding semantic and height labels. The image coverage primarily focuses on the central urban area of Amsterdam, the capital of the Netherlands, and extends to some surrounding rural areas. The region is predominantly flat plain, with elevations ranging from -8m to 18m. Diverse, unevenly distributed ground objects with significant scale variations pose substantial challenges for both SS and HE tasks.\
\
![image](https://github.com/ZhipengWu1996/ML-OAIP-dataset/blob/main/1.png)\
\
**Semantic labels**: The ground target semantic labels were obtained using open-source annotation software based on optical imagery. The annotation categories include buildings(1), woodlands(2), roads(3), water(4), and background(5).\
**Height labels**: The height labels are derived from the publicly available AHN DEM  data in Google Earth Engine, a 0.5m DSM generated from LiDAR data, covering the entire Netherlands. The missing values in the height map are filled using nearest-neighbor interpolation, assisted by the semantic labels.\
The following are examples from the dataset.\
![image](https://github.com/ZhipengWu1996/ML-OAIP-dataset/blob/main/2.png)

**Note:**\
*We have currently uploaded only a small subset of the dataset samples. The full dataset will be released promptly after the publication of our paper !*

