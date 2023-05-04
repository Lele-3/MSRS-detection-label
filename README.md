# MSRS-detection-label
This is the detection label of [MSRS dataset](https://github.com/Linfeng-Tang/MSRS).
The label contains three categories $i.e.$ person, bicycle and car.
We give annotations for fusion images, infrared images, and visible images respectively. 

~~~
.
├─fusion
│  ├─test    # 361 images with 893 person labels, 127 bicycle labels and 461 car labels
│  └─train   # 1083 images with 2925 person labels, 641 bicycle labels and 1355 car labels
│          
├─infrared
│  ├─test    # 361 images with 1174 person labels, 242 bicycle labels and 379 car labels
│  └─train   # 1083 images with 3733 person labels, 709 bicycle labels and 1139 car labels
│          
└─visible
    ├─test   # 361 images with 466 person labels, 142 bicycle labels and 394 car labels
    └─train  # 1083 images with 1579 person labels, 511 bicycle labels and 1286 car labels
  
~~~

<!-- The RoadScene_Annotation dataset is annotated with 121 aligned Vis and IR image pairs selected from RoadScene(https://github.com/hanna-xu/RoadScene). For each instance, 14 semantic categories are defined and annotated except for the "background" category, i.e. “sky”, “tree”, “car”, “bicyclist”, “road”, “pavement”, “grass”, “fence”, “pedestrian”, “roadsign”, “building”, “pole”, “wire”, “light”. Each instance has annotations whenever the corresponding category appears in the current image. -->
