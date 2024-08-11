# Friendzee: An AI Chatbot
Friendzee is an AI chatbot designed to provide emotional support for individuals who may find it challenging to express their feelings. This project features a custom-developed dataset, on which a Recurrent Neural Network (RNN) has been trained to generate response. The project has been deployed using a Flask server. Integration between the frontend and
backend is achieved through REST API, where the trained model delivers a empathetic response.

The corpus of the dataset used to train Friendzee has been carefully developed and collected from various books and other resources under the guidance of a professional therapist. However, please note that the dataset is still under development, and the chatbot's performance and accuracy may improve as the dataset is further refined. The dataset is not shared here with the project but will be made public once it is fully developed.


<div align="center"><img src="https://github.com/user-attachments/assets/2e4bd203-350e-416f-8dc9-caf7ca33a264"></div>

## Key Features

- Basic conversational abilities using NLP.
- Simple and modular code structure for easy customization.
- Demonstrates how to preprocess text data for chatbot training.
- Simple and intuitive interface for seamless interaction.

## Installation

To run the code in this repository, you need to have Python installed along with the following dependencies:

- Numpy
- NLTK
- TensorFlow
- TFLearn
- Flask (for web-based interaction)

## Usage
The main implementation is provided in the Jupyter Notebook AI_Chatbot.ipynb. You can run this notebook to see how the chatbot processes inputs and generates responses.

### Steps to Run
1. Clone the repository:
```bash
git clone https://github.com/Dipon12/Friendzee-An-AI-Chatbot.git
cd Friendzee-An-AI-Chatbot
```

2. Open the Jupyter Notebook and run the cells to interact with the chatbot:

```bash
jupyter notebook "AI_Chatbot.ipynb"
```

3.  To interact in a web-based interface, you can deploy the chatbot using Flask. Install flask and run the following in the terminal:

```bash
python app.py
```

## Files
- AI_Chatbot.ipynb: The Jupyter Notebook containing the chatbot's implementation and step-by-step explanations.
- app.py: A Flask application script for deploying the chatbot as a web service.
- requirements.txt: A list of required Python packages.
- README.md: This file, providing an overview of the project.

## Acknowledgments
- Inspired by the advancements in AI and NLP.
- Thanks to the open-source community for providing valuable tools and libraries.
