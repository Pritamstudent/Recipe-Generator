
# Recipe Generator

A simple web application for generating recipes using a pretrained language model.

# Overview

This web application uses the Hugging Face Transformers library to generate recipes based on user-provided prompts. It loads a pretrained language model that can generate text based on the input text provided by the user.

![Recipe Generator Screenshot](https://github.com/Pritamstudent/Recipe-Generator/assets/121369078/46e4f0ed-4c2b-49be-a595-8625cf1d05e8)

## Getting Started

### Prerequisites

- Python 3.6+
- Streamlit
- Transformers library by Hugging Face
- Trained model weights and tokenizer

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/recipe-generator.git
   cd recipe-generator
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Run the Streamlit application:

   ```bash
   streamlit run app.py
   ```

2. Access the web application by opening the provided URL in your web browser.

3. In the sidebar, enter a prompt text (e.g., "I want to make a delicious pasta dish") and click "Generate."

4. The generated recipe will be displayed on the right side of the page.

# Dataset

You can find the dataset for this project on Kaggle. Click the link below to access and download the dataset:

[Recipe Dataset on Kaggle](https://www.kaggle.com/datasets/pritamstudent/dataset-for-gpt-recipe-generation)

# Model

The application uses a pretrained language model fine-tuned on recipe generation tasks. You can replace the model and tokenizer with your own pretrained models if needed. Make sure to update the paths in the code accordingly.

# Configuration

You can customize the application by modifying the `app.py` file. For example, you can change the maximum length of generated text, temperature, top-k, and top-p values to adjust the randomness and creativity of the generated recipes.

# Acknowledgments

- [Hugging Face Transformers](https://github.com/huggingface/transformers)
- [Streamlit](https://streamlit.io/)
