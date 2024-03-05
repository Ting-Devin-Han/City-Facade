![City-Facade-logo](https://github.com/Ting-Devin-Han/City-Facade/blob/main/logo/City-Facade.png)
# City-Facade 
This is the Dataset and Code of City-Facade proposed by our paper "City-Facade: Segmentation of Building Facade Elements in Large-Scale 3D Point Clouds".

<b>City-Facade</b> is a large-scale urban building facade dataset for <b>semantic-level and instance-level</b> segmentation from MLS LiDAR point clouds. It consists of labeled point clouds (<b>with 9 classes for building facades</b>) as well as unlabeled data (point clouds of street landscapes). The data collection area encompasses a variety of streets in Xiamen, China, with distinct architectural styles. We believe that our City-Facade will faciliate feature research on point cloud semantic or instance segmentation, urban understanding and modeling, point cloud completion, etc.

## City-Facade Preview

## Dataset Download

Please enjoy this dataset we have provided. Click here to download.

## Installation

### Requirements
<ul>
<li>Python 3.6.0 or above</li>
<li>Pytorch 1.2.0 or above</li>
<li>CUDA 10.0 or above</li>
</ul>

### Virtual Environment
````
source install.sh
````

## Data Preparation
(1) View and Download the City-Facade training / testing for building facade segmentation.

(2) Put the data in the corresponding folders, which are organized as follows.
````
data
|--City-Facade
|  |--train
|  |  |--CAR
|  |  |--JMC
|  |  |--SGS
|  |  |--XHR
|  |  |--YWR
|  |--test
|  |  |--CAR
|  |  |--JMC
|  |  |--SGS
|  |  |--XHR
|  |  |--YWR
...
````
## Model Zoo

## Organizations
![SYSU](https://github.com/Ting-Devin-Han/City-Facade/blob/main/logo/Sun%20Yat-sen%20University.png){:width="50%" height="50%"}
![XMU](https://github.com/Ting-Devin-Han/City-Facade/blob/main/logo/Xiamen%20University.png)
