<h1 align="center">Toward the Creation of Precise Synthetic Datasets for Trustworthy and Privacy-preserving Machine Learning</h1>
<h2 align="center"> Overview</h2>
This repository aims to implement a data augmentation method (BCTGAN) and a data generation method (BPCA) to create synthetic data. Then, experiments are run on five datasets (Adult, Covertype, Intrusion, Credit, and MIMIC), and the quality of the synthetic datasets is evaluated.

<h2 align="center"> Download and Installation</h2>
Jupiter Notebook, vscode, or other IDEs can be used to run the codes.

Please enter
```bash
$ git clone https://github.com/Jing-jing-Li/dataset-generation-augmentation.git
```
in the terminal to download this repository.

Please download the [original datasets](https://drive.google.com/drive/folders/1Ws7rj9OKQzjLhR9zjMc5xlTvn8Tc1KVU?usp=sharing) from Google Drive and put it in the repository's folder before running the code. Three datasets in them (adult, intrusion, and covertype) are sourced from [sdgym library](https://github.com/sdv-dev/SDGym.git). The credit dataset is sourced from [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). And the mimic dataset is sourced from a [preprocessed MIMIC-III dataset](https://github.com/MIT-LCP/mimic-code).

The [synthetic datasets](https://drive.google.com/drive/folders/1gVYbupuIAULqiQOROLCMLKiud8U6DTk_?usp=sharing) created by the author are also available on Google Drive. Please put the ```synthetic data``` folder containing the synthetic data in the repository folder before running the evaluation code.

<h2 align="center"> Structure of Repository</h2>
The code is packaged according to the original datasets (Adult, Covertype, Intrusion, Credit, and MIMIC).

In each folder, there are three files ( ```..._augmentation.ipynb``` , ```..._generation.ipynb``` , and ```..._evaluation.ipynb``` ) showing the augmentation, generation, and evaluation process.

All the result images are packaged in the ```images``` folder.

<h2 align="center"> Acknowledgement</h2>

- Many thanks to  Dr. Alberto Huertas and Mr. Weijie Niu for their guidance.
- The BCTGAN method is develped based on [CTGAN](https://github.com/sdv-dev/CTGAN.git). Many thanks to the authors who provide the framework.
