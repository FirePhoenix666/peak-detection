# peak-detection group project

Developed a peak detection project with a group of friends for time-series MDS-UPDRS data for parkinson's disease detection. Due to limited amount of data, 
we were unable to pursue a neural network based solution and instead we chose to reproduce a algorithmic solution from a paper called
[An Efficient Algorithm for Automatic Peak Detection in Noisy Periodic and Quasi-Periodic Signals](https://www.mdpi.com/1999-4893/5/4/588).   

The result werent satisfying as compared to what we can achieve using find_peak() from scipy package. Hence, we developed another solution using wavelet transform and the find_peak() function 
since it is decently optimised already.   

AMPD_preprocess and AMPD_main are the AMPD algorithm's code. Then, the rest is in the main file. We created presentation slides for presenting our work. To view it, 
git pull this repo and click on the pre_files.html   

The data is not open souced so we dont have the right to share it, even so with the original github repo. Hence, I created this personal repo only for illustration purpose during my job hunting period.    
