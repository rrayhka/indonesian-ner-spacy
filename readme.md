# Indonesian-NER-Spacy

SpaCy is an open-source Natural Language Processing (NLP) library that offers powerful tools for various language processing tasks. However, it does not natively support a Named Entity Recognition (NER) model for the Indonesian language. This project aims to bridge that gap by fine-tuning a SpaCy model specifically for Indonesian using the available dataset.

## Table of Contents

- [About](#about)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)

## About

This project provides a fine-tuned Named Entity Recognition (NER) model for the Indonesian language using SpaCy. By leveraging the available dataset, the model has been trained to recognize various entities within Indonesian text, such as names, organizations, locations, and more.

## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

- Python 3.8+
- SpaCy
- Jupyter Notebook

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/rrayhka/indonesian-ner-spacy.git
    cd indonesian-ner-spacy
    ```

2. Install SpaCy:

    ```bash
    pip install spacy
    ```

3. Ensure that SpaCy is correctly installed and the necessary SpaCy components are downloaded:

    ```bash
    python -m spacy download en_core_web_sm
    ```


## Usage

To fine-tune and test the Indonesian NER model, you can use the provided Jupyter notebooks:

1. **Data Preparation:**
   Run the `convert_data.ipynb` notebook to preprocess the dataset and convert it into a format suitable for training.

   ```bash
   jupyter notebook convert_data.ipynb
   ```

2. **Model Training:**
   Use the `modelling.ipynb` notebook to fine-tune the SpaCy model on the Indonesian dataset.

   ```bash
   jupyter notebook modelling.ipynb
   ```

3. **Testing:**
   After training, the model can be tested using the provided test dataset or any custom Indonesian text.

   ```bash
   jupyter notebook modelling.ipynb
   ```

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Inspiration

This project was inspired by [this post](https://yudanta.github.io/posts/train-an-indonesian-ner-from-a-blank-spacy-model/) by Yudanta, which provides a guide on training an Indonesian NER model from a blank SpaCy model. It served as a valuable reference in the creation and fine-tuning of this project.

## Contact

Akhyar - [khyar075@gmail.com](mailto:khyar075@gmail.com)
