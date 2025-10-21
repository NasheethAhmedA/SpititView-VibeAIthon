# 🧠 AR-HOST — AR-Agent Hosting Service

### Bringing AI Agents to the Real World with Virtual Space
---

Check Out [AR Agent](https://github.com/NasheethAhmedA/AR-Agent)


## 🎥 Demo Video


https://github.com/user-attachments/assets/396bfe6e-90ba-4514-b6d0-e003dd0cca65



## 🚀 Overview

**AR-Agent** is an experimental project that blends **Augmented Reality**, **AI agents**, and **game engine logic** into one interactive experience.

It uses **Godot Engine** (with custom ARCore integration) to render and animate intelligent agents in the real world.
Meanwhile, an **n8n backend** powers the agent’s **NLP, reasoning, and workflow automation**, turning natural language into intelligent AR actions.

---

## 🧩 Core Features

* 🌍 **Real-World Anchoring:**
  Uses **ARCore Plane Detection** and **Geospatial API** for precise world tracking and location-based agent placement.

* 🧠 **Agentic AI Backend (n8n):**
  Integrates **LLMs** and custom **NLP pipelines** using n8n for reasoning, conversation, and action planning.

* 🎮 **Godot-Powered Logic & Animation:**
  Uses **GDScript** to manage real-time logic, interactions, and animations in an AR environment.

* ⚙️ **Custom ARCore Plugin Build:**
  Built with **C, C++, Java, Kotlin, and Python**, compiled into a native Godot plugin to bridge ARCore with GDScript.

* 📱 **Cross-Compiled Android App:**
  Exported as an **APK** for Android devices — enabling on-device AR interactions powered by AI.

---

## 🏗️ Tech Stack

| Layer              | Technology                               | Purpose                                     |
| ------------------ | ---------------------------------------- | ------------------------------------------- |
| **Game Engine**    | [Godot Engine](https://godotengine.org/) | Rendering, physics, AR handling             |
| **AR Integration** | Google **ARCore SDK**                    | Plane detection, geospatial mapping         |
| **AI Backend**     | [n8n](https://n8n.io/)                   | Agent logic, LLM integration, NLP workflows |
| **Languages**      | GDScript, C, C++, Java, Kotlin, Python   | Engine scripting, native plugin integration |
| **Output**         | Android APK                              | Deployable AR experience                    |
---

## 📦 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/AR-Agent.git
cd AR-Agent
```

### 2️⃣ Setup Backend (n8n)

* Install and run n8n locally or in the cloud
* Import the provided workflow JSON from `/backend/n8n/`
* Configure your LLM / API keys (e.g., OpenAI, Anthropic, etc.)

### 3️⃣ Setup Godot Project

* Open the project in **Godot 4.x**
* Make sure the **ARCore plugin** is properly placed in `/addons/`
* Link the backend API endpoint in your GDScript config file

### 4️⃣ Export to Android

* Follow [Godot’s Android export guide](https://docs.godotengine.org/en/stable/tutorials/export/exporting_for_android.html)
* Test on an ARCore-supported Android device

---

## 🧭 Usage

1. Launch the app on your Android device
2. Move your phone around to detect surfaces
3. Speak or type commands — the AI agent will interpret and respond
4. Watch as the **intelligent AR agent** interacts with your environment

---

## 🌐 Future Roadmap
* [x] Text to Speech (tts) 
* [ ] Voice interaction (speech-to-text)
* [ ] Multi-agent collaboration
* [ ] WebAR / cross-platform support
