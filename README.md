# VirtuHire-OCR

[![GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-lightgrey.svg)](https://github.com/magma-bangkit/VirtuHire-OCR)

OCR (Optical Character Recognition) is a machine learning project that utilizes the power of TensorFlow, a popular open-source deep learning library, to recognize and extract text from images or scanned documents. By leveraging advanced neural network architectures, OCR systems can automatically identify and convert printed or handwritten text into machine-readable formats. This technology has revolutionized the digitization of documents, enabling efficient text extraction for various applications such as document indexing, text translation, data analysis, and more.

## Table of Contents

- [Getting Started](#getting-started)
- [Installation](#installation)
- [Features](#features)
- [Model History](#model-history)
- [Acknowledgements](#acknowledgements)

## Getting Started
Here is what you need to be able to run this repo :

- Jupyter Notebook or Google Colab
- Python
- Pip Python
- Tensorflow
- Numpy
- SKLearn
- OpenCV 2
- Matplotlib
- Imutils
- Glob

## Installation

How to install : 
1. Download the repo
```bash
$ git clone https://github.com/magma-bangkit/VirtuHire-OCR.git
```
2. Upload the notebook to jupyter notebook cloud or google colab. Or you can use your local jupyter notebook.
3. Open the notebook using jupyter notebook or google colab
4. Set the dataset folder
5. Run each cells (make sure already install the packages and libraries)

## Features
The usage of this repo is to extract texts from images. So in our application, VirtuHire, we need an text extraction from CV upload, and we use this OCR Model to extract text from CV images.
The result is not quite good, because of the resource limitation. In normal, we need 36 hours to run the training, so for this capstone we simplified the model and resulting the accuracy is decrease.

## Model History
![result_loss](https://github.com/magma-bangkit/VirtuHire-OCR/assets/70988407/2d2bc1e7-5e0c-4dd1-a155-281193242fca)
![result_acc](https://github.com/magma-bangkit/VirtuHire-OCR/assets/70988407/ddf89468-a52a-4a7f-ae30-f9f78a760978)
![zzz](https://github.com/magma-bangkit/VirtuHire-OCR/assets/70988407/400a732c-1088-4c7b-904b-b645fcb76b8d)


## Acknowledgements

Mention any contributors, libraries, or resources that have been helpful during the development of the project.

- [Lana Saiful Aqil](https://github.com/lazaaq)
- [Dea Alifia Maharani S.](https://github.com/deaalifiams)
