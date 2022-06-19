# UNET++ based CAC Scoring
**THIS REPO IS STILL UNDER DEVELOPMENT, IMPROVEMENT IS WELCOMED!**

A UNet++ based ML model to do automatic CAC scoring
This is a repo to develop my Undergraduate Thesis on Biomedical Engineering

### Development Environment
- WSL2 Ubuntu Linux 20.04.4 LTS
- Miniconda (for environment management)
- Poetry (for dependencies management)
- Python 3.9.12

### Library
- Tensorflow
- Streamlit
- Pydicom
- Numpy

### Reference
- Paper:
  - [Original Paper using COCA Dataset (they use UNET Architecture)](https://www.nature.com/articles/s41746-021-00460-1)
  - [Calcium Scoring Method](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5487233/)
- Code:
  -  [keras-unet-collection](https://github.com/yingkaisha/keras-unet-collection)

# Dataset
The dataset used for this model is provided by Stanford AI COCA Dataset, this dataset can be accessed through this [link](https://stanfordaimi.azurewebsites.net/datasets/e8ca74dc-8dd4-4340-815a-60b41f6cb2aa.)

This model is using Gated MRI Data from the COCA Dataset consisting of the MRI image saved in a DICOM format and the calcium mask saved in a xml plist format.

Other dataset usage will be developed after the implementation of the COCA Dataset has been done.