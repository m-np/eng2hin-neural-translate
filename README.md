<h1 align = "center">
  AI-ML Project Template <br>
  <a href="https://github.com/m-np/eng2hin-neural-translate/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/m-np/eng2hin-neural-translate?logo=git&style=plastic"></a>
  <a href="https://github.com/m-np/eng2hin-neural-translate/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/m-np/eng2hin-neural-translate?style=plastic&logo=github"></a>
  <a href="https://github.com/m-np/eng2hin-neural-translate/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/m-np/eng2hin-neural-translate?style=plastic&logo=github"></a>
  <a href="https://makeapullrequest.com/"><img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=plastic&logo=open-source-initiative"></a>
</h1>

<div align = "justify">

**Objective:** A *simple* and *well-designed* template structure to start a machine learning/deep learning-based project. The template provides a basic directory structure with additional files (like [`notebooks/pytorch-boilerplate.ipynb`](./notebooks/pytorch-boilerplate.ipynb) to perform EDA. In addition, the template is designed such that code can be deployed into production. *Quickly get started* working on the code and preparing documentation as highlighted below. To understand the template check [**HOWTO.md**](./HOWTO.md) file.

---

</div>

## Setup

Please follow the following steps to run the project locally <br/>

1. `git clone https://github.com/m-np/eng2hin-neural-translate.git`
2. Open Anaconda console/Terminal and navigate into project directory `cd path_to_repo`
3. Run `conda create --name <env_name> python==3.9`.
4. Run `conda activate <env_name>` (for running scripts from your console or set the interpreter in your IDE)

For adding the new conda environment to the jupyter notebook follow this additional instruction
1. Run `conda install -c anaconda ipykernel`
2. Run `python -m ipykernel install --user --name=<env_name>`

-----

For pytorch installation:

PyTorch pip package will come bundled with some version of CUDA/cuDNN with it,
but it is highly recommended that you install a system-wide CUDA beforehand, mostly because of the GPU drivers. 
I also recommend using Miniconda installer to get conda on your system.
Follow through points 1 and 2 of [this setup](https://github.com/Petlja/PSIML/blob/master/docs/MachineSetup.md)
and use the most up-to-date versions of Miniconda and CUDA/cuDNN for your system.

-----

For other module installation, please follow the following steps:
1. Open Anaconda console/Terminal and navigate into project directory `cd path_to_repo`
2. Run `conda activate <env_name>`
3. Run `pip install -r requirements.txt` found 👉 [`requirements.txt`](./requirements.txt)

### Modelling Results

<p align = "justify">:writing_hand: Information about the used models/engines/agents and their performance can be documented here :sparkles:. An AI/ML trained model can be stored in their respective directories.</p>

> Report Link: :writing_hand: `report link` :ledger:

## LICENSE 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)


## Resources

<p align = "justify">:card_index: Documentation and/or Resources for your codes, and other mentions can be included in this section! :key:</p>
