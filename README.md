This script identifies semantically similar web pages by crawling URLs, generating text embeddings, and calculating cosine similarity between them. It saves results in an Excel file for analysis.

**Features**	
  •	Crawl Web Pages: Extracts titles, meta descriptions, and visible text from URLs.
	•	Generate Text Embeddings: Uses OpenAI’s text-embedding-ada-002 model to encode content.
	•	Semantic Similarity: Computes cosine similarity between embeddings to find related pages.
	•	Export Results: Saves similarity scores and content embeddings to an Excel file with two organized tabs.

**Requirements**

Python Packages

Install the required packages using pip: pip install requests beautifulsoup4 openai pandas scikit-learn numpy openpyxl

API Key
	•	Obtain an API key from OpenAI.
	•	Replace your-api-key in the script with your API key.

 **Usage**
	1.	Prepare Input
	•	Create an Excel file (e.g., input_urls.xlsx) with a column named URL, listing all the URLs to analyze.
	2.	Run the Script
	•	Replace input_file and output_file in the script with your input and desired output file names.
	•	Execute the script

 **View Results**
	•	Similarity Check Tab: Displays URL pairs with a similarity score above 0.8.
	•	Embeddings and Content Tab: Stores the crawled content and its corresponding embedding.
