# OpenDenseLane
OpenDenseLane is a LiDAR-based dataset developed for land marking detection and HD map constuction.

# Data Format

## Pointcloud
###Data structure
pointcloud {  
    "x", "y", "z", "intensity", "value", "timestamp", "frame_index", "sensor_index", "label"  
}
###Definition
>x, y, z: position values  
>intensity: laser reflection   
>value: light reflection  
>frame_index: multi frame index  
>sensor_index: multi sensor index  
>label: annotation label 

## Image

### BEV image
Pseudo mask image that rasterized from the LiDAR point cloud from the BEV view.

### Instance image
instance label image corresbonding to BEV image

## Annotation

annotation {
    "backgroud": 0, 
    "curb": 1, 
    "lane": 2, 
    "stopline": 3,
    "crosswalk": 4,
    "arrow": 5
}

# Data Download
Link: https://pan.baidu.com/s/1WhkaVbApvw2KBLawVHcGTQ  Key: 3emv
