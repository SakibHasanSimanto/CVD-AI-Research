# CVD-AI-Research 
## Abstract
Cardiovascular disease is one of the most critical diseases that causes one
person to die in every 33 seconds globally. Hence, to reduce the death counts
significantly, we developed a ML system on non-clinical features, fostering a
novel early warning system. Furthermore, we developed several specialized
models on combined clinical and non-clinical features for clinical usage pur-
poses to diagnose CVD and validated our models on external dataset. We uti-
lized advanced newborn tabular neural networks like TabNet, TabPFN, and
FT-Transformer alongside three ensemble models- XGBoost, RFC, LGBoost.
Data augmentation is performed with CTGAN and Gaussian Copula, while
class imbalance is dealt with SMOTE. Gaussian Copula also provided in-
sights on harmful consequences of solely relying on data augmentation in
clinical sectors. Unsupervised learning is utilized for theoretical region ex-
traction from the combined dataset to report on models’ regional bias and
generalization. Moreover, causal inference with DoWhy extracted statisti-
cally significant features behind heart disease, leading to further insights
on the disease, and a voting classifier leveraging the features. We incorpo-
rated SHAP, TabNet sparse attention mechanism for local and global inter-
pretability, DiCE for counterfactual analysis, FairLearn for fairness and bias
mitigation, and Bayesian Neural Network for uncertainty analysis, creating a diverse ecosystem of specialized models for robust CVD diagnosis. Also,
we compared our models with recent works, developed easy to use and ac-
cessible software packages for diagnosis purposes, and two web applications
integrated the best ensemble model for both diagnostic and early warning
purposes. Classification reports, ROC-AUC, bias metrics are analyzed for
models’ performance, and hyperparameters are tuned with Bayesian Opti-
mization. With a recall and f1 score of 0.94 and 0.92, respectively, TabPFN
outperformed other models. We outlined the methodological rigor to align
with the components of European Union Trustworthy AI ethics, and FDA
Good Machine Learning Practice. 
## Dataset 
All the datasets can be accessed from the following Google Drive file: https://drive.google.com/drive/folders/1xSxfxY84rhHvndd7LDO5J2aMDncXyqPM?usp=drive_link 

## Codes 
All the codes can be sequentially accessed from the following Google Colaboratory notebook: https://colab.research.google.com/drive/1fx3u_yBNG4aVKqZ_3VskwVZXbjuj7sM-?usp=sharing 
The notebooks are documented well for reproducibility. 
