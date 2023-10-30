# FinalYearProject
IMPROVED ESTIMATION OF FORMATION VOLUME FACTOR OF NIGER DELTA CRUDE OIL SYSTEM USING MACHINE LEARNING APPROACH

Understanding reservoir flow behavior and correctly quantifying reservoir productivity depends 
on accurate reservoir fluid characterization. 

Over the years, a wide range of methods have been suggested to determine the formation volume factor for oil. 
These correlations fall short of its accuracy when applied to Niger Delta crude oil system.
This study developed a correlation for the formation volume factor of crude oil from the Niger 
Delta and assessed whether it was necessary to use locally created correlation when evaluating 
the formation volume factor (𝐵𝑜). 
A machine learning approach was used in the study. A process of model development was created
using the PVT dataset of the Niger Delta Crude Oil System to evaluate the oil formation volume 
factor. 

The model algorithm selection (linear regression) was based on the various statistical 
metrics which shows why multiple linear regression performed excellently than ridge and lasso.


This method involves the use of an empirical correlation which was developed using Python 
codes and linear regression machine learning techniques.

# Summary

The new model predicted 𝐵𝑜 more accurately. The model's output was used to compare laboratory PVT-derived 
𝐵𝑜 to other existing models and correlate the results. The 𝐵𝑜 results show that the average 
absolute error for crude oil fluids has been greatly reduced when compared to the most popular 
reported correlations. In the absence of laboratory PVT data, 𝐵𝑜 can be quickly predicted using 
the new correlation. Python programming was used to generate the correlation, which resulted in 
an Average Absolute Error of 0.0311%, a root mean square error of 0.0753%, and an SD of 0.0753.
The new correlation developed predicted the experimental 𝐵𝑜 better than the other correlations 
used in the study. This implies that the 𝐵𝑜 obtained from this newly developed model gave a better 
evaluation of reservoir performance when applied to oil reserves estimation.

# Conclusion
The objective of the study has been achieved. The correlation developed in this project work is
specifically meant for predicting the formation volume factor for the Niger-delta crude oil system. 
Linear regression which happens to be the best regression technique among the three 
regression techniques (linear, ridge, and lasso) was used to develop the correlation. The 
development of the correlation was based on non-linear regression analysis which can 
satisfactorily estimate the formation volume factor for crude oil samples with API gravity less 
than 50, which is typical of crude oil found in this region.
The new correlation developed predicted the experimental 𝐵𝑜 better than the other correlations 
used in the study. This implies that the 𝐵𝑜 obtained from this newly developed model gave a better 
evaluation of reservoir performance when applied to oil reserves estimation.
Statistical metrics were employed to handle model performance, and the comparison between the 
predictions of the new model and other pre-existing models with this new correlation 
outperforming the other ones. The result also shows that the developed correlation provides 
better estimation (least error) and higher accuracy than previously published correlations for 
Niger-Delta crude oils
