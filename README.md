# VArcGIS
A remote sensing image dataset constructed from the ArcGIS World Imagery online image resource using the V-RSIR tool. 

<b>Author</b>: Dongyang Hou

## Data description

VArcGIS is a remote sensing image dataset constructed from the ArcGIS World Imagery online image resource using the V-RSIR tool. It covers 38 classes (see Table 1) and contains a total of 59,071 images. Each class contains at least 1500 images with spatial resolutions ranging from 0.07 m to 19.11 m. Figure 1 represents the spatial distribution of the VArcGIS dataset. Without affecting the data accuracy, the team converted the original dataset from RGBA four-channel to RGB three-channel and converted the images from tiff format to jpg format on December 14, 2021, reducing the dataset storage space from 8.08 GB to 2.09 GB.

### Fig. 1 Spatial distribution of images from the VArcGIS

![image-20230328130111559](https://github.com/GeoRSAI/VArcGIS/blob/master/figures/spatial_distribution.jpg)

### Table 1 Class name

| Class               | Code | Class            | Code | Class                      | Code |
| ------------------- | ---- | ---------------- | ---- | -------------------------- | ---- |
| airplane            | 0    | forest           | 14   | runway                     | 28   |
| baseball field      | 1    | freeway          | 15   | runway marking             | 29   |
| basketball court    | 2    | golf course      | 16   | shipping yard              | 30   |
| beach               | 3    | harbor           | 17   | solar panel                | 31   |
| bridge              | 4    | intersection     | 18   | sparse residential         | 32   |
| cemetery            | 5    | mobile home park | 19   | storage tank               | 33   |
| chaparral           | 6    | nursing home     | 20   | swimming pool              | 34   |
| christmas tree farm | 7    | oil gas field    | 21   | tennis court               | 35   |
| closed road         | 8    | oil well         | 22   | transformer station        | 36   |
| coastal mansion     | 9    | overpass         | 23   | wastewater treatment plant | 37   |
| crosswalk           | 10   | parking lot      | 24   |                            |      |
| dense residential   | 11   | parking space    | 25   |                            |      |
| ferry terminal      | 12   | railway          | 26   |                            |      |
| football field      | 13   | river            | 27   |                            |      |

## Download link
Download dataset from the following link: (We recommend using the compressed version.)
- [Compressed version (code is `xhkv`)](https://pan.baidu.com/s/1KRKnr5R2UTfnOuGwQhsX5Q)
- [Uncompressed version (code is `hq5h`)](https://pan.baidu.com/s/1FaLtuwlVg-PjCurrLwasUQ)

## License
This dataset is for scientific research use only and should not be used commercially. When using it, please cite the following references. 

[1] Hou Dongyang; Miao Zelang; Xing Huaqiao*; Wu Hao*; V-RSIR: an Open Access Web-based Image Annotation Tool for Remote Sensing Image Retrieval, IEEE Access. 2019, 7: 83852-83862.

[2] Hou Dongyang; Miao Zelang; Xing Huaqiao*; Wu Hao*; Two Novel Benchmark Datasets from ArcGIS and Bing World Imagery for Remote Sensing Image Retrieval, International Journal of Remote Sensing. 2021, 42(1): 240-258. doi: 10.1080/01431161.2020.1804090.

## Contact

For questions about the dataset, please contact me by email houdongyang1986@163. com.
