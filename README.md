# NewsAutoAnalysisGaza

NewsAutoAnalysisGaza is a tool designed to scrape, analyze, and summarize news articles focusing on the Gaza conflict. By leveraging advanced Python libraries and OpenAI's GPT models, this application provides insightful visualizations such as word clouds and frequency analysis charts, alongside comprehensive summaries that offer a deeper understanding of the conflict's coverage in the media.


## Features
- **Article Scraping**: Automatically scrapes news articles from specified sources.
- **Data Analysis**: Performs text analysis to identify the most frequent terms and generates word clouds and bar charts.
- **Summarization**: Utilizes OpenAI's GPT models to generate concise summaries of the collected articles.
- **Automation**: Streamlines the entire process from data collection to analysis and summarization, requiring minimal user input.
  
## Getting Started

### Prerequisites
Ensure you have Python 3.x installed on your system. This project depends on several Python libraries, including `requests`, `beautifulsoup4`, `wordcloud`, `matplotlib`, `python-docx`, and `openai`. You can install these using pip:

  ```bash
  pip install requests beautifulsoup4 wordcloud matplotlib python-docx openai
  ```

### Installation
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/Op27/NewsAutoAnalysisGaza.git
    ```

2. Navigate to the project directory:
    ```bash
    cd NewsAutoAnalysisGaza
    ```

3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```
    Note: This command ensures that all the necessary Python packages are installed and up to date. If you have previously installed the required packages, this command will verify your installation, making it a safe operation to perform.


### Usage
To run the tool, execute the main script from the command line:
  ```bash
  python main.py
  ```

### Obtaining OpenAI API Key
For summarization features in NewsAutoAnalysisGaza, an API key from OpenAI is required. This key enables interaction with OpenAI's GPT models to generate summaries. To obtain an API key, users must create an account on the [OpenAI platform](https://openai.com/) and follow the instructions to register for API access. Please be aware that OpenAI's services might incur costs depending on the usage volume, so it's advisable to review their pricing structure. After obtaining your API key, ensure to secure it properly and not to share it publicly or with unauthorized users.

## How It Works
**Scraping**: The tool first scrapes news articles from pre-defined URLs.  
**Analysis**: Analyzes the text to generate visualizations and identify key themes.  
**Summarization**: Summarizes the content using GPT, producing a coherent overview of the main points.  

## Disclaimer 
### Web Scraping 
Web scraping, as utilized by NewsAutoAnalysisGaza for analyzing publicly available news articles, is legal within certain boundaries. However, it's critical to note that personal data is protected under GDPR in the European Union and by similar privacy laws worldwide. Users of NewsAutoAnalysisGaza should ensure not to scrape personal data unless they have a legitimate reason, in accordance with applicable privacy laws. We encourage users to familiarize themselves with and adhere to the terms of service of any source websites, including but not limited to BBC, when using this tool.

### Responsibility
The use of NewsAutoAnalysisGaza and any actions or consequences resulting from its application are solely the responsibility of the user. The project owners and contributors do not assume any legal liability or responsibility for the manner in which the tool is used or for ensuring compliance with applicable laws. Users are responsible for using NewsAutoAnalysisGaza in a manner that is consistent with all relevant legal requirements and regulations that apply to their specific circumstances.


## Contributing
Contributions to NewsAutoAnalysisGaza are welcome! If you have suggestions for improvements or new features, please feel free to:
- Open an issue to discuss what you would like to change.
- Fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/Op27/NewsAutoAnalysisGaza/blob/main/LICENSE) file for details.

