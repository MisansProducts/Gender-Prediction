# Gender Prediction

Gender prediction project for Python 3.11.5 (conda)

## Applications

* [Miniconda](https://docs.conda.io/en/latest/miniconda.html "Miniconda download")
* [Visual Studio Code](https://code.visualstudio.com/download "Visual Studio Code download")
* [Jupyter Iteractive Extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter "Jupyter Extension for Visual Studio Code installation page")
* [ipykernel](https://pypi.org/project/ipykernel/ "ipykernel for Jupyter")
* [Jupyter Notebook](https://jupyter.org/ "Jupyter Notebook download")
* [CUDA Toolkit 11.7](https://developer.nvidia.com/cuda-11-7-0-download-archive?target_os=Windows&target_arch=x86_64&target_version=10 "CUDA Toolkit 11.7 for Windows")
* `conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia`

## Required Libraries

* [Matplotlib](https://matplotlib.org/)
* [NumPy](https://numpy.org/)
* [pandas](https://pandas.pydata.org/)
* [seaborn](https://seaborn.pydata.org/)
* [PyTorch](https://pytorch.org/)
* [scikit-learn](https://scikit-learn.org/stable/)

## Credits

Alex Akoopie - Creator

# Analysis

Evaluation metrics:

```
F1-Score:	0.9212242849974912
Log Loss:	0.20243027084605875
ROC-AUC:	0.9751247761229851
```

![ROC-AUC Graph](imgs/1_roc-auc.png)

![Confusion Matrix Graph](imgs/2_confusion_matrix.png)

![Decision Boundary Graph](imgs/3_decision_boundary.png)
