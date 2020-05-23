# Blood-Cell-Counting
This work is also supported by an article published on GeeksForGeeks website. Find my article here:
https://www.geeksforgeeks.org/python-blood-cell-identification-using-image-processing/

This is a program to get count of white and/or red blood cells from input blood smear image. 

## Image Processing Techniques Pipeline

### Image Enhancement and Important Feature Highlight

* Input: Microscopic image 
* Enhancement Process:
  * Gray Scale 
  * Smoothening (Median, Gaussian Filtering) 
  * CLAHE normalization 
  * Contrast Stretching 
  * Canny Edge Detection
* Output: Enhanced Images

### Image Segmentation and Feature Extraction

* Input: Edge Detection on Smoothened Image  
* Segmentation and Feature Extraction Process:
  * Morphological Operations (Closing) 
  * Adaptive thresholding  
  * Modified Haugh Transformation  
  * Blood Cell Detection
* Output: Blood Cell Count

## Acknowledgments

* Blood Smear Image Data Source. Zheng, Xin (2018), “Data for: Fast and robust segmentation of cell images by self-supervised learning”, Mendeley Data, v1. http://dx.doi.org/10.17632/w7cvnmn4c5.1  
* Lestriandoko, Nova Hadi, and Rifki Sadikin. "Circle detection based on hough transform and Mexican Hat filter." 2016 International conference on computer, control, informatics and its applications (IC3INA). IEEE, 2016.
* Seth, Sachin, and Kanik Palodhi. "An efficient algorithm for segregation of white and red blood cells based on modified hough transform." 2017 IEEE Calcutta Conference (CALCON). IEEE, 2017.
* Savkare, S. S., and S. P. Narote. "Blood cell segmentation from microscopic blood images." 2015 International Conference on Information Processing (ICIP). IEEE, 2015.


	     
