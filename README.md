<!--
# Harmonizing Light and Darkness: Nighttime Image Deraining Using Color Space Transformation

Qiyuan Guan, Shumin Fan, Jiyu Jin, Guiyue Jin, Tianyu Song, Pengpeng Li, Xiang Chen, and Kui Jiang

><font size=5>**Abstract:**</font>
>*Nighttime image deraining presents unique challenges compared to daytime scenarios, primarily due to the complex characteristics of nighttime scenes and the limited availability of datasets that effectively capture the interplay between lighting and rain streaks. In this paper, we contribute a high-quality nighttime image deraining dataset, BDD-NightRain, consisting of 5,600 synthetic nighttime rain images with higher realism and harmony for driving scenes. Furthermore, we develop a two-stage Nighttime Rain Removal Network (NRRNet) that leverages color space transformation. Specifically, the coarse processing stage focuses on rain streak removal in the Y channel, where luminance contrast is most pronounced under nighttime rain conditions, while the fine processing stage further refines the deraining results of the previous stage. In addition, we introduce coordinate-based implicit neural representations between these two stages to guide the model's focus toward areas with appropriate illumination. Extensive experiments show that our method outperforms others in removing rain streaks from nighttime scenes, with potential applications in nighttime object detection.*
---

-->


## **🔥 Dataset**

<!--
### Dataset pipeline
![image](https://github.com/guanqiyuan/NRRNet/blob/main/figs/pipeline.png)
-->

### Dataset structure

```tex
BDD-NightRain
    |
    |--images
    |    |--train
    |    |    |--input   (5000 images)
    |    |    |--target  (5000 images)
    |    |
    |    |--validation
    |    |    |--input   (500 images)
    |    |    |--target  (500 images)
    |    |  
    |    |--test
    |    |    |--input   (100 images)
    |    |    |--target  (100 images)
    |
    |--labels
    |    |--train      (5000 json)
    |    |--validation (500 json)
    |    |--test       (100 json)
```

### ⬇️ Download
You can download the BDD-NightRain dataset by [Baidu Cloud](https://pan.baidu.com/s/12nypp2MpLGN-1SsL-eNURw)(code：bddn).


<!--
## **✨ Network Architecture**
![image](https://github.com/guanqiyuan/NRRNet/blob/main/figs/network.png)

-->

## Training
The code will be released soon.


## Testing
The code will be released soon.







## Acknowledgement
This dataset is based on [BDD100K](https://github.com/bdd100k/bdd100k). Thanks for their greate work!
