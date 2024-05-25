# LiDAR
3D IMAGE RECONSTRUCTION USING LiDAR
THE FOLLOWING PROJECT DISPLAYS THAT A LOW COST LiDAR CAN ALSO BE USED TO PRODUCE IMAGES THAT ARE SIMILAR TO IMAGES THAT A HIGH COST LiDAR'S CAN PRODUCE WITH A BETTER METHODOLOGY.

Recent advancements in image restoration of 3-dimensional objects have seen significant growth, particularly with the emergence of LiDAR (Light Detection and Ranging) technology. This project focuses on utilizing a low-cost LiDAR to develop a point cloud and restore the shape of a crushed object. The methodology involves the LiDAR's linear movement and continuous data recording to reconstruct the object's 3D shape. The project employs Cloud Compare software for accurate point cloud visualization.
Through the analysis of 720 files, each containing approximately 5000 points, the project achieves clear visualization of the crushed object, including the edges where the damage occurred. This demonstrates the potential of LiDAR technology in image restoration and the development of point cloud datasets for various objects requiring a 3D view. The findings serve as a foundation for utilizing low-cost LiDAR’s in object recovery and contribute to advancements in image restoration technology.


https://github.com/Vkpower2/LiDAR/assets/92012806/097e834f-a83f-4f07-be6c-cd8e7c21827a


This repository consists of the codes to convert .txt file to .csv files and .las, .laz files and these .las and .laz files to .shp files which will be used as a major group in cloud compare software to recover the 
point cloud based 3D image of the whole scanned object.
The major_project_last.ipynb and major_project_last.py has the codes to convert the data recorded by LiDAR to .shp files.
In the repository there are .zip files which have a total of 5000 points each and this group is used in building the 3D image.
Below are the outputs obtained by using the created dataset of a crushed tin and also using the TF-Luna LiDAR.

https://github.com/Vkpower2/LiDAR/assets/92012806/655cf372-1260-4c1b-b042-45708a89f335


The main software used for building these project are:
1. TF-Luna
2. TTL-USB converter (Used to convert the ASCII based data produced by TF-luna to human redable format as shown below)
   
Dist	     Strength	    Reserved
14	         6243	          0
15	         6263	          0
14	         6264	          0
15	         6274          	 0
14	         6282          	 0
14	         6283          	 0
14	         6276	          0
14	         6281	          0
14	         6275	          0
14	         6277	          0


4. Benewake software (Used for recording the data that is produced by TF-Luna)
5. Cloud Compare (To make changes and comparisions between the point cloud datasets created like translation, rotation in the data)
