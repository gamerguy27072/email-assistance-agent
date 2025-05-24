# AI Personal Assistant

An intelligent personal assistant leveraging **LangGraph** to automate email processing, summarization, and response drafting with context-aware interactions.

---

## ✨ Features

* **Automated Email Processing:** Efficiently handles incoming emails, reducing manual effort.
* **Intelligent Summarization:** Automatically distills key information from emails, providing quick insights.
* **Drafting Capabilities:** Generates intelligent response drafts, streamlining communication.
* **Persistent Memory:** Implements long-term memory for context-aware interactions, enabling personalized and consistent email handling over time.
* **Stateful Agentic Workflow:** Designed with a robust, multi-step **LangGraph** agentic workflow to manage complex email tasks reliably and efficiently.

---

## 🛠️ Technologies Used

* **Python**
* **LangGraph**
* **uv** (for dependency management and virtual environments)

---

## 🚀 Getting Started

Follow these steps to set up and run the AI Personal Assistant locally.

### Prerequisites

* Python 3.9+
* `uv` installed: `pip install uv`

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/gamerguy27072/report-writter-agent.git](https://github.com/gamerguy27072/report-writter-agent.git)
    cd your-repo-name
    ```

2.  **Create and activate a virtual environment with `uv`:**
    ```bash
    uv venv
    source .venv/bin/activate # On macOS/Linux
    # .venv\Scripts\activate   # On Windows (in PowerShell/Cmd)
    ```

3.  **Install dependencies:**
    ```bash
    uv pip install -e .
    ```

### Configuration

* **API Keys:** You will likely need API keys for your Large Language Model (LLM) provider (e.g., OpenAI, Google AI). Create a `.env` file in the root directory of the project and add your keys:
    ```
    OPENAI_API_KEY=your_openai_api_key
    # Add other keys as needed, e.g., GOOGLE_API_KEY
    ```

### Running the Project

To start the AI Personal Assistant, execute the main application file:

```bash
python main.py # Or whatever your primary entry point script is named