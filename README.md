# EEG analysis for Traumatic Brain injury

This repo provide a step-by-step guide line to analyze EEG files to classify patients which got brain trauma from healthy.

### Project team:

> Bruna Faria – Experience with ML (classification/regression tasks), exploring data. PhD student in Computational and Data Science and Engineering (Skoltech).

> J. Williamn ...

### Introduction

> Traumatic brain injury can bring serious consequences for people. Due to the rising number of TBI patients, computed tomography or magnetic resonance imaging isn’t useful because of their cost and time consumption. On other hand, the brain injury cause electrophysiologic abnormalities visible on electroencephalography (EEG) becoming this technique combined with machine learning approaches stronger helper in diagnostic and prognostic brain injuries. So, the main goal here is applying ML methods to EEG data to predict brain trauma in patients.

### This project expects to generate a full EEG processing pipeline including:

- Raw data preprocessing
- Feature extraction
- Exploratory data analysis
- Statistical testing
- Machine learning models development

### Main task:

>	Work on the development of a Machine Learning approach for brain trauma using engineering features and checking the preprocessing quality in data.

### Expected results:

> As the final result, the ML pipeline able to explore significant predictors on the data and provide better-quality metrics for helping to distinguish people suffered from brain trauma in past from healthy controls.

### Adviser:

> Alexander Ledovsky, Research Engineer of Skolkovo Institute of Science and Technology (Skoltech), Moscow.
________________________________________________

# Workflow:

<img src="images/Workflow.jpg" alt="My cool logo"/>

> 1) Preprocessing EEG files:

**- Preprocessing.ipynb**

- Getting number and names of channels based on the international guideline:
prefrontal = fp1,fp2
frontal = f7,f3,f4,fz,f8
central/temporal = t3,c3,cz,c4,t4
parietal = t5,p3,pz,p4,t6
occipital = o1,o2

<img src="images/Electrodes.PNG" alt="My cool logo"/>

> 2) Features Engineering:

**- FeaturesEngineering.ipynb**

- Ratios bands
- Coherence
- Conectivity

> 3) Exploratory Data Analysis:

**- AnalyzeFeatures.ipynb**

- Correlation

> 4) ML models:

**- MLworkflow.ipynb**

# External link to CometML:

XXXXXXXX


________________________________________________

#### References:

- Dhivya, S., & Nithya, A. (2018). A Review on Machine Learning Algorithm for EEG Signal Analysis. Proceedings of the 2nd International Conference on Electronics, Communication and Aerospace Technology, ICECA 2018. https://doi.org/10.1109/ICECA.2018.8474801
- Gemein, L. A. W., Schirrmeister, R. T., Chrabąszcz, P., Wilson, D., Boedecker, J., Schulze-Bonhage, A., Hutter, F., & Ball, T. (2020). Machine-learning-based diagnostics of EEG pathology. NeuroImage. https://doi.org/10.1016/j.neuroimage.2020.117021
- Hosseini, M. P., Hosseini, A., & Ahi, K. (2020). A Review on Machine Learning for EEG Signal Processing in Bioengineering. IEEE Reviews in Biomedical Engineering. https://doi.org/10.1109/RBME.2020.2969915
- Lai, C. Q., Ibrahim, H., Abd Hamid, A. I., Abdullah, M. Z., Azman, A., & Abdullah, J. M. (2020). Detection of Moderate Traumatic Brain Injury from Resting-State Eye-Closed Electroencephalography. Computational Intelligence and Neuroscience. https://doi.org/10.1155/2020/8923906
- Li, S., Zhou, W., Yuan, Q., Geng, S., & Cai, D. (2013). Feature extraction and recognition of ictal EEG using EMD and SVM. Computers in Biology and Medicine. https://doi.org/10.1016/j.compbiomed.2013.04.002
- Lotte, F., Bougrain, L., Cichocki, A., Clerc, M., Congedo, M., Rakotomamonjy, A., & Yger, F. (2018). A review of classification algorithms for EEG-based brain-computer interfaces: A 10 year update. In Journal of Neural Engineering. https://doi.org/10.1088/1741-2552/aab2f2
- Siuly Siuly, Li, Y., & Zhang, Y. (2016). EEG Signal Analysis and Classification Techniques and Applications. In Springer.
- Thatcher, R. W., North, D. M., Curtin, R. T., Walker, R. A., Biver, C. J., Gomez, J. F., & Salazar, A. M. (2001). An EEG severity index of traumatic brain injury. Journal of Neuropsychiatry and Clinical Neurosciences. https://doi.org/10.1176/jnp.13.1.77

