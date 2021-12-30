# EEE/CSE499: Pulmonary Fibrosis Progression

### Overview

In this project , we will predict a patient’s severity of decline in lung function based on a CT scan of their lungs. We will determine lung function based on output from a spirometer, which measures the volume of air inhaled and exhaled. The challenge is to use deep learning techniques to make a prediction with the image, metadata, and baseline FVC as input.

### Pulmonary fibrosis
Pulmonary fibrosis is a chronic interstitial lung disease that occurs due to gradual irreparable lung tissue scarring and damage over time. As the disease worsens, loss in lung capacity increases, and the patient becomes progressively more short of breath. There is no known cure and limited treatment options available, but early diagnosis without surgical lung biopsy is crucial for the treatment and management. The most promising method in the treatment of pulmonary fibrosis is the assessment of lung function decline based on computed tomography (CT) imaging. However, identification and characterization of pulmonary fibrosis is sometimes difficult for the general radiologist and even for the subspecialist radiologist, due to the low frequency of such cases and numerous types of interstitial lung diseases.

<p align="center">
  <img width="400" height="400" src="https://github.com/shazzad-hasan/EEE-CSE499/blob/master/explainability.png" />
</p>

### How to Reproduce Our Results


### Installation
**Download and Install** the latest version of `miniconda` by selecting the latest Python version for your operating system.

|      | Linux | Mac  | Windows |
| ---- | ----- | ---- | ------- |
| 64-bit | [64-bit (bash installer)][lin64] | [64-bit (bash installer)][mac64] | [64-bit (exe installer)][win64]
| 32-bit | [32-bit (bash installer)][lin32] |  | [32-bit (exe installer)][win32]

[win64]: https://repo.continuum.io/miniconda/Miniconda3-latest-Windows-x86_64.exe
[win32]: https://repo.continuum.io/miniconda/Miniconda3-latest-Windows-x86.exe
[mac64]: https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
[lin64]: https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
[lin32]: https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86.sh

Create and activate a new `conda` environment.

For Windows users, these following commands need to be executed from the **Anaconda prompt** as opposed to a Windows terminal window. For Mac, a normal terminal window will work. 

#### Git and version control
These instructions also assume you have `git` installed for working with Github from a terminal window, but if you do not, you can download that first with the command:
```
conda install git
```

**Now, we're ready to create our local environment!**

#### Dependencies
- numpy==1.20.0
- opencv-python==4.5.1.48
- pandas==1.2.1
- Pillow==8.1.0
- pydicom==2.1.2
- scikit-learn==0.24.1
- scipy==1.6.0
- tensorflow-gpu==1.15.0
- tqdm==4.56.0

Install required dependencies (which are specified in the requirements text file) using 
```
pip install -r requirements.txt
```
That's it! Now most of the libraries are available to you. If you need additional requirments to install, please install in your local machine. 

To reproduce our results, first clone this repository, and download the dataset [here](https://www.kaggle.com/c/osic-pulmonary-fibrosis-progression).

Now, assuming your environment is still activated, you can navigate to the working directory and start working with the notebooks.

