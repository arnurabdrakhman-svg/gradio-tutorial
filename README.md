# Gradio & Hugging Face Integration Tutorial

## Tutorial Overview
This repository contains a step-by-step tutorial designed to introduce developers to **Gradio**, a Python library for creating rapid machine learning demos. The tutorial is divided into two distinct sections: first, mastering custom layouts (using Rows, Columns, and Blocks) by building a creative "Intergalactic Passport Creator," and second, integrating deep learning models by connecting the **Hugging Face** `transformers` library to a frontend interface. The goal is to demonstrate how easily Python scripts can be transformed into interactive web applications.

## Model & App Description
The deep learning portion of this tutorial features a **Sentiment Analysis App** powered by the **DistilBERT base uncased** model (via the Hugging Face `sentiment-analysis` pipeline). DistilBERT is a smaller, faster, cheaper, and lighter version of BERT, pre-trained on the same corpus. The app takes raw text input from the user, processes it through the model to detect emotional tone (POSITIVE or NEGATIVE), and returns the confidence score, demonstrating a practical use case for NLP integration in web apps.

## How to Run
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/gradio-tutorial.git](https://github.com/YOUR_USERNAME/gradio-tutorial.git)
   cd gradio-tutorial
