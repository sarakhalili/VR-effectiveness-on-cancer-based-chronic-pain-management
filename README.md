# VR-effectiveness-on-cancer-based-chronic-pain-management
Assessed VR effectiveness on cancer-based chronic pain management using patient-generated data.

## Time Series for daily VAS scores
Here we calculate the mean VAS score changes for each day and then plot the calculated amount for each day of the study. There is two type of VAS score changes as the data was captured pre, during and post intervention. The first data (blue) compares pain changes during using the interventions compared to before using it. The second data (orange) compares pain changes after using the interventions compared to before using it. Group 0 stands for the control group and group 1 stands for the VR group.

![image](https://github.com/user-attachments/assets/82c82f28-5a7f-4fe6-8881-b508ac1ec4b4)
![image](https://github.com/user-attachments/assets/7b7ee183-f359-4cd8-9e0e-a0fa50f2fb7f)

 
Here is the plot for all the participants in the VR group averaged in a week:
 
As can be seen, overall there was a decrease in pain (min= -5.5, max=-9.0) and Post VR pain reduction is more significant compared to During VR.
## Statistical Analysis for mean pain scores 
Here, we have the mean pain score changes for each subject throughout the study. Thus the temporal element is omitted. For statistical analysis, the normality of the distribution of the outcome variables should be checked. 'MW_dur_pre' and 'MW_aft_pre' are the continuous variables representing the mean pain score changes during and after using the intervention, respectively.

![image](https://github.com/user-attachments/assets/fa74dd5a-5694-4497-8a3b-ad3145c50983)  ![image](https://github.com/user-attachments/assets/d6d49c21-a473-4f1b-bd82-ded8507d4dc2)



As the data did not follow a normal distribution, non-parametric tests were chosen for the analysis. The Mann-Whitney U test was used to compare the two independent groups, while the Wilcoxon signed-rank test was used to compare the paired 'during' and 'post' measurements within each group. 

## Results
### Mann-Whitney U Test
The Mann-Whitney U test was conducted to compare the 'MW_dur_pre' and 'MW_aft_pre' between the two groups. The results indicated that there was no significant difference between the groups for either 'MW_dur_pre' (p = 0.8119) or 'MW_aft_pre' (p = 0.1690).

### Wilcoxon Signed-Rank Test
The Wilcoxon signed-rank test was performed to compare 'MW_dur_pre' and 'MW_aft_pre' within each group to determine if there are significant changes pre and post within the same group. Significant differences were found in Group 0 (p = 3.46e-05), indicating a significant change from 'pre' to 'post'. However, no significant differences were observed within Group 1 (p = 0.3694).

