# MPSR 
#Environmental requirements  
pytorch 1.10.0  
cuda 11.3  
other：pandas，numpy，opencv，matplotlib，sklearn  
Ethics statement：The study was approved by the Ethical Committee of the Fifth Affiliated Hospital of Zunyi Medical University.  
Data Availability：For original data, please contact the author：Correspondence: Ren-li Deng，dengrenli.research@outlook.com. After obtaining authorization, all data from the PSTSZC dataset can be used.  
The download address of the pre-training model is：https://pan.baidu.com/s/1zyw0ALteaHmspqDdX9MHAg?pwd=8djb 
We have provided a val example and a visual example in Visual analysis + test examples.ipynb
In order to better assist researchers in using this code, we provide a reproducible public dataset result. Its implementation steps are as follows:
1. Download dataset from https://www.cancerimagingarchive.net/collection/ucsf-pdgm/
2. Run UCSF-dataset.ipynb Note that the output_directory = './public/dataset/'+formatted+'/'+'DWI' parameter needs to be modified according to the local path
3. Put the pre-processed dataset into the dataset folder
4. Execute the UCSF-MISRP file
