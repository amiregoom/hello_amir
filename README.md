# Activity-Recognition

In this repository you can find the code for classification of the common activities of electrical line workers. We recruited 37 subjects to perform the 10 tasks listed below and collected the acceleration signals from a signle wrist-worn Empatica E4 accelerometer.

1. Sitting on a chair while keeping hands still on the chair arms for 3 minutes


The following picture shows a sample subject and the experiment area.


## Classification
We investigated the performance of ```k-Nearest Neighbors```, ```Support Vector Machines```, and ```Random Forest``` classifiers in 
## Report
The classification models for each combination of classifiers, feature sets, and window lengths were trained and saved to a pickle file. For 
## LIME
Using the LIME algorithm [[1]](#1) we found the important features for 2 activities of electric panel and hoisting in frequency and time-frequency feature sets. We reconstructed the signals using the selected features to investigate the relevance of the selected features. 
Also, all feature importance plots (for all activities) can be found at the bottom of the pages [here for the FFT features](https://saebragani.github.io/projects/HAR/LIMEFFTAllTasks.html) and [here for the wavelet features](https://saebragani.github.io/projects/HAR/LIMEWaveletAllTasks.html).

# References
<a id="1">[1]</a> Ribeiro, Marco Tulio, Sameer Singh, and Carlos Guestrin. "" Why should i trust you?" Explaining the predictions of any classifier." Proceedings of the 22nd ACM SIGKDD international conference on knowledge discovery and data mining. 2016.
