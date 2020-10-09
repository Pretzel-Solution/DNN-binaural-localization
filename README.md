<a href="https://github.com/Pretzel-Solution/DNN-binaural-localization/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/Pretzel-Solution/DNN-binaural-localization"></a>

# DNN-binaural-localization
1. Simulate directional sound with head related impulse responses (HRIRs)
2. Train a deep neural network (DNN) to locate sound sources
3. Evaluate the DNN and analyse it with layer-wise relevance propagation (LRP)

# Code structure
* **1_data_presentation.ipynb**: Visually investigation of the HRIR database, directional sound simulation and decision of which preprocessing is applied for the input feature vector (->ILD)
* **2_training.ipynb**: DNN training with grid search hyperparameter optimization

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

