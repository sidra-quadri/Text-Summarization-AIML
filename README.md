# Text Summarization Project using AIML

## Project Overview

This project is a **Text Summarization** application developed using **Artificial Intelligence (AI)** and **Machine Learning (ML)** techniques. The application takes large text inputs and generates a concise, accurate summary. The goal of the project is to save users' time by providing a shortened version of lengthy texts while preserving key information.

## Key Technologies Used

- **Gradio**: A user-friendly library that enables the creation of interactive interfaces for machine learning models. I used Gradio to build an intuitive front-end interface for users to input text and get summaries instantly.
  
- **AIML Model**: The model leverages state-of-the-art Natural Language Processing (NLP) techniques to process large blocks of text and extract the most important information for summarization.

## Features

- **Text Input**: Users can input large paragraphs or articles to be summarized.
- **Instant Summary**: Once the text is provided, the system will generate a concise, human-readable summary.
- **Interactive UI**: The application is equipped with a simple and easy-to-use interface via Gradio for an enhanced user experience.

## Installation

### Prerequisites

Before you start, ensure you have the following installed:
- Python 3.x
- Gradio
- Required libraries (`transformers`, `torch`, etc.)

### Step-by-step Instructions

1. **Clone the Repository**:
    ```bash
    git clone <repository-url>
    cd <project-directory>
    ```

2. **Run**:
    ```bash
    gradio.ipynb
    ```
    This will run the project, and you can access the application via your Google colab or Jupyter.

4. **Start Summarizing**:
    - Open the provided link in your browser.
    - Paste your text in the input box.
    - Click on the "Summarize" button to receive the summary.

## How It Works

1. **Text Input**: The user provides a long text (e.g., an article or research paper) into the input field.
2. **Preprocessing**: The text is tokenized and processed by the underlying NLP model.
3. **Summarization**: The model generates a summary by extracting important information.
4. **Output**: The summary is displayed in the output section for the user.

## Example

Here is an example of how you can use the system:

- **Input**: A detailed article about AI advancements.
- **Output**: A concise summary that highlights the main points about AI innovations and their impact.

## Glimpse of the project
![alt text](https://github.com/sidra-quadri/summary/blob/5c1b30e6328856e41a1efbaae94f5db79abead76/sum1.png)
<br> <br>
![alt text](https://github.com/sidra-quadri/summary/blob/5c1b30e6328856e41a1efbaae94f5db79abead76/sumR.png)
