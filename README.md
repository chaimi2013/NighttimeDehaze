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
[1]. Fast Haze Removal for Nighttime Image Using Maximum Reflectance Prior. [MRP_CVPR: Project,](https://chaimi2013.github.io/Research/NighttimeDehazing/index.html)
    [MRP_CVPR: github](https://github.com/chaimi2013/MRP)
    
    @CONFERENCE{CVPR_2017_Jing,
    	author = {Jing Zhang and Yang Cao and Shuai Fang and Yu Kang and Chang Wen Chen},
		title = {Fast Haze Removal for Nighttime Image Using Maximum Reflectance Prior},
		booktitle = {IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
		year = {2017}
	}
[2]. Fully Point-wise Convolutional Neural Network for Modeling Statistical Regularities in Natural Images. [FPC-Net: Project, ](https://chaimi2013.github.io/Research/FPC/index.html)
    [FPC-Net: github](https://github.com/chaimi2013/FPCNet)
    
    @inproceedings{zhang2018fpcnet,
      title={Fully Point-wise Convolutional Neural Network for Modeling Statistical Regularities in Natural Images},
      author={Zhang, Jing and Cao, Yang and Wang, Yang and Wen, Chenglin and Chen, Chang Wen},
      booktitle={ACM Multimedia Conference},
      year={2018}
    }
[3]. FAMED-Net: A Fast and Accurate Multi-scale End-to-end Dehazing Network. [FAMED-Net: Project, ](https://chaimi2013.github.io/Research/FAMED-Net/)
    [FAMED-Net: github](https://github.com/chaimi2013/FAMED-Net)
    
    @article{zhang2019famednet, 
        author={Zhang, Jing and Tao, Dacheng}, 
        journal={IEEE Transactions on Image Processing}, 
        title={FAMED-Net: A Fast and Accurate Multi-scale End-to-end Dehazing Network}, 
        year={2019}, 
        volume={}, 
        number={}, 
        pages={1-1}, 
        doi={10.1109/TIP.2019.2922837}, 
        ISSN={1057-7149}, 
        month={}
    }

## Contact
[Email](zj.winner@163.com)
