# Sys_Discrimant-Model

## Using discrimant model
## Project Summary: Scatter Plot Analysis and Model Performance Evaluation (Screenshot Excel)
This project focuses on visualizing and analyzing the relationship between Experience and Training of administrators, highlighting task completion rates and model performance metrics.

Steps Undertaken:

Scatter Plot Visualization


<img width="713" alt="image" src="https://github.com/user-attachments/assets/741b96ed-c969-4506-82a0-e334acdd8ea0" />


##Created a scatter plot to explore the relationship between Experience and Training.

Used colors to differentiate task completion status: yellow (completed) and orange (not completed).
Added a red dashed line as a visual separator (e.g., Training ≈ 4.5).


Model Misclassification Analysis
40% of administrators who completed tasks were misclassified as failing to complete them.





<img width="909" alt="image" src="https://github.com/user-attachments/assets/9e97a2fb-1c74-47d9-9976-953327433278" />







<img width="967" alt="image" src="https://github.com/user-attachments/assets/ad7ec85a-6a53-4cfc-a7f9-88e722e74f66" />


##Performance Metrics

True Positives (TP): 9 administrators correctly classified as completing tasks.
False Negatives (FN): 6 administrators misclassified as not completing tasks.
True Negatives (TN): 59 administrators correctly classified as not completing tasks.
False Positives (FP): 1 administrator misclassified as completing tasks.




##Sensitivity and Specificity
Sensitivity (60%): Model identifies 60% of task-completers correctly but misses 40%.
Specificity (98.33%): Model is highly effective at identifying non-completers, with very few false positives.


##Discussion and Recommendations
Strengths: High specificity minimizes false positives, making it reliable for identifying non-completers.
Weaknesses: Lower sensitivity indicates a need for improvement in correctly identifying task-completers.


#Implications: 
Adjusting thresholds or incorporating additional predictors could improve sensitivity if identifying task-completers is a priority.
