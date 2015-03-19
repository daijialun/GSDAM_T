GSDAM_T
=======

Grayscale Surface Direction Angle Model.


Copyright
==========

This software is free for use in research projects. If you publish
results obtained using this software, please use this citation.

    @article{zheng2014automatic,
    author  = {Zheng, Haiyong and Zhao, Hongmiao and Sun, Xue and Gao, Huihui and Ji, Guangrong},
    title   = {Automatic setae segmentation from Chaetoceros microscopic images},
    journal = {Microscopy Research and Technique},
    year    = {2014},
    }

Mannual
========


Installation
--------------
Open `GSDAM_T.cbp` in Code::Blocks and build the project named GSDAM_T

Run the code
----
1.Using the command line in terminal, change directory into the location of final file.
  > cd */bin/Debug/
  * represents the directory of the program. 
2.Under the directory, you can get the final image without any parameters 
  >./GSDAM_T *.jpg 
  *.jpg is the input image and it will output a image name "*-Bidui.tif".
3.Or run the file with several parameter and exact filenames you want for obtaining intermediate images.
  > ./GSDAM_T *.jpg -x x.tif -y y.tif
  x.tif and y.tif are the filenames of output image along with -x and -y as the optional parameters perspectively.
  More information please read 操作说明.txt 


Contact
=======

If you have any question, please feel free to contact Haiyong Zheng (zhenghaiyong@gmail.com).
