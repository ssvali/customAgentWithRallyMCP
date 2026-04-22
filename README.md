# 🧪 Custom Agent with Rally MCP – Manual Test Case Generator

## 📌 Overview
This repository provides a **custom AI agent** built using the **Model Context Protocol (MCP)** to integrate with **Rally (Agile Central)** and generate **manual test cases** from user stories.

The agent automatically:
- Fetches User Stories from Rally
- Parses descriptions and acceptance criteria
- Generates structured **manual test cases**
- Ensures coverage using standard QA techniques

---

## 🚀 Key Features

- 🔗 **Rally Integration via MCP**
  - Fetch user stories, descriptions, and acceptance criteria
  - Access Rally artifacts securely through MCP

- 🧠 **Intelligent Test Case Generation**
  - Converts requirements into testable scenarios
  - Identifies implicit and missing cases

- 📋 **Manual Test Case Focus**
  - Step-by-step execution-ready test cases
  - Human-readable format (no automation scripts)

- ✅ **Comprehensive Coverage**
  - Positive scenarios
  - Negative scenarios
  - Edge cases
  - Boundary Value Analysis (BVA)
  - Alternate flows

---

## 🏗️ Architecture
Rally → MCP Server → Custom Agent → Test Case Generator → Output (Markdown/CSV)

### Components:
- **Rally MCP Server**
  - Acts as a bridge between Rally and the agent
- **Custom Agent**
  - Processes requirements and generates test cases
- **LLM Engine**
  - Applies QA logic and test design techniques

---
