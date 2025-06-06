## Noisy Labelled Hyperspectral Image Classification using Few-Shot Learning and Counterfactual Correction
![system model](https://github.com/user-attachments/assets/1d9a8f1f-e74b-4456-8d19-964149e76271)

### Abstract
Hyperspectral image (HSI) classification with noisy labels has recently attracted increasing interest. Recently proposed approaches, such as Few-shot learning (FSL) methods, require that the support sets used during training accurately represent their respective classes and are free from mislabeled samples. However, despite careful annotation efforts in real-world applications, support set samples are still susceptible to misleading labels, making this requirement unrealistic. This paper introduces a novel FSL method for HSI Classification with Noisy Labels and Counterfactual Correction (FSLCC-HSI). Initially, the model utilises VGGNet as a pre-trained network to transfer features for HSI feature extraction, specifically within the residual slice attention module (RSAM). RSAM effectively identifies relevant slices, suppresses misleading features to enhance their interrelatedness, and captures inherent aleatoric uncertainty for regularisation. Furthermore, FSLCC-HSI employs counterfactual learning to identify true labels by selecting the label with the lowest counterfactual proximity score. Thus, it mitigates the impact of noisy labels during training. The algorithm is theoretically proven to converge to a global minimum under bounded noise and sufficient sample diversity, guaranteeing stability and reliability in its training process. To the best of our knowledge, FSLCC-HSI is the first method to apply counterfactual learning in HSI classification under noisy label conditions. We evaluate FSLCC-HSI’s performance on four public HSI datasets under symmetric and asymmetric noisy labels conditions. Experimental results demonstrate that FSLCC-HSI outperforms all benchmark methods for HSI classification, even with limited labelled samples. 

### The code will be released upon acceptance.

Houston 2018 [link](https://github.com/YuxiangZhang-BIT/Data-CSHSI)

Download Pavia University and Pavia Centre datasets [link](https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes)


