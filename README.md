# Information Extractor for RFP Documents  

This project was developed as part of a data science mini project assignment for academics, focusing on extracting structured information from various document types, such as HTML and PDF, related to the Request for Proposals (RFP) process.  

## Objective  

To extract structured data from RFP-related documents and present it in a predefined JSON format, leveraging Language Models (LLMs), NLP techniques, and parsing tools.  

---

## Features  

- **Multi-format Support**: Parses both HTML and PDF documents.  
- **Text Extraction**: Extracts relevant sections of text efficiently.  
- **Information Structuring**: Maps extracted content to a predefined schema.  
- **JSON Output**: Outputs the structured information in a JSON format.  
- **Robust Processing**: Handles varying document structures.  

---

## Prerequisites  

- Python 3.8 or higher  
- Jupyter Notebook (optional, if running interactively)

---

## Execution

- 1.Open the Jupyter Notebook
Run this command "jupyter notebook Information_extractor.ipynb"
- 2.Run the notebook cells in sequence to process the provided documents.

---

## Folder Structure

## Folder Structure  

```plaintext
project/  
├── bid1 & bid2/                   # Folder for input HTML and PDF documents  
├── output1.json & output2.json    # Files for generated JSON outputs  
├── Information_extractor.ipynb    # Main code notebook  
└── README.md                      # This readme file
```


## Output Format  

The structured data is extracted into a JSON format with the following fields:  

```json
{  
  "Bid Number": "12345",  
  "Title": "Project Title",  
  "Due Date": "YYYY-MM-DD",  
  "Bid Submission Type": "Online/Offline",  
  "Term of Bid": "Duration",  
  "Pre Bid Meeting": "Details",  
  "Installation": "Yes/No",  
  "Bid Bond Requirement": "Details",  
  "Delivery Date": "YYYY-MM-DD",  
  "Payment Terms": "Details",  
  "Additional Documentation Required": "Yes/No",  
  "MFG for Registration": "Details",  
  "Contract or Cooperative to use": "Details",  
  "Model_no": "Details",  
  "Part_no": "Details",  
  "Product": "Details",  
  "Contact Info": "Details",  
  "Company Name": "Details",  
  "Bid Summary": "Summary Text",  
  "Product Specification": "Specification Details"  
}
```

## Key Libraries Used  

- **PyPDF2**/`pdfplumber`: For PDF parsing.  
- **BeautifulSoup**: For HTML parsing.  
- **transformers**/`spaCy`: For NLP and LLM processing.  

---

## Deliverables  

- Python notebook (`Information_extractor.ipynb`) for processing documents.  
- JSON files for structured outputs.  
- This README file.  

---

## Evaluation Criteria  

- **Accuracy**: Correctly structured output for all provided documents.  
- **Robustness**: Handles diverse document structures.  
- **Code Quality**: Clean, modular, and well-documented.  
- **Effective Use of NLP**: Leverages LLMs or NLP for enhanced processing.  

---

## Notes  

- The script is not designed to be highly scalable for handling very larger document sets.  

---

Developed by Abhishek A, as part of the mini project assignment process for academics.





