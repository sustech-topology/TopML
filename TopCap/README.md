# TopCap: topological features for machine learning

[`snapshot.ipynb`](snapshot.ipynb) produces the snapshot results in Fig. 2 of the varied shapes of vowels, voiced consonants, and voiceless consonants (cf. the primary experiments below).  

[`snapshot'.ipynb`](snapshot'.ipynb), along with [`ear.jpeg`](ear.jpeg), produces a featured image for the manuscript.  In it, visuals of phones as in Fig. 2 form an icon cloud, weighted according to frequency of their occurrence in real-world speech data, along the contour of a human ear, which signifies speech signal processing and auditory perception.  In the background, an illustration of GRU neural network gives an idea of state-of-the-art machine learning framework for speech signal processing, enhanced by TopCap features through TopNN.  

## Primary experiments

The [`primary`](primary) directory contains code for results in Fig. 3 of machine learning topological features.  

## Model comparison

The [`comparison`](comparison) directory contains code for results in Table 1 of comparing TopCap with multiple state-of-the-art methods on both small and large datasets.  

## Feature analysis

The [`analysis`](analysis) directory contains code for results in Fig. 4 of analysing and comparing the features derived from TopCap, STFT, and MFCC.  
