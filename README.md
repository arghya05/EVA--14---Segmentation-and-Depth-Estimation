# Session 14 - Segmentaion and Depth Estimation using PlanerCNN and MiDaS

This repository contains the link of dataset which contains depth map, surface planes, and bounding boxes for the classes.

- This Dataset includes 4 classes :<br>
    - hardhat<br>
    - vest<br>
    - mask<br>
    - boots<br><br>

- Dataset Link : https://drive.google.com/file/d/1gdkjVx-Dnji_kCBBkhPaVMhVImEuXZaU/view?usp=sharing 

## Directory Structure:


```bash
Construction PPE Kit
    ├── Annotated Images
    |   ├── images
    |   |   ├── image_0001.jpg
    |   |   ├── image_0002.jpg
    |   |   ├── ...
    |   |   ├── image_3521.jpg
    |   ├── labels
    |   |   ├── image_0001.txt
    |   |   ├── image_0002.txt
    |   |   ├── ...
    |   |   ├── image_3521.txt
    ├── Depth Images using MiDaS
    |   ├── image_0001.png
    |   ├── image_0002.png
    |   ├── ...
    |   └── image_3521.png
    |── Planer images using PlanerCNN
        ├── image_0001.png
        ├── image_0002.png
        ├── ...
        └── image_3521.png    
```

Construction PPE Kit folder contains 3 main folders <b>Annotated images</b>, <b>Depth Images using MiDaS</b> and <b>Planer images using PlanerCNN</b>.
1. <b>Annotated images</b> contains two folders which are <b>images</b> and <b>labels</b>. <b>images</b> folder contains input images and <b>labels</b> folder contains bounding boxes for the images in <b>images</b> folder
2. <b>Depth Images using MiDaS</b> contains the depth images generated by [MiDaS](https://github.com/intel-isl/MiDaS)
3. <b>Planer images using PlanerCNN</b> contains the surface planes images for the images which are generated by [planercnn](https://github.com/NVlabs/planercnn)

## Group Members
- Vishwajeet Pratap Singh (vishwajeet.pratapsingh2207@gmail.com)
- Happy Singh (hsingh0805@gmail.com)
