## Cow Carcass Weight Estimation Using Images 

### Documentation Master Thesis

Author: Melchior Reihlen-Börgers
University: Maastricht University
Supervisor: Rui Jorge Almeida
GitHub: [Project Link](GitHub.com/MelchiorReihlenBorgers/MasterThesis)

Overview:
* Three classes: 
	1. CowImage
	2. KeypointData
	3. CnnModel
	4. KeypointEstimation

### CowImage

    __init__:
    Input:
    * path (str): path to an image
    * printInfo (bool): indicates whether information about image should be printed
    
    Output:
    -

    plot_image:
    Input:
    * title (str): title for plot
    
    Output:
    -


    resize_image:
    Input:
    * target_size (int,int): two integers giving the size of the image after resizing
    
    Output:
    * array with dimensions of target size and color channels

    normalize_image:
    Input:
    *target_size (int, int): two integers giving the size of the image after resizing
    
    Output:
    * array with dimensions of target size and all pixel values normalised to scale [0,1]



### Keypoint Data

### CnnModel

### KeypointEstimation

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTAxMDI3NjE0Ml19
-->