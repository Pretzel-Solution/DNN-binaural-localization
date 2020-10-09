<a href="https://github.com/Pretzel-Solution/DNN-binaural-localization/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/Pretzel-Solution/DNN-binaural-localization"></a>
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)

# DNN-binaural-localization
1. Simulate directional sound with head related impulse responses (HRIRs)
2. Train a deep neural network (DNN) to locate sound sources
3. Evaluate the DNN and analyse it with layer-wise relevance propagation (LRP)

This repository contains the source code of my Bachelor thesis with the topic "An Analysis of Binaural Localization Models with Explainable Machine Learning Methods". A PDF version is available on my website: http://pretzelsolution.com/binaural-localization

# Code structure
* **1_data_presentation.ipynb**: Visually investigation of the HRIR database, directional sound simulation and decision of which preprocessing is applied for the input feature vector. Interaural level difference (ILD) has been chosen.
* **2_training.ipynb**: DNN training with grid search hyperparameter optimization
* **3_evaluation.ipynb**: Evaluate DNNs with different error metrics and explain its predictions with LRP
* **custom_dataset_class.ipynb**: Additional dataset class which can be used to conduct memory efficiant preprocessing in batches

# Quickstart
Copy the repository to your google drive and run the notebooks with colab.

# License
<p xmlns:dct="http://purl.org/dc/terms/" xmlns:cc="http://creativecommons.org/ns#" class="license-text">
   Text, figures and source code of the work
   <a rel="cc:attributionURL" property="dct:title" href="https://github.com/Pretzel-Solution/DNN-binaural-localization">
     An Analysis of Binaural Localization Models with Explainable Machine Learning Methods
  </a> by 
  <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="pretzelsolution.com">
    Niclas Hildebrandt
  </a> is licensed under 
  <a rel="license" href="https://creativecommons.org/licenses/by/4.0">
    CC BY 4.0
    <img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" height="22" width="22" />
    <img src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" height="22" width="22" />
  </a>
</p>

Content in the folder LRP is licensed under the [BSD License 2.0](https://github.com/moboehle/Pytorch-LRP/blob/master/license.txt) by Moritz Böhle and available in [this](https://github.com/moboehle/Pytorch-LRP) repository.

The HRIR database was created by [J. Arend et. al.](http://audiogroup.web.th-koeln.de/ku100hrir.html) under [Attribution-ShareAlike 3.0 Unported](https://creativecommons.org/licenses/by-sa/3.0/) and can be downloaded [here](http://sofacoustics.org/data/database/thk/)
