# feats_of_cnn
👁experimenting with things involving cnns, [Pytorch](https://pytorch.org/docs/stable/index.html) used everywhere.

---

## Visualizations   
![Filters and data patches](./ss/viz1.png)
Vizualizations from the `CNN Viz.ipynb` notebook showing conv layer kernel for some channel in the first layer, it's resultant activation map and patches that result in highly activated neurons in the channel.

*More stuff to be added...*

---

## Style Transfer   
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1sECOu0dZqfiU5wlFUV-_1cvLYNQEVhjc?usp=sharing)  
An attempt at recreating (partially) the Gaty's et al paper - [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576), along with some other experiments.  

![StyleTransfer](ss/st.png)
Styled using Van Gogh's Starry Night Over the Rhone

---

## Fine Grained Visual Categorization
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1I9XJqaf2tgUB8v52DfOC9AKiilPDHoJQ?usp=sharing)  
A naive attempt at [FGVC7 - Plant Pathology](https://www.kaggle.com/c/plant-pathology-2020-fgvc7).
Makes use of image augmentation using [Albumentations](https://github.com/albumentations-team/albumentations), ensemble of 4 models among other things.  

![Misclassified](ss/fgvc.png)
*Inspecting some misclassified samples*