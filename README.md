
# Augy

> A revolutionary AI-powered GUI agent that transforms how you interact with your Mac using natural language commands

[![macOS](https://img.shields.io/badge/macOS-Apple%20Silicon-blue.svg)](https://www.apple.com/mac/)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)]()
[![Version](https://img.shields.io/badge/Version-1.0.0-green.svg)]()

<p align="center">
  <img alt="Augy" width="260" src="augy.icns">
</p>

## ✨ What is Augy?

Augy is an intelligent desktop application that revolutionizes GUI interaction by allowing you to control your Mac using natural language commands. Built on Anthropic's Claude AI model with advanced computer vision capabilities, Augy can understand what you want to accomplish and execute tasks safely within a secure virtual machine environment.

> **Note**: Augy is based on a modified version of agent-tars developed by ByteDance.

## 🎬 Demo Video

[![Augy Demo](https://img.youtube.com/vi/xkv9No3pUU0/0.jpg)](https://www.youtube.com/watch?v=xkv9No3pUU0)

Watch Augy in action! Click the thumbnail above to see how natural language commands translate into powerful GUI automation.

## 🚀 Key Features

### 🧠 **AI-Powered Control**
- **Natural Language Commands**: Simply describe what you want to do in plain English
- **Advanced Computer Vision**: Analyzes application interfaces and UI elements intelligently
- **Context-Aware Execution**: Understands complex workflows and multi-step processes

### 🔒 **Built-in Virtual Machine**
- **Secure Isolation**: All operations run in a safe virtual environment powered by Lume
- **Risk-Free Testing**: Experiment without affecting your main system
- **Privacy Protection**: All processing happens locally on your machine

### 🎯 **Smart Automation**
- **Cross-Application Workflows**: Seamlessly work across different macOS applications
- **Task Planning**: Breaks down complex requests into manageable steps
- **Error Recovery**: Intelligently handles unexpected situations and retries

### ⚡ **Developer-Friendly**
- **MCP (Model Context Protocol) Support**: Extensible through custom tools and integrations
- **Local Processing**: No data leaves your machine
- **Apple Silicon Optimized**: Built specifically for modern Macs

## 🏗️ Architecture & Principles

### Core Components

1. **AI Agent Engine**
   - Powered by Anthropic's Claude with computer use capabilities
   - Advanced prompt engineering for GUI interaction
   - Real-time screen analysis and decision making

2. **Virtual Machine Manager (Lume Integration)**
   - Secure VM provisioning and management
   - Isolated execution environment
   - Resource optimization for smooth performance

3. **Computer Interface Layer**
   - Cross-platform computer control abstraction
   - Mouse, keyboard, and screen interaction
   - Application-specific optimizations

4. **Security & Privacy Framework**
   - Local-first architecture
   - Encrypted communication channels
   - Granular permission controls

### How It Works

1. **Input Processing**: User describes a task in natural language
2. **AI Analysis**: Claude analyzes the request and current screen state
3. **Task Planning**: Breaks down complex tasks into actionable steps
4. **VM Execution**: Executes actions safely within the virtual machine
5. **Feedback Loop**: Provides real-time updates and results



## 📖 Getting Started

### System Requirements

- **Operating System**: macOS (Apple Silicon required)
- **Storage**: 50GB available space for VM images
- **Network**: Internet connection for initial setup

### Installation

1. **Download Augy**: Get the latest release from our secure distribution
2. **Install Application**: Drag Augy.app to your Applications folder
3. **Grant Permissions**: Allow necessary accessibility and screen recording permissions
4. **Setup Virtual Machine**: Augy will guide you through VM configuration

### First Steps

1. **Launch Augy** and complete the initial setup
2. **Configure your AI model** (Claude API key required)
3. **Set up your virtual machine** environment
4. **Try a simple task**: "Open Safari and search for the weather"

### Basic Usage Examples

```bash
# Simple application control
"Open the Calculator app and compute 2+2"

# File management
"Create a new folder called 'Projects' on the Desktop"

# Web browsing
"Go to GitHub and search for React repositories"

# Complex workflows
"Take a screenshot, open Preview, and crop the image to focus on the center"
```

## 🛠️ Configuration

### AI Model Setup

Augy supports multiple AI providers for computer use:

- **Anthropic Claude**
- **Custom endpoints**

### Security Settings

- **Sandbox Mode**: Enable/disable VM isolation
- **Network Access**: Control internet connectivity
- **File System**: Configure shared directories
- **Screen Recording**: Limit capture permissions

## 🔧 Advanced Features

### MCP Server Integration

Augy supports the Model Context Protocol for extended functionality:

```typescript
// Example MCP server configuration
{
  "servers": {
    "filesystem": {
      "command": "mcp-server-filesystem",
      "args": ["/safe-directory"]
    },
    "browser": {
      "command": "mcp-server-browser",
      "args": ["--headless"]
    }
  }
}
```

## 🆘 Support

- **Website**: [https://augy.nickqiao.asia/](https://augy.nickqiao.asia/)
- **Twitter**: [https://x.com/augy_ai](https://x.com/augy_ai)
- **Discord**: [https://discord.gg/jQvCKBTanb](https://discord.gg/jQvCKBTanb)
- **Issue Tracker**: Report bugs and request features
- **Email Support**: Contact our team for assistance

## 🎯 Roadmap

### Upcoming Features
- [ ] manual takeover 
- [ ] scheduled task support

**Made with ❤️ for the future of human-computer interaction**

Transform your workflow today with Augy - where natural language meets powerful automation.
