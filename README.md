# peak-detection group project

Developed a peak detection project with a group of friends for time-series MDS-UPDRS data for parkinson's disease detection. Due to limited amount of data, 
we were unable to pursue a neural network based solution and instead we decided to reproduce a algorithmic solution at first from a paper called
[An Efficient Algorithm for Automatic Peak Detection in Noisy Periodic and Quasi-Periodic Signals](https://www.mdpi.com/1999-4893/5/4/588).   

Having known that the Scipy package have an algorithm, namely find_peak() taht works decently, our research question is that if we can do better than the algorithm from Scipy.   

The results from AMPD weren't satisfying as compared to what we can achieve using find_peak(). Hence, we developed another solution using wavelet transform to create a denoising layer to smoothen the series and then deployed the find_peak() function. We also designed a filter layer at the end to filter out some false positive peaks (look into the pre_files.html).     

The data is not open souced so we dont have the right to share it, also the original github repo. Hence, I created this personal repo only for illustration purpose during my job hunting period.    

How to read this repo:  
1. AMPD_main.ipynb  
2. AMPD_preprocess.ipynb  
3. main.ipynb
4. We created presentation slides for presenting our work. To view it, 
git clone this repo unzip it and click on the pre_files.html  (optional) 
