[//]: # (Image References)
[output_uu]: runs/uu_animated.gif
[output_um]: runs/um_animated.gif
[output_umm]: runs/umm_animated.gif


# Semantic Segmentation (using FCN)
### Problem Statement
Label the pixels of a road in images using a Fully Convolutional Network (FCN).

### Sample Output
The outputs for the model trained can be found in [runs](runs) folder. The outputs for different settings were:

Prefix _uu_      |  Prefix _um_   | Prefix _umm_
:---------------:|:--------------:|:------------:
![][output_uu]   | ![][output_um] | ![][output_umm] 


### Setup
##### Frameworks and Packages
All the dependencies for the project has been exported to [requirement.txt](requirements.txt).

##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

##### Run
Run the following command to run the project:
```
python main.py
```
**Note** If running this in Jupyter Notebook system messages, such as those regarding test status, may appear in the terminal rather than the notebook.
