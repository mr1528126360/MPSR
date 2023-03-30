# MISRP
# Stroke is a disease with high incidence and mortality. Notably, the mortality rate is substantially higher in patients with stroke recurrence than in patients with the first stroke outbreak. Three main challenges remain in existing research. Firstly, there is a lack of reliable multi-omics image dataset for stroke recurrence, making it difficult for researchers to establish artificial intelligence (AI) model. Secondly, as far as we know, there is no multi-omics stroke recurrence prediction model based on medical Imaging. However, most clinicians must assess the likelihood of the stroke recurrence based on medical Imaging data. Thirdly, stroke recurrence data has serious sample imbalance problem, which brings great difficulties to train a good prediction model. 
# Based on these issues, we collected magnetic resonance imaging (MRI) and physiological indicator data from 602 patients with stroke in Zhuhai, China and after 12 months of extended follow-up to established the first multi-omics stroke recurrence dataset. Then, we proposed MISRP, a multi-omics transfer learning integrated stroke recurrence prediction model, which is based on Residual Network (ResNet), Long Short-Term Memory method (LSTM) and Deep Neural Networks (DNN). The MISRP model utilizes ResNet & LSTM to extract the key features from omics MRI data and constructs an integrated classifier based on the DNN. We use transfer learning framework to train ResNet model which solve the problem of sample imbalance problem. Experimental results show that the MISRP model outperforms the single omics model. The prediction accuracy, AUROC, specificity, and sensitivity of the MISRP model can be as high as 0.96,0.97,1 and 0.94, respectively. The MISRP model is the first multi-omics stroke recurrence predictive model which to provide new ideas for stroke recurrence forecasting field. We believe that the MISRP model can assist clinicians in diagnosing patients who may relapse and in designing effective secondary care planning.
#Environmental requirements
# pytorch 1.10.0
# cuda 11.3
# other：pandas，numpy，opencv，matplotlib，sklearn
# Ethics statement：The study was approved by the Ethical Committee of the Fifth Affiliated Hospital of Zunyi Medical University.
#	Data Availability：For original data, please contact the author：Correspondence: Ren-li Deng，dengrenli.research@outlook.com. After obtaining authorization, all data from the PSTSZC dataset can be used.
