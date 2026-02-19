# AI Legacy Code Summarizer
An intelligent **Generative AI** application developed to automate the documentation and analysis of legacy codebases. This tool uses **Anthropic Claude 3.5 Sonnet** via **Amazon Bedrock** to provide architectural and logical summaries of complex code.

##  Overview
Modernizing legacy systems is a major challenge in software engineering. This project demonstrates how **Generative AI** can be used to perform "Code-to-Text" synthesis, translating technical logic (Python, Java, or COBOL) into clear, structured English prose.

##  Technical Stack
* **AI Orchestration**: [LangChain](https://www.langchain.com/) (using LCEL for chain logic).
* **Foundation Model**: **Anthropic Claude 3.5 Sonnet** (via AWS Bedrock).
* **Cloud Infrastructure**: **Amazon Bedrock** (utilizing EU Inference Profiles for optimized routing).
* **Frontend**: **Streamlit** (Python-based web interface).
* **R&D Environment**: Originally prototyped and tested in **Google Colab**.


## 🚀Live Demo
You can check out the live application here: send message it needed **

*(Note: If the app is in 'Sleep Mode', click 'Yes, get this app back up' to wake it.)*

---

##  System Architecture
The application follows a production-grade GenAI workflow:
1.  **Input**: User selects the programming language and provides the source code.
2.  **Processing**: LangChain formats the request and manages the conversation memory.
3.  **Inference**: The system performs a secure, cross-region inference call to **AWS Bedrock**.
4.  **Output**: A detailed summary of the code logic is generated and rendered in real-time.

##  Installation (Local Testing)
To run this project on your local machine:

1.  Clone the repository:
    ```bash
    git clone [https://github.com/YOUR-GITHUB-USERNAME/legacy_code_ai_summarizer.git](https://github.com/YOUR-GITHUB-USERNAME/legacy_code_ai_summarizer.git)
    ```
2.  Install requirements:
    ```bash
    pip install -r requirements.txt
    ```
3.  Add your AWS credentials to a `.streamlit/secrets.toml` file.
4.  Run the app:
    ```bash
    streamlit run app.py
    ```

---

##  Development Journey
Developed by **Akhil Kamble**
