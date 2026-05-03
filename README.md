# 📊 Data Processing Project "Good manners" (اخلاق حميدة)
## 1.Definition of the problem and project context
This project is a Natural Language Processing (NLP) application focused on analyzing and classifying Arabic text related to human behavior and manners.

🧠 Problem Definition & Context

Understanding and categorizing human values and behaviors expressed in text is a challenging task, especially in Arabic due to its linguistic complexity. This project aims to automatically classify textual content—such as citations, poems, and short paragraphs—based on whether they represent positive (good) manners or negative (bad) manners.

📊 Dataset
Collected over 5,000 Arabic text samples through web scraping using Python
Data includes:
Citations
Poems
Paragraphs related to ethics and behavior<br><br>
⚙️ Methodology

The project follows a complete NLP pipeline:

Web Scraping
Automated data collection from multiple online sources
Data Preprocessing
Text cleaning (removal of noise, punctuation, etc.)
Normalization of Arabic text
Feature Engineering
Named Entity Recognition (NER)
Stemming for Arabic words
Model Development
Trained a Machine Learning model to classify text into:
✅ Good manners
❌ Bad manners
## 2.Selection and collection of data
### Prerequisites
Before starting this project, ensure you have the following software and libraries installed:
1. **Python** (version 3.x)
2. **VSCode** (or any preferred code editor)

#### Python Libraries
Make sure you have the following libraries installed:
- **requests**: For sending HTTP requests.
- **BeautifulSoup**: For parsing HTML and XML documents.
- **camel_tools**: A library for processing and analyzing Arabic text, including:
  - `SentimentAnalyzer`
  - `MorphologyDB`
  - `Analyzer`
  - `simple_word_tokenize`
- **xlsxwriter**: For creating and writing to Excel files.
- **csv**: A built-in Python library for working with CSV files.
#### Installation
1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/your-repository-name.git
    cd your-repository-name
    ```

2. **Create a virtual environment** (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows, use: venv\Scripts\activate
    ```

3. **Install the required libraries**:
    ```bash
    pip install requests beautifulsoup4 camel-tools xlsxwriter
    ```
### Usage
1. **Open the project** in VSCode or your preferred code editor.
2. **Run the main script**:
    ```bash
    python main.py
    ```
 
