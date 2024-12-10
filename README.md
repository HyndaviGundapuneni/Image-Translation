# Image OCR Translation App

The **Image OCR Translation App** is a Streamlit-based web application that allows users to upload an image, extract text from it using OCR (Optical Character Recognition), and then translate the extracted text into a selected language. 

Built using **EasyOCR** for OCR, **Google Translate API** for translation, and **Pillow** for image processing, this app provides a seamless experience for extracting and translating text from images.

## Features

- **Image Upload:** Upload an image in **JPG**, **JPEG**, or **PNG** format.
- **OCR Text Extraction:** Automatically extracts text from the image using **EasyOCR**.
- **Text Translation:** Translates the extracted text to a specified target language using **Google Translate**.
- **Multiple Language Support:** Supports translation to and from several languages.

## Supported Languages

The app currently supports OCR and translation for the following languages:

- **OCR Languages:** English (`en`)
- **Translation Languages:** English (`en`), French (`fr`), Spanish (`es`), German (`de`)

You can easily extend the list by modifying the supported languages section.

## Requirements

To run this app, you need to install the following Python libraries:

- `streamlit`
- `easyocr`
- `numpy`
- `Pillow`
- `googletrans`

You can install these libraries using `pip`:

```bash
pip install streamlit easyocr numpy Pillow googletrans
How to Run
Clone this repository or download the necessary files.

Install the required libraries as mentioned above.

Run the following command to start the Streamlit app:

bash
Copy code
streamlit run app.py
Open the app in your web browser (usually at http://localhost:8501).

Usage
Upload an Image: Click the "Upload an image" button to upload an image in JPG, JPEG, or PNG format.
Select OCR Target Language: Choose the target language for translation from the dropdown menu.
Perform OCR: Click the "Perform OCR" button to extract and translate the text from the image.
View Translated Text: The app will display the translated text extracted from the image.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
EasyOCR: Used for extracting text from images using Optical Character Recognition (OCR).
Google Translate API: Used for translating the extracted text.
Streamlit: A framework for building interactive web applications with Python.
css
Copy code

This `README.md` provides a detailed description of your app, including features, supported languages, installation steps, usage, and credits.





