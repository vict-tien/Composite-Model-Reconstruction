# Composite-Model-Reconstruction

## Environmernt Setup

### Package Required
- os
- Tensorflow - 2.10.0
- Cv2 (opencv-python) - 4.5.5
- Numpy
- Matplotlib
- Torch - 1.12.1
- Torchvision
- Itertools
- Sklearn
- Python3 - 3.10.4
- Jupyter notebook
- Patchify - 0.2.3
- Scikit-learn - 1.4.0
- Pillow - 10.2.0 (https://pillow.readthedocs.io/en/stable/)

### Local Training Environment Setup (Python Local Environment Setup)

```
module load python3/3.10.4
python3 -m venv VENV_NAME
. VENV_NAME/bin/activate
pip install -U pip setuptools
pip install jupyterlab xarray
pip install tensorflow (tensorflow is same as tensorflow-gpu)
pip install opencv-python
pip install numpy
pip install matplotlib
pip install torch
pip install torchvision
pip install patchify
pip install scikit-learn
pip install pillow
python -m pip install 'git+https://github.com/facebookresearch/detectron2.git'
pip install -U segmentation-models
```
