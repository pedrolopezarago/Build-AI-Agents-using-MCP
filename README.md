# Module 2: MCP Server and Client Implementation

This repository contains the source code for Module 2 of Build AI Agents using MCP. It focuses on implementing a Model Context Protocol (MCP) server-client architecture.

## 📂 Project Structure

* **Lesson 1**: 
    * Initial setup and "Hello World" of MCP Server.
* **Lesson 2**: 
    * `server.py`: The MCP server implementation.
    * `client.py`: The client-side logic to interact with the server.
    * `requirements.txt`: Python package dependencies.
* `.gitignore`: Configured to exclude environments (`.env`, `.venv`), cache, and local study materials.

## 🛠️ Setup & Installation

1.  **Initialize a Virtual Environment:**
    ```bash
    python -m venv .venv
    source .venv/bin/activate  # On Windows: .venv\Scripts\activate
    ```

2.  **Install Requirements:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Environment Configuration:**
    Ensure you create a `.env` file for any necessary API keys or configuration strings.

## 🚀 Running the Application

To run the MCP system, you  need to start the server and the client:

```bash
python client.py server.py
