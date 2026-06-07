## Multi-Source Fusion Dataset for Intelligent Vessel(WHUT-MSFVessel)
The multi-source fusion dataset is partly available at:  https://pan.baidu.com/s/100KGjcVkTfsBWa3NwGPxIA 

password: WHUT   

For more content, please contact the corresponding author.

The WHUT-MSFVessel dataset consists the data collect from different sensors, include AIS receiver, marine radar, and visible camera. All the data are synchronously collected, AIS data is stored in its raw coded format as text formats with timestamp, and radar and visible data are provided as continuous frame, each named with timestamp. All timestamps are accurate to the millisecond. The original format of the multi-source data in the dataset is as follow: 
<img width="2171" height="1055" alt="20260607203417_16_25" src="https://github.com/user-attachments/assets/0c83c6ff-e00d-4d62-a339-1c8cadbc4fce" />



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

<img width="649" alt="diff_weather" src="https://github.com/user-attachments/assets/3b7dcea6-4010-45db-bde2-0d671e8f08e4">  

https://github.com/user-attachments/assets/bae12d8c-4342-49fa-a267-440c7b98e2e4

https://github.com/user-attachments/assets/e3d3268f-896d-4871-8b21-02edd6f0cbc3



