# WOTR
A Dataset for people walk on the road.<br>
Click the link to get WOTR: [Baidu CODE:WOTR](https://pan.baidu.com/s/1XmKwi6IMWNllZXm2EMhkGA), [Google](https://drive.google.com/file/d/11Idy50HhzedOXxpxYuoecfqMNHGcxVfj/view?usp=share_link)

Classes:[ 'tree','red_light','green_light','crosswalk','tactile_paving','sign', 'pedestrian', 'bicycle', 'bus', 'truck', 'car','motorcycle', 'reflective_cone', 'ashcan', 'warning_column','roadblock', 'pole', 'dog', 'tricycle','fire_hydrant' ]

Note that in the Annotations folder, class tactile_paving->blind_road, pedestrian->person.

This dataset follows VOC format, if you are not clear about the VOC data format, please [click to view](http://host.robots.ox.ac.uk/pascal/VOC/).

Dataset file directory:
```
WOTR Dataset
   -Annotations
   -ImageSets
     --Main
       ---test.txt
       ---train.txt
       ---val.txt
   -JPEGImages
```

# Citations
Please consider citing our papers in your publications if this dataset helped with your research.
```
@article{xia2023dataset,
  title={A dataset for the visually impaired walk on the road},
  author={Xia, Haiying and Yao, Cong and Tan, Yumei and Song, Shuxiang},
  journal={Displays},
  volume={79},
  pages={102486},
  year={2023},
  publisher={Elsevier}
}
```
