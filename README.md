PDF to Text Extraction using Azure AI Vision and Google Colab
This project automates the process of extracting text from PDF files using Azure AI Vision and Google Colab. The solution converts each page of a PDF into JPG images, extracts text from each image, and writes the results into a text file.

Prerequisites
Before you begin, ensure you have the following:

Azure Account: You need an Azure account to access Azure AI Vision services.
Azure AI Vision Key and Endpoint: Obtain your Azure AI Vision key and endpoint from the Azure portal.
Google Colab Account: A Google account to use Google Colab.
Python Libraries: The following Python libraries are required:
dotenv
os
time
PIL (Pillow)
matplotlib
azure-ai-vision
azure-core
fitz (PyMuPDF)
google.colab
Setup
Clone the Repository: Clone this repository to your local machine or open it in Google Colab.
Install Required Libraries: Install the required Python libraries using pip:
pip install python-dotenv pillow matplotlib azure-ai-vision azure-core pymupdf

Create a .env File: Create a .env file in the root directory and add your Azure AI Vision key and endpoint:
AI_SERVICE_ENDPOINT=your_azure_ai_service_endpoint
AI_SERVICE_KEY=your_azure_ai_service_key

How to Run
Upload the PDF File: Run the code in Google Colab and upload the PDF file when prompted.
Execute the Code: The code will convert each page of the PDF into JPG images, extract text from each image, and write the results into a text file named output_text.txt.
