# Text Classification with spaCy and Synthetic Data

This repository contains a project for text classification using spaCy and a synthetic dataset related to social services. The steps outlined below will guide you through setting up your environment, downloading the necessary data, and running the project.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.7 or higher
- pip (Python package manager)

## Setup Instructions

Follow these steps to set up the project:

### 1. Install Required Python Packages

First, install the required Python packages by running:

```bash
pip install -r requirements.txt
```

### 2. Download the Dataset

Next, download the synthetic data for social services from Kaggle:

```bash
kaggle datasets download -d bnzn261029/synthetic-data-social-services
```

### 3. Unzip the Dataset

After downloading, unzip the dataset into the `data` directory:

```bash
unzip synthetic-data-social-services.zip -d data
```

### 4. Remove the Zip File

You can now remove the original zip file to clean up your directory:

```bash
rm synthetic-data-social-services.zip
```

### 5. Clone the spaCy Text Classification Pipeline

To set up the spaCy text classification pipeline, clone the pre-built project template:

```bash
python -m spacy project clone pipelines/textcat_demo
```

### 6. Run the Jupyter Notebook

Finally, open the Jupyter Notebook included in this repository and follow the steps outlined there to train and evaluate the text classification model.

## Additional Notes

- Ensure your `data` directory is structured properly after unzipping the dataset.
- The cloned spaCy project includes configuration files and scripts that are essential for training and evaluation.
- If you encounter any issues, refer to the official spaCy documentation for troubleshooting tips.

## License

This project is licensed under the MIT License.

## Acknowledgments

- [spaCy](https://spacy.io) for providing the NLP framework.
- [Kaggle](https://www.kaggle.com) for hosting the dataset.
