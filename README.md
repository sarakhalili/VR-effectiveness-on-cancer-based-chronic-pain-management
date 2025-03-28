# VR-effectiveness-on-cancer-based-chronic-pain-management
Assessed VR effectiveness on cancer-based chronic pain management using patient-generated data.

## Introduction
The study aimed to assess the effectiveness of VR as an intervention for adults with chronic cancer-related pain, utilizing cognitive distraction and mindfulness meditation techniques. This randomized controlled trial compared the experiences of participants using VR versions of the same NPI to those using a two-dimensional (2D) medium for 30 minutes a day over a month. The methodology involved the use of four different applications, delivered either through a VR system to the VR group or a computer screen to the control group. 

The primary outcomes measured were daily, weekly average pain scores using the Visual Analog Scale (VAS) and the Short Form McGill Pain Questionnaire (SF-MPQ), along with secondary outcomes of Quality of Life (SF-12) and sleep quality (Pittsburgh Sleep Quality Index).

### Daily VAS score Data and Weekly Data in the Study:
**VAS Daily Data:** The Visual Analogue Scale (VAS) was used for daily assessment of pain pre, during, and post VR intervention. This scale is a self-reported measure of pain intensity, providing insights into immediate pain changes due to VR exposure.
**Weekly Data: **This includes measurements of pain trends, health-related quality of life, and sleep quality, assessed at the end of each week. Instruments like the Short Form McGill Pain Questionnaire (SF-MPQ) and the Pittsburgh Sleep Quality Index (PSQI) were used.

#### Results for Daily VAS score:
There was not a noticeable difference in pain reduction during VR exposure, with clinically meaningful reductions observed. However, overall, there were no significant differences in pain reduction between the VR and control groups. The results suggest that while VR may offer some pain relief during exposure, especially with cognitive applications, its overall effectiveness compared to non-VR interventions is not conclusively superior.

Here, pre-post/during VAS change indicates the change in pain levels after/during the VR session compared to before starting it. As can be seen in Table 3.1, the overall VAS change for the VR group is beneath -10mm which is the threshold for clinically meaningful change in pain. In addition to that, there is not a meaningful difference between the VR and the control group. The same is true for each VR environment as well.
![image](https://github.com/user-attachments/assets/598628a9-a9dc-491d-a227-08ebb304cc09)

The second table indicates VAS change for patients who started using VR with substantial amount of pain (pre VAS score>40mm). Here, we see VAS changes greater than -10mm, but, again no meaningful difference between the VR and the control group.
![image](https://github.com/user-attachments/assets/0a010c32-8e15-4a36-85ee-c66579c6c42b)


#### Results for the weekly data:
**SF-MPQ Pain Questionnaire**: The study observed a decrease in end-of-week pain scores compared to baseline in both groups. The only clinically significant decrease from baseline was seen in the control group's week 4 total score. 

**Quality of Life (SF12)**: For all participants overall, the SF12 scores in both groups did not appear to change significantly over the period of the trial.

**Pittsburgh Sleep Quality Index**: In all participants both PSQI groups did not meet the MCID over the period of the trial, except for a significant PSQI reduction (improvement) in control arm participants by the end of week 4.

## Time Series for daily VAS scores
Here we calculate the mean VAS score changes for each day and then plot the calculated amount for each day of the study. There is two type of VAS score changes as the data was captured pre, during and post intervention. The first data (blue) compares pain changes during using the interventions compared to before using it. The second data (orange) compares pain changes after using the interventions compared to before using it. Group 0 stands for the control group and group 1 stands for the VR group.

![image](https://github.com/user-attachments/assets/82c82f28-5a7f-4fe6-8881-b508ac1ec4b4)
![image](https://github.com/user-attachments/assets/7b7ee183-f359-4cd8-9e0e-a0fa50f2fb7f)

![e8ed454d-ef2e-4e89-a4e5-f42e231b5c46](https://github.com/user-attachments/assets/bf07e05d-7058-4832-b6e8-ce8317ea2d5f)

 
Here is the plot for all the participants in the VR group averaged in a week:
 
As can be seen, overall there was a decrease in pain (min= -5.5, max=-9.0) and Post VR pain reduction is more significant compared to During VR.
## Statistical Analysis for mean pain scores 
Here, we have the mean pain score changes for each subject throughout the study. Thus the temporal element is omitted. For statistical analysis, the normality of the distribution of the outcome variables should be checked. 'MW_dur_pre' and 'MW_aft_pre' are the continuous variables representing the mean pain score changes during and after using the intervention, respectively.

![image](https://github.com/user-attachments/assets/fa74dd5a-5694-4497-8a3b-ad3145c50983)  ![image](https://github.com/user-attachments/assets/d6d49c21-a473-4f1b-bd82-ded8507d4dc2)

![b5680ef5-602c-4c41-a237-da887de13189](https://github.com/user-attachments/assets/33c7a85f-815a-4f8b-9b2f-4df2d1ddeb8c)


As the data did not follow a normal distribution, non-parametric tests were chosen for the analysis. The Mann-Whitney U test was used to compare the two independent groups, while the Wilcoxon signed-rank test was used to compare the paired 'during' and 'post' measurements within each group. 

## Results
### Mann-Whitney U Test
The Mann-Whitney U test was conducted to compare the 'MW_dur_pre' and 'MW_aft_pre' between the two groups. The results indicated that there was no significant difference between the groups for either 'MW_dur_pre' (p = 0.8119) or 'MW_aft_pre' (p = 0.1690).

### Wilcoxon Signed-Rank Test
The Wilcoxon signed-rank test was performed to compare 'MW_dur_pre' and 'MW_aft_pre' within each group to determine if there are significant changes pre and post within the same group. Significant differences were found in Group 0 (p = 3.46e-05), indicating a significant change from 'pre' to 'post'. However, no significant differences were observed within Group 1 (p = 0.3694).

