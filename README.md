# NighttimeDehaze
[Nighttime Haze Removal Based on a New Imaging Model](https://chaimi2013.github.io/Research/NighttimeDehazing_ICIP2014/index.html)

The code has been tested on Win7/10 with Opencv 2.7.

## Installation
Please install opencv 2.4.9 (or copy "opencv_core249.dll" "opencv_highgui249.dll " "opencv_imgproc249.dll" from "OPENCV_DIR/build/x64/vc10/bin/" to the same directory with "NighttimeDehaze.exe") before running this code.

Then, run the executable code as: "NighttimeDehaze.exe name.bmp", where "name.bmp" is the input nighttime hazy image, the output dehazed result is named as "name_J.bmp".

## Folder Structure
    NighttimeDehaze
        -NighttimeDehaze.exe
            The executable code
        -*.dll
            The dependencies
        -flickr*.bmp
            Some test images
        -IMG*.bmp
            The test image with a color set and the corresponding ground truth (IMG_GT.bmp)

## Citation
Please cite our paper in your publications if it helps your research:

    @INPROCEEDINGS{JingZhang_ICIP2014_ND, 
    	author={Zhang, Jing and Cao, Yang and Wang, Zengfu}, 
		booktitle={2014 21th IEEE International Conference on Image Processing (ICIP)}, 
		title={Nighttime Haze Removal Based on a New Imaging Model}, 
		year={2014}, 
		month={Oct}
	}
    
    
    
## Related Work
[1]. Fast Haze Removal for Nighttime Image Using Maximum Reflectance Prior, CVPR 2017. [MRP_CVPR: Project,](https://chaimi2013.github.io/Research/NighttimeDehazing/index.html)
    [MRP_CVPR: github](https://github.com/chaimi2013/MRP)
    
[2]. Fully Point-wise Convolutional Neural Network for Modeling Statistical Regularities in Natural Images, ACM MM 2018. [FPC-Net: Project, ](https://chaimi2013.github.io/Research/FPC/index.html)
    [FPC-Net: github](https://github.com/chaimi2013/FPCNet)
    
[3]. FAMED-Net: A Fast and Accurate Multi-scale End-to-end Dehazing Network, T-IP, 2019. [FAMED-Net: Project, ](https://chaimi2013.github.io/Research/FAMED-Net/)
    [FAMED-Net: github](https://github.com/chaimi2013/FAMED-Net)

## Contact
[Email](zj.winner@163.com)
