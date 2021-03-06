<a href="https://github.com/Pretzel-Solution/DNN-binaural-localization/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/Pretzel-Solution/DNN-binaural-localization"></a>
<a><img alt="GitHub license" src="https://img.shields.io/badge/PyTorch-1.6.0-important"></a>
<a href="https://zenodo.org/badge/latestdoi/302612342"><img src="https://zenodo.org/badge/302612342.svg" alt="DOI"></a>

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
1. Create a folder named with "binaural_localization" in your Google Drive
2. Copy content of this repository into the folder
3. Doube-click on a Jupiter notebook, e.g. 1_data_presentation.ipynb, and choose "open with" "Google colab"
4. Mount Google Drive
5. Run the code

# License
Content in the folder LRP is licensed under the [BSD License 2.0](https://github.com/moboehle/Pytorch-LRP/blob/master/license.txt) by Moritz Böhle and available in [this](https://github.com/moboehle/Pytorch-LRP) repository.

The HRIR database was created by [J. Arend et. al.](http://audiogroup.web.th-koeln.de/ku100hrir.html) under [Attribution-ShareAlike 3.0 Unported](https://creativecommons.org/licenses/by-sa/3.0/) and can be downloaded [here](http://sofacoustics.org/data/database/thk/)
