# Build AI Agents using MCP

## DISCLAIMER
    
This repository contains my work for the **Build AI Agents using MCP** course.

It includes code, notebooks, and implementations related to the **Model Context Protocol (MCP)**, including MCP servers, clients, and AI agent workflows.

The code on this project is part of Coursera´s IBM Build AI Agents using MCP, the goal of the repository is to document my learning progress and use git and Github on the process.

## Project Structure

```text
.
├── Module 1/
│   ├── MCP-powered LangGraph application.py
│   ├── Run Existing MCP Servers.ipynb
│   └── stdio_server.py
│
├── Module 2/
│   ├── Lesson 1/
│   │   └── FINAL Hello World of MCP Servers
│   └── Lesson 2/
│       ├── client.py
│       └── server.py
│
├── Module 3/
│   └── Work in Progress
│
├── .gitignore
├── README.md
└── requirements.txt
```

## Modules

### Module 1 — Getting Started with MCP

This module introduces the basics of MCP and how to run existing MCP servers.

It includes introductory examples, notebooks, and a simple `stdio_server.py` implementation.

### Module 2 — MCP Server

This module focuses on building an MCP server and connecting it with a client.

Main files:

- `server.py`: MCP server implementation.
- `client.py`: Client-side logic to interact with the MCP server.
- Lesson notebooks and exercises for reference.

### Module 3 — MCP Hosts and Clients

This module explores MCP hosts and client implementation patterns.

It focuses on how clients connect to MCP servers and how MCP can be integrated into broader AI agent workflows.

## Setup

This repository was run and built on IBM SkillsBuild platform so API keys used were local. Please use your own API keys to run some of the scripts in the repo.

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it on macOS/Linux:

```bash
source .venv/bin/activate
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Code

The exact command depends on the module or lesson you are working on.

For Python scripts, run them from the corresponding module folder. For example:

```bash
python server.py
```

or:

```bash
python client.py
```

For notebooks, open the `.ipynb` files in VS Code or Jupyter.

## Notes

- Environment files such as `.env` are ignored for security.
- Virtual environments such as `.venv/` are ignored.
- Cache files and local system files are excluded through `.gitignore`.

## Goal

The goal of this repository is to document my learning process while building AI agents using MCP, including:

- Running existing MCP servers.
- Creating custom MCP servers.
- Building MCP clients.
- Understanding how MCP connects tools, hosts, and AI agents.

