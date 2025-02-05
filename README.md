# AI
# Children's Story Generator with AI Illustrations

## Overview
This project is an **AI-powered Children's Story Generator** that creates unique, interactive stories for children aged 4-10, complete with **AI-generated illustrations**. The stories are automatically formatted and exported into a **professionally designed PDF**.

The tool leverages cutting-edge technologies like **Groq's DeepSeek model** for story generation and **Hugging Face's models** for creating high-quality, animated-style illustrations.

## Key Features
- **Story Generation**: Generates original children's stories based on a given title.
- **AI-Powered Illustrations**: Creates illustrations related to the story pages using AI models.
- **PDF Creation**: Compiles the story and illustrations into a cleanly formatted PDF document.
- **Customizable Content**: Easily change the title, number of pages, and story details.

## Technologies Used
- **Groq API**: For generating children's stories using Groq’s DeepSeek-R1-Distill-Llama-70B model.
- **Hugging Face API**: For creating AI-generated illustrations.
- **Python**: The main programming language for implementing the backend logic.
- **ReportLab**: Used for generating the PDF files.
- **Pillow (PIL)**: Used for image processing and resizing.
- **textwrap**: For neatly formatting the story text in the PDF.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mohanreddypal25/AI

2.Install the required dependencies:

bash
Copy code

pip install -r requirements.txt

Note: You will need API keys for both Groq and Hugging Face to use the story generation and image generation features. Please sign up for API access on their respective websites and replace the API keys in the script.


Usage
Set up your API keys:

Obtain an API key from Groq and Hugging Face, and replace the placeholder keys in the code.
Run the script: After setting up your API keys, run the script with the following command:

bash
Copy code

python story_generator.py
This will:

Generate a story based on the specified title.
Create AI-generated images for the story pages.
Format the content into a PDF and save it to the output folder.

3. Customize the story: You can change the title and number of pages to create different stories by modifying the title and num_pages variables in the script.

Example Output
The output will be a PDF file located in the ./story_output directory. The file will contain:

A cover page with an illustration.
The generated story pages with corresponding illustrations.
The PDF will be named in the format: story_timestamp.pdf.

Future Improvements

Interactive UI: A simple web interface using Flask or Streamlit for non-technical users to generate stories.
Personalized Stories: Allow users to customize character names, settings, and themes.
Additional Languages: Support for generating stories in multiple languages.
Contributing
We welcome contributions! If you have suggestions for improvements or find any bugs, feel free to open an issue or submit a pull request
