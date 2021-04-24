# Blood-Cell-Counting

Find my article on this work here:
https://www.geeksforgeeks.org/python-blood-cell-identification-using-image-processing/

## Objective 
To get count of white and/or red blood cells from input blood smear image. 

## Image Processing Techniques Pipeline

### Step 1: Image Enhancement and Important Feature Highlight

* Input: Microscopic image 
* Enhancement Process:
  * Gray Scale 
  * Smoothening (Median, Gaussian Filtering) 
  * CLAHE normalization 
  * Contrast Stretching 
  * Canny Edge Detection
* Output: Enhanced Images

### Step 2: Image Segmentation and Feature Extraction

* Input: Edge Detection on Smoothened Image  
* Segmentation and Feature Extraction Process:
  * Morphological Operations (Closing) 
  * Adaptive thresholding  
  * Modified Haugh Transformation  
  * Blood Cell Detection
* Output: Blood Cell Count

## Clone this repo
```
git clone https://github.com/VishvaP/Blood-Cell-Counting.git
```
## Requirements
- Python IDE 
- Libraries: OpenCV, NumPy, matplotlib (Install using `pip install`, if not already)
  
## Run 
To run Python files, use your favourite Python IDE.
- For Image Enhancement and Important Feature Highlight:
	- Run `imageEnhancement.py` file
- For Image Segmentation and Feature Extraction:
	- Run `SegmentationFeatureExtraction.py` file 


## Acknowledgments

* Blood Smear Image Data Source. Zheng, Xin (2018), “Data for: Fast and robust segmentation of cell images by self-supervised learning”, Mendeley Data, v1. http://dx.doi.org/10.17632/w7cvnmn4c5.1  
* Lestriandoko, Nova Hadi, and Rifki Sadikin. "Circle detection based on hough transform and Mexican Hat filter." 2016 International conference on computer, control, informatics and its applications (IC3INA). IEEE, 2016.
* Seth, Sachin, and Kanik Palodhi. "An efficient algorithm for segregation of white and red blood cells based on modified hough transform." 2017 IEEE Calcutta Conference (CALCON). IEEE, 2017.
* Savkare, S. S., and S. P. Narote. "Blood cell segmentation from microscopic blood images." 2015 International Conference on Information Processing (ICIP). IEEE, 2015.


	     
