
# African Sentiment Classification Model

## Overview

This project implements a sentiment classification model for African tweets using data augmentation and preprocessing techniques. The model is based on transformer architectures and is trained on eight African languages.

## Features

- **Data Augmentation**: PEGASUS text paraphrasing and synonym replacement are used for data augmentation, contributing to increased model accuracy.
- **Data Preprocessing**: Regular expressions are applied to clean the data by removing emojis, stop words, and punctuation.
- **Multilingual Model**: The sentiment classification model is trained on eight African languages, making it versatile for a diverse range of tweets.
- **Transformer-based Model**: Leveraging the power of transformer architectures for effective sequence processing.

## Requirements

- Python 3.8+
- A good GPU which supports CUDA
- Other dependencies specified in `requirements.txt`

## Installation

1. Clone the repository:

```bash
git clone https://github.com/nanihemanth/CS_678_FINAL_PROJECT.git
cd CS_678_FINAL_PROJECT/code
```

2. Create a virtual environment and activate it
```bash
python -m virtualenv venv
source venv/bin/activate
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Run Jupyter Notebook in the same directory

```bash
jupyter notebook
```

4. Open the Jupyter Notebooks in the browser


## Data Augmentation

Data augmentation is performed using PEGASUS text paraphrasing and synonym replacement. Ensure you have the necessary models or API keys for PEGASUS.

## Data Preprocessing

Data preprocessing is crucial for cleaning the text data. Regular expressions are applied to remove emojis, stop words, and punctuation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Mention any third-party libraries or tools you used.
- Credit PEGASUS for text paraphrasing.