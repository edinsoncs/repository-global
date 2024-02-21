Document Information Extractor

This project uses Streamlit to create a web application that allows users to upload PDF files and extract structured information from them using OCR (Optical Character Recognition) and Hugging Face language models.
Installation

    Clone this repository to your local machine:

    bash

git clone https://github.com/edinsoncs/document-information-extractor.git

Install the dependencies using pip:

bash

    pip install -r requirements.txt

Usage

    Make sure you have a folder named pdfs in the root directory of your project. This folder should contain the PDF files from which you want to extract information.

    Run the Streamlit application:

    bash

    streamlit run app.py

    The application will open in your browser. Use the file upload widget to select a PDF file and then click the "Process" button to extract structured information from the document.

Features

    Conversion of PDF files into images for processing.
    Extraction of text from images using OCR.
    Extraction of structured information using Hugging Face language models.
    User-friendly interface with Streamlit.

Contributing

If you'd like to contribute to this project, follow these steps:

    Fork the repository.
    Create a new branch (git checkout -b feature/new-feature).
    Make your changes and commit them (git commit -am 'Add new feature').
    Push to the branch (git push origin feature/new-feature).
    Create a new Pull Request.

Credits

    This project was created by Edinson Carranza.

License

This project is licensed under the MIT License. See the LICENSE file for more information.
