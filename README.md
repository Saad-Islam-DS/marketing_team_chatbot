# Hearst Marketing Team Research Chatbot

A Streamlit app for generating data-driven crypto mining content and research for the Hearst marketing team.

## Features
- Researches crypto mining topics using credible sources
- Generates LinkedIn, Instagram, and X (Twitter) posts
- Provides technical summaries and simple explanations
- Exports results to Word documents

## Setup

1. **Clone the repository** and navigate to the `deployed` directory:
   ```bash
   cd path/to/deployed
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set the GROQ API Key**:
   - Obtain your `GROQ_API_KEY` from [Groq](https://groq.com/).
   - Set it as an environment variable:
     - On Linux/macOS:
       ```bash
       export GROQ_API_KEY=your_key_here
       ```
     - On Windows (CMD):
       ```cmd
       set GROQ_API_KEY=your_key_here
       ```
     - On Windows (PowerShell):
       ```powershell
       $env:GROQ_API_KEY="your_key_here"
       ```
   - Or add it to your Streamlit Cloud secrets if deploying there.

4. **Run the app**:
   ```bash
   streamlit run v1.py
   ```

## Deployment (Streamlit Cloud)
- Upload all files in the `deployed` directory to your Streamlit Cloud workspace.
- Set the `GROQ_API_KEY` in the app's secrets or environment variables.
- Click 'Deploy'.

---

**Note:**
- Do not hardcode API keys in your code.
- For best results, use a recent version of Python (3.9+).
