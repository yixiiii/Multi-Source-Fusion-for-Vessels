## Multi-Source Fusion Dataset for Intelligent Vessel(WHUT-MSFVessel)
The constructed multi-source fusion dataset is available at:  https://pan.baidu.com/s/1vnE5y9l18z2c-ZFSRfbD-g   
 
The dataset is currently being organized and will be uploaded progressively.

The WHUT-MSFVessel dataset consists the data collect from different sensors, include AIS receiver, marine radar, and visible camera. All the data are synchronously collected, AIS data is stored in its raw coded format as text formats with timestamp, and radar and visible data are provided as continuous frame, each named with timestamp. All timestamps are accurate to the millisecond. The original format of the multi-source data in the dataset is as follow: 
![MSF](https://github.com/user-attachments/assets/e5e8022b-8cbd-4df7-8d48-62a885676850)
## Details
The data collection platform is positioned perpendicular to the Yangtze River, with deployment coordinates at [114.306087, 30.563549] and a height of 20 meters above the water surface. The data collection spanned 12 months to ensure sufficient diversity in the dataset and each scene data contains the following files:
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

https://github.com/user-attachments/assets/bae12d8c-4342-49fa-a267-440c7b98e2e4

https://github.com/user-attachments/assets/e3d3268f-896d-4871-8b21-02edd6f0cbc3



