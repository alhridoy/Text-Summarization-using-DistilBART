# Text-Summarization-using-DistilBART


This project demonstrates how to use the pre-trained DistilBART model from the Hugging Face Transformers library to perform text summarization. The project supports reading text from PDF files and generating concise summaries.

## Features

- Reads text from PDF files using PyMuPDF
- Generates text summaries using the DistilBART model
- Configurable chunk size and summary length
- Supports handling of large input texts by breaking them into smaller chunks

## Requirements

- Python 3.6 or higher
- PyMuPDF
- Transformers
- Pytorch

## Installation

1. Clone the repository: 
git clone https://github.com/your-username/text-summarization-distilbart.git



2. Install the required dependencies:
pip install -r requirements.txt




## Usage

1. Ensure you have a PDF file you want to summarize. Update the `pdf_path` variable in the example usage section with the path to your PDF file.

2. Run the script:

```python
python summarize.py
This will read the text from the PDF file, generate a summary, and print it to the console.

#Customization
You can customize the summarization process by adjusting the following parameters in the summarize_text function:

chunk_size: The size of the input text chunks. Adjust this value to optimize the performance for your use case.
max_length: The maximum length of the generated summary.
min_length: The minimum length of the generated summary.
You can also fine-tune the pre-trained DistilBART model on a domain-specific corpus to improve the summarization quality for your specific use case.

#Contributing
If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

#License
This project is licensed under the MIT License.
