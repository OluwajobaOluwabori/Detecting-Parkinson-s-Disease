# Detecting-Parkinson's-Disease

What is Parkinson’s Disease?
Parkinson’s disease is a progressive disorder of the central nervous system affecting movement and inducing tremors and stiffness. It has 5 stages to it and affects more than 1 million individuals every year in India. This is chronic and has no cure yet. It is a neurodegenerative disorder affecting dopamine-producing neurons in the brain.
> **Detecting Parkinson’s Disease  – Objective
To build a model to accurately detect the presence of Parkinson’s disease in an individual.
Using two machine learning algorithms, Logistic regression and eXtreme Gradient Boost to classify**

The dataset was created by Max Little of the University of Oxford, in collaboration with the National Centre for Voice and Speech, Denver, Colorado, who recorded the speech signals. The original study published the feature extraction methods for general voice disorders
**Content**-The dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds one of 195 voice recording from these individuals ("name" column). The main aim of the data is to discriminate healthy people from those with PD, according to the "status" column which is set to 0 for healthy and 1 for PD.
> Accurately detecting Parkinson's disease (PD) at an early stage is certainly indispensable for slowing down its progress and providing patients the possibility of accessing to disease-modifying therapy. Towards this end, the premotor stage in PD should be carefully monitored. An innovative deep-learning technique is introduced to early uncover whether an individual is affected with PD or not based on premotor features.
> Attribute Information:
> - name - ASCII subject name and recording number
> - MDVP:Fo(Hz) - Average vocal fundamental frequency
> - MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
> - MDVP:Flo(Hz) - Minimum vocal fundamental frequency
> - MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Several measures of variation in fundamental frequency
> - MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude
> - NHR,HNR - Two measures of ratio of noise to tonal components in the voice
> - status - Health status of the subject (one) - Parkinson's, (zero) - healthy
> - RPDE,D2 - Two nonlinear dynamical complexity measures
> - DFA - Signal fractal scaling exponent
> - spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation.
**Note: 'status' acts as our Target parameter for Supervised ML**

<h2> CONCLUSION</h2>
By comparing the result of the system, the maximum classification rate is achieved by XGBoost than LR with an accuracy 95%, whereas LR achieved only 87% accuracy.
The aim of the study is to analyze which algorithm provide the high accuracy of prediction for the Parkinson’s disease dataset, here the classification accuracy was studied and compared, with good performance and fast implementation XGBoost achieved a high accuracy with 96%. This system provides the comparison between machine learning classifiers of LR and XGBoost in PD disease diagnosis with high dimensional data.
