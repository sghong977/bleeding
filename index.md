<center> <h1>Amplifying Action-context Greater: Image segmentation-guided Active Bleeding Localization in intraoperative gastrectomy</h1> </center>


![overall figure](./figs/overall.png) The schematic diagram of active bleeding framework using our proposed model AMAGI

![fusion figure](./figs/fusion_archi.png) Proposed fusion-based active bleeding recognition model AMAGI.




### GradCAM Visualization
Example gifs

| Data Type | frames                | Fast Pathway (SlowFast)                     | Fast Pathway (AMAGI)                     | Fusion Layer (AMAGI)                     |
|:---------:| ----------------------- | ------------------------ | ------------------------- |
| Ex1       |  <img src="./figs/82400_82408_conv3.gif" width="300"> |  <img src="./figs/sf50_82400_82408_conv3_gcam.gif" width="300"> | <img src="./figs/amagi_82400_82408_conv3_gcam.gif" width="300"> | <img src="./figs/amagi_82400_82408_map_fast2_gcam.gif" width="300"> |





## Surgical Analysis Index
Comparisons of SlowFast and AMAGI on blood count and duration for each 30 test cases.

### Split 1
<img src="./figs/split1.png" height="500">

### Split2 
<img src="./figs/split2.png" height="500">

### Split 3
<img src="./figs/split3.png" height="500">


