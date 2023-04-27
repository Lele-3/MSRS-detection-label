# MSRS-detection-label
This is the detection label of MSRS dataset.
The label contains three categories $i.e.$ person, bicycle and car.
We give annotations for fusion images, visible images, and infrared images respectively. 

~~~
.
├─fusion
│  ├─test 
│  └─train
│          
├─infrared
│  ├─test 
│  └─train
│          
└─visible
    ├─test 
    └─train
  

The RoadScene_Annotation dataset is annotated with 121 aligned Vis and IR image pairs selected from RoadScene(https://github.com/hanna-xu/RoadScene). For each instance, 14 semantic categories are defined and annotated except for the "background" category, i.e. “sky”, “tree”, “car”, “bicyclist”, “road”, “pavement”, “grass”, “fence”, “pedestrian”, “roadsign”, “building”, “pole”, “wire”, “light”. Each instance has annotations whenever the corresponding category appears in the current image.
