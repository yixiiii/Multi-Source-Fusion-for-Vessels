# Multi-Source-Fusion-for-Vessels
Surface vessels detection and tracking method and datasets with multi-source data fusion in real-world complex scenarios
## Multi-Source Fusion Dataset for Intelligent Vessel(WHUT-MSFVessel)
The constructed multi-source fusion dataset is available at:  https://pan.baidu.com/s/1vnE5y9l18z2c-ZFSRfbD-g   
Pass Code: whut

The WHUT-MSFVessel dataset consists the data collect from different sensors, include AIS receiver, marine radar, and visible camera. All the data are synchronously collected, AIS data is stored in its raw coded format as text formats with timestamp, and radar and visible data are provided as continuous frame, each named with timestamp. All timestamps are accurate to the millisecond. The original format of the multi-source data in the dataset is as follow: 
![MSF](https://github.com/user-attachments/assets/e5e8022b-8cbd-4df7-8d48-62a885676850)
## Details
The data collection platform is positioned perpendicular to the Yangtze River, with deployment coordinates at [114.306087, 30.563549] and a height of 20 meters above the water surface. The data collection spanned 12 months to ensure sufficient diversity in the dataset and 22 scenearios are selected to constructed the WHUT-MSFVessel dataset and each scene data contains the following files:
```  
WHUT-MSFVessel/  
│  
├── scene01/
│   ├── radar_images/
│   │   ├── 2364714282.jpg
│   │   ├── 2364716530.jpg  
│   │   └── ...
│   ├── visible_images/
│   │   ├── 2364716724.jpg
│   │   ├── 2364717351.jpg  
│   │   └── ...
│   ├── AIS.txt 
│   ├── radar_track_gt.csv
│   │   ├──<frame>, <ID>, <Bbox_left>, <Bbox_top>, <Bbox_width>, <Bbox_height>, 1, -1, -1, -1
│   │   ├──<frame>, <ID>, <Bbox_left>, <Bbox_top>, <Bbox_width>, <Bbox_height>, 1, -1, -1, -1
│   │   └──...
│   ├── radar_video.mp4  
│   ├── visible_track_gt.csv
│   │   ├──<frame>, <ID>, <Bbox_left>, <Bbox_top>, <Bbox_width>, <Bbox_height>, 1, -1, -1, -1
│   │   ├──<frame>, <ID>, <Bbox_left>, <Bbox_top>, <Bbox_width>, <Bbox_height>, 1, -1, -1, -1
│   │   └──...
│   └── visible_video.mp4  
│  
├──scene02
│   ├── ...
│   └── ...
└── ...
```  
The WHUT-MSFVessel dataset covers a variety of weather conditions, include sunny, cloudy, rainy, and foggy, fully reflecting the environmental in real navigating scenarios.  

<img width="649" alt="diff_weather" src="https://github.com/user-attachments/assets/3b7dcea6-4010-45db-bde2-0d671e8f08e4">  

More detailed information about different scenarios is provided in the following table. The "NR", "NV", "MN", and "OC" represent the total number of radar target, the  total number of visible target, the maximum number of targets in camera view, and the number of occluded targets, respectively.    
| Scene | Duration | NR | NV | MN | OC | Weather |
| --- | --- | --- | --- | --- | --- | --- |
| scene01 | 09m06s | 12 | 4 | 3 | 1 | Sunny |
| scene02 | 04m20s | 25 | 7 | 6 | 3 | Cloudy |
| scene03 | 08m20s | 21 | 10 | 9 | 1 | Cloudy |
| scene04 | 07m01s | 17 | 6 | 5 | 4 | Rainy |
| scene05 | 07m16s | 15 | 6 | 5 | 2 | Foggy |
| scene06 | 15m20s | 32 | 10 | 6 | 4 | Sunny |
| scene07 | 11m50s | 11 | 5 | 6 | 0 | Sunny |
| scene08 | 14m54s | 30 | 11 | 6 | 4 | Sunny |
| scene09 | 18m38s | 17 | 10 | 6 | 3 | Sunny |
| scene10 | 10m07s | 19 | 8 | 6 | 2 | Cloudy |
| scene11 | 21m22s | 12 | 8 | 6 | 0 | Cloudy |
| scene12 | 13m21s | 20 | 12 | 6 | 5 | Cloudy |
| scene13 | 18m16s | 18 | 7 | 6 | 0 | Rainy |
| scene14 | 14m48s | 21 | 5 | 6 | 1 | Rainy |
| scene15 | 21m23s | 25 | 6 | 6 | 2 | Rainy |
| scene16 | 17m02s | 18 | 7 | 6 | 2 | Rainy |
| scene17 | 23m12s | 33 | 9 | 6 | 3 | Rainy |
| scene18 | 30m17s | 19 | 6 | 6 | 2 | Foggy |
| scene19 | 21m45s | 15 | 5 | 6 | 0 | Foggy |
| scene20 | 19m24s | 20 | 9 | 6 |  2 | Foggy |
| scene21 | 31m36s | 27 | 9 | 6 | 0 | Foggy |
| scene22 | 41m07s | 31 | 12 | 6 | 4 | Foggy |



https://github.com/user-attachments/assets/bae12d8c-4342-49fa-a267-440c7b98e2e4

https://github.com/user-attachments/assets/e3d3268f-896d-4871-8b21-02edd6f0cbc3



