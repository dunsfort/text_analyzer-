# PDF Extraction and Analysis Tool

This tool provides various functionalities to extract and process information from PDF files, including text extraction, image extraction, optical character recognition (OCR) on images, table extraction, text preprocessing, and detailed text analysis.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Functions](#functions)
    - [Extract Text from PDF](#extract-text-from-pdf)
    - [Extract Images from PDF](#extract-images-from-pdf)
    - [OCR on Images](#ocr-on-images)
    - [Extract Tables from PDF](#extract-tables-from-pdf)
    - [Preprocess Text](#preprocess-text)
    - [Combine All Steps](#combine-all-steps)
    - [Detailed Text Analysis](#detailed-text-analysis)
    - [Further Analysis and Visualization](#further-analysis-and-visualization)
4. [Results](#results)
    - [Top Terms by TF-IDF](#top-terms-by-tf-idf)
    - [Sentiment Analysis](#sentiment-analysis)
    - [Visualizations](#visualizations)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/pdf-extraction-analysis.git
    ```
2. Navigate to the project directory:
    ```sh
    cd pdf-extraction-analysis
    ```
3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

To use the tool, open the `notebook.ipynb` file in Jupyter Notebook or JupyterLab and follow the instructions in the notebook.

## Functions

### Extract Text from PDF

The `extract_text_from_pdf` function extracts text from a PDF file.

### Extract Images from PDF

The `extract_images_from_pdf` function extracts images from a PDF file.

### OCR on Images

The `ocr_image` function performs optical character recognition (OCR) on images extracted from the PDF.

### Extract Tables from PDF

The `extract_tables_from_pdf` function extracts tables from a PDF file.

### Preprocess Text

The `preprocess_text` function preprocesses the extracted text by converting to lowercase, removing numbers and punctuation, and removing stopwords.

### Combine All Steps

The `extract_text_with_handling` function combines all the steps to extract text, images, perform OCR on images, extract tables, and preprocess text.

### Detailed Text Analysis

The notebook includes code for detailed text analysis using TF-IDF to identify the top terms.

### Further Analysis and Visualization

The notebook provides further analysis and visualizations, including word cloud and bar chart of TF-IDF scores, and sentiment analysis.

## Results

### Top Terms by TF-IDF

Identifies the most significant terms in the document.

### Sentiment Analysis

Provides an overview of the emotional tone conveyed by the text.

### Visualizations

Includes word clouds and bar charts to understand the most frequent and significant terms in the document.

---

For more details, refer to the Jupyter notebook (`notebook.ipynb`).


```python

```
