# Gradio & Hugging Face Tutorial

## Tutorial Overview
This tutorial explores how to build interactive web applications for machine learning using **Gradio**. We demonstrate how to use `gr.Blocks` to create complex layouts with **Rows** and **Columns**, integrate interactive **Sliders** and **Image** inputs, and connect deep learning models to the UI.

## The App & Model
The application features a dual-purpose dashboard:
1. **Intergalactic Passport Creator:** A custom UI layout using Gradio's layout components to process biometric images and user metadata.
2. **AI Sentiment Analyst:** Integrated with the Hugging Face `transformers` library using the **DistilBERT** model (`distilbert-base-uncased-finetuned-sst-2-english`). This model is a light, fast version of BERT designed to classify text sentiment with high accuracy.

## How to Run
Click the `gradio_tutorial.ipynb` file in this repository and select "Open in Colab" to run the interactive demo.
