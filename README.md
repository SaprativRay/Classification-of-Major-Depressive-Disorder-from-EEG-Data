# Classification-of-Major-Depressive-Disorder-from-EEG-Data

## Abstract

Electroencephalogram (EEG) is an electrophysiological monitoring method to record the electrical activity of the brain. EEG is most often used to diagnose epilepsy, which causes abnormalities in EEG readings. It is also used to diagnose sleep disorders, depth of anesthesia, coma, encephalopathy, brain death, and depression. Being one of the prevalent psychiatric disorders, depressive episodes of major depressive disorder (MDD) is often misdiagnosed or overlooked. Therefore, identifying MDD at earlier stages of treatment could help to facilitate efficient and specific treatment. In this article, Random Forest (RF) and Ant Colony Optimization (ACO) algorithm are used to reduce the number of features by removing irrelevant and redundant features. The selected features are then fed into k-nearest neighbors (KNN) and SVM classifiers, a mathematical tool for data classification, regression, function estimation, and modeling processes, in order to classify MDD and non-MDD subjects. The proposed method used Wavelet Transformation (WT) to decompose the EEG data into corresponding frequency bands, like delta, theta, alpha, beta and gamma. A total of 119 participants were recruited by the University of Arizona from introductory psychology classes based on survey scores of the Beck Depression Inventory (BDI). The performance of KNN and SVM classifiers is measured first with all the features and then with selected significant features given by RF and ACO.

## Dataset

119 participants were recruited by the University of Arizona from introductory psychology classes based on survey scores of the Beck Depression Inventory (BDI). All participants were between 18 and 25 years of age and had no history of head trauma or seizures and were not on any psychoactive medications. Controls had stable low BDI scores (<8) and had no self-reported history of MDD. Depressed participants had stable high BDI scores (>13) and met the criteria for MDD according to the Diagnostic and Statistical Manual of Mental Disorders, fourth standard EEG cap based on the extended 10-20 system of electrode positions using a NeuroScan EEG system (NeuroScan Lab, Charlotte, NC, USA) and were filtered and amplified using a bandpass filter 0.5-100Hz and sampling rate of 500Hz. Electrode impedances were maintained below 10kΩ throughout the experiment. Eye blink artifacts were removed using ICA. The data consists of 64 EEG micro-voltage rows, the 65th row contains HEOG and the 66th row contains VEOG values. VEOG and HEOG were recorded with two pairs of electrodes one placed above the right eye and the other 10mm from the lateral canthi. Some data may have a 67th column with EKG data as well. Voltages are referenced to a site anterior to the Fz section of the scalp. Out of 119 subjects 75 did not show characteristics of MDD while the rest 44 showed characteristics of MDD.

## Results

The accuracy varies with the inclusion of the electrodes as follows: 
![AccuracyNew](https://user-images.githubusercontent.com/33724590/83785149-84c14380-a6ae-11ea-904c-21ac139d508c.png)

These Electrodes are selected from the Importance Graph generated from Random Forest

