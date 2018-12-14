# Computer Vision
For final project, please see: [Vehicle Classification and Localization](https://github.com/tiff-wang/415-final-project).
We used various cloud services along with computer vision techniques to train classifiers on over 600 000 images. For direct implementation details please see link above. 


The following is an assortment of assignments built in a computer vision I took at McGill University. Each assignment covers various fundamental computer vision topics. The full run down of each is seen below:

#### Assignment 1: Denoising, Sharpening, Template Matching
This assignment was focussed on several of the following fundamental computer vision techniques:
* Edge detection
  * Sobel edge detector
  * Laplacian of Gaussians edge detector
* Image sharpenning
* Image denoising
* Template matching

#### Assignment 2: Image Stitching 
This assignment focussed on several keypoint detectors, image stitching and classification techniques:
* SIFT keypoints
* SURF keypoints
* Image homography
  * RANSAC method
* Pyramid image blending
* Linear image blending
* Histogram of Oriented Gradients (HoG)
* KNearestNeighbors

#### Assignment 3: Image Segmentation
This assignment focussed on image segmentation and stereo image depth estimation, the full concepts include:
* Segmentation (using only numpy)
  * K-means clustering - 3 channel implementation
  * Expectation maximization - 3 channel implentation 
* Stereo Vision
  * Depth estimation
  * Epipolar geometry
   * SIFT kepoints
   * Epipolar lines
   * Sum of squared differences image matching
   
#### Assignment 4: Face Detection
This assignment was focussed on developing a face detection algorithm using eigenvector representations obtained by performing PCA on a self obtained training dataset, full list of concepts include:
* Eigenspace space based face detection
* Viola-Jones face detector
