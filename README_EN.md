📱 AUAK AGENTY
==============

**An AI-powered Mobile Agent for Autonomous App Control**

* * *

🌍 English Version
------------------

<p align="center">
  <img src="app/src/main/res/drawable/splash_icon.png" alt="Main Interface" width="200"/>
</p>

<p align="center">
  🌍 <a href="README_EN.md">English</a> | <a href="README.md">中文</a>
</p>

###  🚀 Project Overview

**AUAK AGENTY** is an AI-driven mobile agent system powered by a Firebase cloud backend.  
It allows **vision-based or LLM models** to autonomously operate Android apps by calling low-level **window and UI control functions** on the device.

For example, the AI can:

* Open a video app

* Search for a keyword

* Click buttons and input text

* Navigate through UI like a human

* Log every step in real-time using a step progress panel

This enables true **AI → Phone → Action** automation.

* * *

### 🧠 How It Works

1. The user sends a task (e.g., _“Open YouTube and search AI news”_).

2. The LLM or Vision model analyzes the UI.

3. The agent calls **window-level interaction APIs** to simulate taps, scrolls, and inputs.

4. Each action is recorded in a **real-time Step Timeline**.

5. The agent continues until the task is completed.

* * *

### 🔐 Permissions

This app uses **Shizuku** to obtain elevated permissions for system-level control.

> Shizuku is required to allow AUAK AGENTY to control other apps.

* * *

### ⚙️ Key Features

* 🔥 Firebase cloud backend

* 👁️ Vision / LLM model integration

* 📲 Autonomous app control

* 🧭 Real-time step execution panel

* 🔑 Custom AI API proxy & key configuration

* 🛡️ Secure permission handling via Shizuku

* * *

* * *

### 🛠️ Tech Stack

* Android (Kotlin)

* Firebase

* Window / Accessibility APIs

* Shizuku

* Custom LLM API Proxy
