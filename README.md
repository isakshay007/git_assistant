
# Git Assistant 👨‍💻

## Overview
The **Git Assistant** is a Streamlit-based application powered by **Lyzr Agent API**. It simplifies version control by converting natural language inputs into precise Git commands. With the integration of advanced AI models, this app provides developers with an intuitive way to manage Git workflows efficiently.

---

## Features
- **AI-Driven Git Command Generator**:
  - Analyze natural language inputs to generate accurate Git commands.
  - Provides clear explanations for the generated commands.
- **Tool Integration**:
  - Utilizes `perplexity_search` for context-aware command generation.
- **Interactive UI**:
  - Accepts user-friendly natural language queries.
  - Displays the corresponding Git commands with explanations.

---

## Installation

### Prerequisites
- **Python**: Ensure Python 3.8 or higher is installed.
- **Dependencies**: Install required packages via `requirements.txt`.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/git-assistant.git
   cd git-assistant
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your **API Keys**:
   - Create a `.env` file in the project directory.
   - Add your API keys in the following format:
     ```env
     OPENAI_API_KEY="your_openai_api_key"
     LYZR_API_KEY="your_lyzr_api_key"
     ```

4. Run the application:
   ```bash
   streamlit run app.py
   ```

5. Open your browser and navigate to:
   ```
   http://localhost:8501
   ```

---

## Usage

1. **Enter Natural Language Query**: Input your desired Git operation in plain language.
   - Example: *"Create a new branch and switch to it."*

2. **Generate Commands**: Click the **"Generate!"** button to view the suggested Git command.

3. **Review Results**: The app provides a Git command tailored to your input, along with an explanation.

---

## File Structure
```
git-assistant/
│
├── app.py                  # Main application file
├── lyzr_agent.py           # Lyzr Agent API integration
├── requirements.txt        # Python dependencies
├── .env                    # API key configuration
└── .streamlit/             # Streamlit configuration
    └── config.toml         # UI settings
```

---

## Key Functionalities

### 1. **Natural Language Input**
- Accepts plain language descriptions of Git tasks.

### 2. **Git Command Generation**
- Uses Lyzr Agent API and OpenAI models to generate accurate Git commands.

### 3. **Explanations**
- Provides detailed explanations for the generated commands.

---

## Dependencies

- **Streamlit**: Interactive UI framework.
- **Lyzr Agent API**: Integrates advanced AI capabilities.
- **dotenv**: Manages environment variables securely.
- **requests**: Handles API interactions.
- **Python (>=3.8)**

### Install all dependencies with:
```bash
pip install -r requirements.txt
```

---

## Acknowledgments
- Built with the **Lyzr Agent API**.
- Designed to streamline Git workflows and enhance developer productivity.
