**Mini Traffic Detection** is a dataset for instance segmentation, semantic segmentation, and object detection tasks. It is used in the traffic monitoring industry. Possible applications of the dataset could be in the smart city and logistics industries. 

The dataset consists of 226 images with 725 labeled objects belonging to 8 different classes including *car*, *bus*, *bicycle*, and other: *person*, *truck*, *traffic_light*, *motorcycle*, and *stop_sign*.

Images in the Mini Traffic Detection dataset have pixel-level instance segmentation annotations. Due to the nature of the instance segmentation task, it can be automatically transformed into a semantic segmentation (only one mask for every class) or object detection (bounding boxes for every object) tasks. All images are labeled (i.e. with annotations). There are 2 splits in the dataset: *train* (158 images) and *val* (68 images). The dataset was released in 2022.

Here are the visualized examples for the classes:

[Dataset classes](https://github.com/dataset-ninja/mini-traffic-detection/raw/main/visualizations/classes_preview.webm)
