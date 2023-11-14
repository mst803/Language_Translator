# Language Translator Readme

This is a simple language translator demo created using Streamlit and the Googletrans library. The application allows users to input text and select a target language for translation.

## Prerequisites

Before running the application, make sure you have the following dependencies installed:

pip install streamlit googletrans==4.0.0-rc1

## How to Run

1. Save the provided code in a Python file, e.g., `translator_app.py`.
2. Open a terminal and navigate to the directory where the file is saved.
3. Run the Streamlit application:

streamlit run translator_app.py

4. The application will open in your default web browser.

## Usage

1. Enter the text you want to translate in the text area.
2. Choose the target language from the dropdown menu (options: Malayalam, Hindi, Tamil).
3. Click the "Translate" button to see the translated text.

## Notes

- The translation is powered by Googletrans, which utilizes Google Translate. Ensure you have a stable internet connection for the translation to work.
- Googletrans library may not work in some environments due to restrictions imposed by Google. In such cases, you might need to explore other translation APIs or solutions.

Feel free to modify and expand upon this code to add more features or improve the user interface based on your requirements. If you encounter any issues or have suggestions for improvement, please refer to the documentation for Streamlit and Googletrans for assistance.
