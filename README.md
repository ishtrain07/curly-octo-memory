News Article Summarizer
A simple tool to summarize news articles from a given URL using the t5-base NLP model, implemented in a Google Colab notebook.

Features
Fetch and parse articles from a URL.
Generate concise summaries using a pre-trained NLP model.
Adjust summary length dynamically based on the article length.
User-friendly interface within a Google Colab notebook.

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/ishtrain07/curly-octo-memory.git
Open the Google Colab notebook:

Go to Google Colab.
Click on File > Upload Notebook.

Upload the LLM_News_Summarizer.ipynb file from the cloned repository.
Install dependencies:

python
Copy code
!pip install newspaper3k transformers torch

Usage
Run the Colab notebook:
Follow the instructions in the notebook cells.
You will be prompted to enter the URL of the news article you want to summarize.

Example
After running the notebook, you will be prompted to enter the URL of the news article. The notebook will fetch the article, generate a summary, and display the original length and summary length.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
If you have any questions or suggestions, please feel free to reach out.
