# healthcare_data_science_practice
 
## Project description
In this project, we aim to explore the relationship between personal behaviors and certain diesease, such that some policies could be developed for public health management.   
  
Dataset used in this project is from [CDC Behavioral Risk Factor Surveillance System](https://www.cdc.gov/brfss/annual_data/annual_data.htm)

## Research Questions 1
What is the association between stroke and some selected modifiable behaviour risk factors, namely `smoking`, `alcohol intake`, `cholesterol level`, `hypertension` and `weight`?  
    
In solving this problem, we used SVM classifier and the model accuracy reached 97%. 

## Research Questions 2
What is the association between health care access, socio-demographics and HIV screening? Could we predict the chances that individuals are getting HIV tests based on their `race`, `income`, `education`, `insurance coverage` and `access to personal doctors`?    
     
In solving this problem, we used KNN classifier with K=69. Model accuracy is 60% as shown below.   
<p align="center">
  <img src="https://i.ibb.co/G3L4LJt/output.png">
</p>
  
## Research Questions 3
Are there gender differences in different types of cardiovascular diseases (CVD)? 
    
In solving this problem, we used K-means clustering. However, no significant boundaries of the clusters are identified. 
<p align="center">
  <img src="https://i.ibb.co/vZVxQPB/output.png">
</p>