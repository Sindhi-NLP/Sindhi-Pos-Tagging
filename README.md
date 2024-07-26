## Sindhi POS Tagging Dataset and Model

**Project Overview**

This repository houses a Sindhi Part-of-Speech (POS) tagging dataset, a trained CRF model, and accompanying Jupyter Notebooks for model training and inference.

**Dataset:**

* **SindhiPosDataset.csv:** Encompasses a collection of Sindhi sentences paired with their corresponding POS tags.
* **Format:** CSV

**Model:**

* **sindhiposmodel.crfsuite:** A pre-trained CRF model specifically tailored for Sindhi POS tagging.

**Notebooks:**

* **model_training.ipynb:** Demonstrates the process of training a CRF model on the provided Sindhi POS dataset.
* **model_inference.ipynb:** Illustrates how to employ the trained model for POS tagging on new Sindhi text.

**Requirements:**

* Python
* pandas
* pycrfsuite
* Jupyter Notebook (optional)

**Installation:**

1. Clone the repository: `git clone https://github.com/your-username/sindhi-pos-tagger.git`
2. Install required libraries: `pip install pandas pycrfsuite`

**Usage:**

1. Explore the `model_training.ipynb` notebook to comprehend the model training process.
2. Utilize the `model_inference.ipynb` notebook to conduct POS tagging on new Sindhi text.

**Contributions:**

We welcome contributions to enhance the dataset, model, or code. Feel free to submit issues or pull requests.
