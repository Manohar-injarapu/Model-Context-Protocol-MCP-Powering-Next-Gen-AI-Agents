# Model-Context-Protocol-MCP-Powering-Next-Gen-AI-Agents
MCP acts like a universal interface or “bridge” so AI agents can interact with multiple sources reliably

## 📌 Overview
Traditional AI chatbots (including ChatGPT) **cannot access local files or folders directly**.  
The **Model Context Protocol (MCP)** solves this problem by standardizing how **AI language models (LLMs)** connect to **local and external tools, data, and systems**.

 "MCP client connect to MCP server access to file system"
---

## 🧠 What is Model Context Protocol (MCP)?
- MCP is an **open standard** introduced by **Anthropic (Nov 2024)**.
- Designed to standardize **AI-to-tool communication**.
- Acts as a **universal bridge** between AI agents and real-world systems.
- Enables context-aware, tool-using AI agents.

---

## 🏗️ MCP Architecture
MCP follows a **Client–Server model**:

### 🔹 Client
- AI-enabled applications (e.g., Claude Desktop)
- Sends **context queries** to MCP servers

### 🔹 Server
- Provides:
  - Local file system access
  - Databases
  - APIs
  - Tool execution

---

## ✨ Key Capabilities
- Access **live external data** (files, databases, APIs)
- Read and write **local files in real time**
- Execute actions beyond text responses
- Enable **agentic AI workflows**
- Reusable and standardized integrations

---

## 🌍 Industry Adoption
- Introduced by **Anthropic**
- Supported by:
  - OpenAI
  - Google DeepMind
  - Microsoft

---

## 🛠️ Workshop Setup – Step by Step

### 1️⃣ Install Claude Desktop
- Download and install **Anthropic Claude Desktop**

---

### 2️⃣ Install Node.js
- Install **Node.js (LTS version)**
- Required to run MCP servers via `npx`

---

### 3️⃣ Configure MCP File System Server
- Go to MCP GitHub repository:
mcp → server → file-system


Copy code
- Copy the **NPX command**

---

### 4️⃣ Enable File System Extension
1. Open **Claude Desktop**
2. Go to:
Settings → Extensions → Browse Extensions

yaml
Copy code
3. Select **File System**
4. Close settings

---

### 5️⃣ Grant Local Directory Access
1. Open **File System**
2. Enable it
3. Provide your **local directory path**
4. Click **Add Directory**
5. Select **Always Allow**
6. Save

---

### 6️⃣ Update Developer Configuration
1. Go to:
Developer → Edit Config


Copy code
2. Open Claude configuration file
3. Paste the **NPX command**
4. Add your **local directory path**
5. Save and close

---

## ✅ Result
Claude can now:
- Access local files and folders
- Read, write, and edit files
- Perform file operations using natural language prompts

