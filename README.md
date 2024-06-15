# MultiLanguage Invoice Extractor

This project is a Streamlit application that leverages the Google Generative AI Gemini Pro Vision model to extract information from invoices in various languages. The application allows users to upload an invoice image and provide an input prompt, and the Gemini Pro Vision model generates a response based on the image and the prompt.

## Features

- Upload invoice images in JPG, JPEG, or PNG formats.
- Provide an input prompt to guide the Gemini Pro Vision model's response.
- Display the uploaded image for visual confirmation.
- Generate a response from the Gemini Pro Vision model based on the input prompt and the uploaded image.

## Prerequisites

- Python 3.x
- Google Cloud Platform account (to obtain the API key for Generative AI)

## Setup

1. Clone the repository: `git clone https://github.com/your-repo/MultiLanguage-Invoice-Extractor.git`
2. Navigate to the project directory: `cd MultiLanguage-Invoice-Extractor`
3. Create a virtual environment (optional but recommended): `python -m venv env`
4. Activate the virtual environment:
   - On Windows: `env\Scripts\activate`
   - On Unix or macOS: `source env/bin/activate`
5. Install the required dependencies: `pip install -r requirements.txt`
6. Set up the Google API key:
   - Obtain an API key from the Google Cloud Console.
   - Create a `.env` file in the project directory.
   - Add the following line to the `.env` file, replacing `<your-api-key>` with your actual API key:
     `GOOGLE_API_KEY=<your-api-key>`

## Usage

1. Run the Streamlit application: `streamlit run invoice.py`
2. The application will open in your default web browser.
3. Upload an invoice image by clicking the "Choose an image..." button.
4. Provide an input prompt in the text input field.
5. Click the "Tell me about the invoice" button.
6. The Gemini Pro Vision model's response will be displayed on the page.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.


## Acknowledgements

- [Streamlit](https://streamlit.io/) for the great Python library for building interactive web applications.
- [Google Generative AI](https://cloud.google.com/generative-ai) for providing the Gemini Pro Vision model.

