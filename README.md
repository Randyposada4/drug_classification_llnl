# drug_classification_llnl

## Slides and Graphs from 2021 Lawrence Livermore Foundation Summer Fellowship.

### Overview
This study focused on the classifying small molecule compounds using a labeled liver toxicity data subset (provided by UCSF Spoke Investigative Team https://spoke.ucsf.edu/) as a benchmark to measure model performance and accuracy. 

### Summer SLAM and Summer SLAM - Special Edition - 2021 Presentation Slides
**"An Organ-ized Approach to Drug Safety"**
[An Organ-ized Approach to Drug Safety.pdf](https://github.com/Randyposada4/drug_classification_llnl/files/7255702/An.Organ-ized.Approach.to.Drug.Safety.pdf)

Details of the Special Edition of Summer SLAM : https://livermorelabfoundation.org/2021/08/12/2021-summer-slam-special-edition/


## *ROC Curve Analysis*

![image](https://user-images.githubusercontent.com/67300875/135366287-1b9d401c-c570-4c9b-b5d8-0290ae998c99.png)

A receiver operating characteristic curve, also knonw as an ROC curve, is a graphical plot that helps illustrates the diagnostic ability of a binary classifier system as its discrimination threshold is varied. In the conducted ROC Curve here, we looked for the curve with the largest AUC (Area Under Curve) and we can note that the random forest classifier outperforms the other models used, at an AUC of 92.4%.


## *Random Forest Feature Importance*

![image](https://user-images.githubusercontent.com/67300875/135366306-49668fc0-7aa8-48d9-abb8-0c4ff030bde2.png)

We decided to use software to run a quick Random forest feature Importance algorithm, which allowed showcased that proportion liver anatomy had a very large impact on our models. 


## *Confusion Matrix* 

![image](https://user-images.githubusercontent.com/67300875/135366336-a62f1bf3-2773-433e-9766-10d2e52fa7bf.png)

The confusion matrix for the random forest classifier allows us to visualize the model’s performance, so … whether the model is correctly predicting if the compound causes DILI or if it is incorrectly predicting DILI. Here, The model predicted the true label was zero when it was zero correctly 43.75 %. We want the false positive to be as low as possible since we don’t want to give a safe no dili label to a compound that causes injury. The random forest model proves to be an exceptional model to make predictions from our data.

## Experience
Undergraduate fellow for the Livermore Lab Foundation (https://livermorelabfoundation.org/) in partnership with Lawrence Livermore National Laboratory (https://www.llnl.gov/)

Participated in the Data Science Summer Institue (DSSI) (https://data-science.llnl.gov/dssi) and the Computing Scholar Program (https://computing.llnl.gov/sites/default/files/scholar-expo-flier-final.pdf)
