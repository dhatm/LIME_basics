# LIME_basics
Explainable AI/ML with LIME: basic scripts to load various models either trained yourself or loaded from tensorflow/keras applications.

LIME stands for local interpretable model-agnostic explanations.  Another alternative is to use SHAP (SHapley Additive exPlanations).  Both methods make post-hoc explanations of superpixel contributions to classifier calls. 

Note to remember: explainable is not the same thing as interpretable. Explainable refers to the ability to identify what contributed to a decision or result, even if the cause, logic, or reason is not transparent.  Interpretable refers to the ability to understand the cause, logic, or reason for a decision or result.  



## notebooks
1. explain_my_xception_tf.ipynb -- loads a very light-weight mini-xception (not to be confused with inception) network I made to classify cat vs dog. Uses tensorflow.

2. explain_resnet50_tf.ipynb -- loads a resnet50 network from keras and explains its classifications. Uses tensorflow.

3. explain_inception_tf.ipynb -- loads an inception network from keras and explains its classifications. Uses tensorflow.

4. explain_inception_pytorch.ipynb -- loads an inception network from keras and explains its classifications. Uses pytorch.


## misc. links
1. [LIME repo](https://github.com/marcotcr/lime)
2. [LIME paper](https://arxiv.org/abs/1602.04938)
3. [SHAP repo](https://github.com/slundberg/shap)


## Status & Possible Future To-dos
- [x] implemented and tweaked lime notebook examples
- [x] added other examples: resnet50, basic self-made mini-xception network
- [x] identified small differences with tensorflow and pytorch inception results (probabilities and explanation heatmap range) 
- [ ] further explore pytorch oddities -- prediction results (independent of LIME) & heatmap range
- [ ] apply to & explore more models (ViTs etc.)


