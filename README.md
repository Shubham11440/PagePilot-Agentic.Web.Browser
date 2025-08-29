
# 🌐 PagePilot

PagePilot is an open-source AI web automation tool that runs in your browser. A free alternative to OpenAI Operator with flexible LLM options and multi-agent system.

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)]()
[![Node.js](https://img.shields.io/badge/Node.js-v22.12.0+-green.svg)](https://nodejs.org/)
[![pnpm](https://img.shields.io/badge/pnpm-v9.15.1+-blue.svg)](https://pnpm.io/)
[![GitHub Stars](https://img.shields.io/github/stars/Shubham11440/PagePilot-Agentic.Web.Browser.svg)](https://github.com/Shubham11440/PagePilot-Agentic.Web.Browser/stargazers)

## 🔥 Why PagePilot?

Looking for a powerful AI web agent without the $200/month price tag of OpenAI Operator? **PagePilot**, as a Chrome extension, delivers premium web automation capabilities while keeping you in complete control:

- **💰 100% Free** - No subscription fees or hidden costs. Just install and use your own API keys.
- **🔒 Privacy-Focused** - Everything runs in your local browser. Your credentials stay with you, never shared with any cloud service.
- **⚡ Flexible LLM Options** - Connect to your preferred LLM providers with freedom to choose different models for different agents.
- **🔓 Fully Open Source** - Complete transparency in how your browser is automated. No black boxes or hidden processes.


## 📊 Key Features

- **Multi-agent System**: Specialized AI agents collaborate to accomplish complex web workflows
- **Interactive Side Panel**: Intuitive chat interface with real-time status updates
- **Task Automation**: Seamlessly automate repetitive web automation tasks across websites
- **Follow-up Questions**: Ask contextual follow-up questions about completed tasks
- **Conversation History**: Easily access and manage your AI agent interaction history
- **Multiple LLM Support**: Connect your preferred LLM providers and assign different models to different agents


## 🔧 Installation & Setup

### Option 1: Download Pre-built Extension (Recommended)

1. **Download**
   - Go to the [Releases page](https://github.com/Shubham11440/PagePilot-Agentic.Web.Browser/releases)
   - Download the latest `PagePilot.zip` file

2. **Install**
   - Unzip `PagePilot.zip`
   - Open `chrome://extensions/` in Chrome
   - Enable `Developer mode` (top right toggle)
   - Click `Load unpacked` (top left button)
   - Select the unzipped `PagePilot` folder

3. **Configure Agent Models**
   - Click the PagePilot icon in your Chrome toolbar
   - Click the `Settings` icon (top right)
   - Add your LLM API keys (OpenAI, Claude, etc.)
   - Choose which model to use for different agents (Navigator, Planner, Validator)

### Option 2: Build from Source

If you prefer to build PagePilot from source:

1. **Prerequisites**
   - [Node.js](https://nodejs.org/) (v22.12.0 or higher)
   - [pnpm](https://pnpm.io/installation) (v9.15.1 or higher)

2. **Clone & Setup**
   ```bash
   git clone https://github.com/Shubham11440/PagePilot-Agentic.Web.Browser.git
   cd PagePilot-Agentic.Web.Browser
   pnpm install
   ```

3. **Build the Extension**
   ```bash
   pnpm build
   ```

4. **Load into Chrome**
   - The built extension will be in the `dist/` directory
   - Follow the installation steps above to load the extension from the `dist/` folder

5. **Development Mode** (Optional)
   ```bash
   pnpm dev
   ```
   This starts the development server with hot reload for making changes.

## 🤖 Choosing Your Models

PagePilot allows you to configure different LLM models for each agent to balance performance and cost. Here are recommended configurations:

### Better Performance
- **Planner & Validator**: Claude 3.7 Sonnet
  - Better reasoning and planning capabilities
  - More reliable task validation
- **Navigator**: Claude 3.5 Haiku
  - Efficient for web navigation tasks
  - Good balance of performance and cost

### Cost-Effective Configuration
- **Planner & Validator**: Claude Haiku or GPT-4o
  - Reasonable performance at lower cost
  - May require more iterations for complex tasks
- **Navigator**: Gemini 2.0 Flash or GPT-4o-mini
  - Lightweight and cost-efficient
  - Suitable for basic navigation tasks

### Local Models
- **Setup Options**:
  - Use Ollama or other custom OpenAI-compatible providers to run models locally
  - Zero API costs and complete privacy with no data leaving your machine

- **Recommended Models**:
  - **Qwen 2.5 Coder 14B**
  - **Mistral Small 24B**

- **Prompt Engineering**:
  - Local models require more specific and cleaner prompts
  - Avoid high-level, ambiguous commands
  - Break complex tasks into clear, detailed steps
  - Provide explicit context and constraints

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Make your changes** and test thoroughly
4. **Commit your changes**: `git commit -m 'Add amazing feature'`
5. **Push to the branch**: `git push origin feature/amazing-feature`
6. **Open a Pull Request**

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

## 📝 Changelog

See [Releases](https://github.com/Shubham11440/PagePilot-Agentic.Web.Browser/releases) for detailed changelog.

## 🐛 Issues & Support

- **Bug Reports**: [Create an issue](https://github.com/Shubham11440/PagePilot-Agentic.Web.Browser/issues)
- **Feature Requests**: [Request a feature](https://github.com/Shubham11440/PagePilot-Agentic.Web.Browser/issues)
- **Discussions**: [Join the discussion](https://github.com/Shubham11440/PagePilot-Agentic.Web.Browser/discussions)

## ⭐ Show Your Support

If you find PagePilot helpful, please consider:
- Giving it a ⭐ on GitHub
- Sharing it with others who might benefit
- Contributing to the project

---

**Made with ❤️ by the PagePilot community**

