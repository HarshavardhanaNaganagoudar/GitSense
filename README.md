# GitSense

**GitSense** is an AI agent built using the LangGraph framework that automatically analyzes and summarizes any GitHub repository.
Just provide a GitHub URL — and it will fetch the README, repo structure, and metadata to generate a concise, human-readable summary using Mistral AI.

---

## ⚙️ How It Works

1) Fetches repository metadata, README, and file tree using the GitHub API.
2) Summarizes the content using the Mistral Large Language Model (LLM).
3) Formats the output into a clean, readable summary of purpose, key features, and tech stack.

---

## Try it on Hugging Face Spaces

[Try it yourself](https://huggingface.co/spaces/nharshavardhana/GitSense)

---

## 🧩 Tech Stack

* LangGraph – for building the agent workflow
* LangChain MistralAI – for summarization via Mistral’s LLM
* Gradio – for the user interface
* GitHub REST API – to fetch repo data

---

## 📎 Example Output

🏗️ **Repository Purpose:**
To create an AI agent that functions as a **Model Context Protocol (MCP) server**, compatible with MCP clients like *Claude Desktop*. The repository provides a Gradio-based interface for deploying the server, enabling seamless integration with external AI clients. It includes a demo and a Hugging Face Spaces deployment for easy testing as a standalone AI agent.

✨ **Key Features:**
- Implements a **Model Context Protocol (MCP) server** for AI agent interoperability
- Gradio-based web interface for user interaction and server deployment
- Compatibility with MCP clients (e.g., *Claude Desktop*) via protocol adherence
- Pre-configured for deployment on **Hugging Face Spaces** as a standalone AI agent
- Includes a demo video showcasing integration with *Claude Desktop*
- Jupyter Notebook (`Gradio_MCP_server.ipynb`) for interactive development/testing

🧠 **Languages Used:**
Python (primary, inferred from Jupyter Notebook and Gradio usage), Markdown (README/LICENSE)

📁 **Notable Files:**
- {'file': 'Gradio_MCP_server.ipynb', 'purpose': 'Main Jupyter Notebook containing the **MCP server implementation** with Gradio UI. Likely includes code for protocol handling, AI agent logic, and client-server communication.'}
- {'file': 'README.md', 'purpose': 'Project overview with links to a **live Hugging Face Spaces demo** and a **demo video** demonstrating MCP client integration.'}
- {'file': 'LICENSE', 'purpose': 'Legal licensing terms (type unspecified in metadata).'}

⚙️ **Predicted Tech Stack:**
{'category': 'Core Framework', 'technologies': ['Gradio (for web UI/server interface)']}, {'category': 'Protocol', 'technologies': ['Model Context Protocol (MCP) (custom implementation)']}, {'category': 'AI/ML', 'technologies': ['Hugging Face Transformers (likely, given deployment on Spaces)', 'LangChain or similar (possible, for agent orchestration; not confirmed)']}, {'category': 'Deployment', 'technologies': ['Hugging Face Spaces (hosted demo)', 'Jupyter Notebook (development environment)']}, {'category': 'Languages/Tools', 'technologies': ['Python 3.x', 'JupyterLab/Notebook (for `.ipynb` files)', 'Google Drive (for demo video hosting)']}
