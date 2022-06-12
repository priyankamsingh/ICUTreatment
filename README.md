### M.Sc. Thesis 
In this repo, we have provided the code for treatment dose prediction for sepsis using supervised learning models and optimal treatment policy recommendation by reinforcement learning models. 
#### Data access
For this research MIMIC-III(1.v4) dataset was used. The data is publically available upon completion of a DSOR course offered by CITI.The data is only accessible to request and as per MIMIC conditioned, it can not be shared.  One can request the database here https://physionet.org/content/mimiciii/1.4/ and use the instructions and codes from public mimic repository to extract relevant tables and sepsis cohort. One can access the repo here : https://github.com/MIT-LCP/mimic-code
#### Repo structure:
##### experiments:
this folder contains three subdirectories:
slprediction : contains models and results for IV fluids and vassopressor dose prediction by supervised models
estatespace : Contains model, performance and results for the extended state space Reinforcement learning models
dstatespace : contains model, performance and results for default state space Reinforcement learning models
##### code : 
This folder contains code for data modeling by reinforcement learning and treatment dose prediction by supervised learning
##### figures: 
folder contains all the relevant figures for the thesis 
