# Image Decomposition using Independent Component Analysis (ICA)

University project.
This notebook demonstrates how to use Independent Component Analysis (ICA) to separate an image into independent components.

![Example Image](https://github.com/viktor436/Image-decomposition-using-ICA/assets/75243626/96373c69-5f31-4419-85d5-dd15a948c52c)

## Prerequisites

Before running the notebook, make sure you have the following dependencies installed:

- Python 3.x
- NumPy
- Matplotlib
- scikit-learn

You can install the required packages by running the following command:
pip install -r requirements.txt


## Getting Started

1. Clone or download the repository to your local machine.

2. Ensure that the `mixed.jpg` file is in the same directory as the notebook.

3. Run the notebook using a Jupyter Notebook environment or an integrated development environment (IDE) that supports Jupyter notebooks.

4. The notebook will load the `mixed.jpg` image, apply ICA to separate the image into foreground and background components, and display the results.

This notebook can also be tried in Google Colab [here](https://colab.research.google.com/drive/1mFDdEOHL3Syou-czdCA-lWigBABEQ5f6?usp=sharing). Note that you need to upload your own `mixed.jpg` file.

## License

Feel free to modify and use the code according to your needs.

## Acknowledgments

This notebook was inspired by Laurent de Vito's project, which can be found here: [https://github.com/ldv1/ICA_for_demixing_images](https://github.com/ldv1/ICA_for_demixing_images). The implementation utilizes the scikit-learn library for ICA and other data preprocessing tasks. Please note that the image may be subject to copyright.

## Note

This method of image decomposition might not always produce good results.
