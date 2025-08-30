# Dobby Research Agent - Enhanced Edition

A sophisticated web-based research assistant that helps academics and researchers quickly gather, organize, and analyze information across multiple domains.

![Dobby Research Agent](https://img.shields.io/badge/Version-Enhanced%20Edition-blue) ![License](https://img.shields.io/badge/License-MIT-green) ![AI-Powered](https://img.shields.io/badge/AI-Powered-orange)

## 🌟 Features

- **Multi-Section Research**: Automatically generates comprehensive research across 8 domains:
  - 📚 Academic Papers
  - 📖 Executive Summary
  - 🔬 Research Methods
  - 🚀 Real-World Applications
  - 📑 Formatted References
  - 🔗 Related Topics
  - 📈 Current Trends
  - 💾 Available Datasets

- **Advanced Customization**:
  - Adjust academic level (General to Expert/PhD)
  - Set time range filters
  - Control number of papers to include
  - Focus on specific research aspects

- **Productivity Tools**:
  - Research note-taking system
  - Search history with quick access
  - Multiple export formats (Text, Markdown, PDF, BibTeX)
  - Section comparison feature
  - Citation generator

- **User Experience**:
  - Clean, responsive interface
  - Search suggestions
  - Keyboard shortcuts
  - Progress indicators
  - Mobile-friendly design

## 🚀 Quick Start

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Access to an AI API endpoint (configured in the code)

### Basic Usage

1. Open `index.html` in your web browser
2. Enter your research topic in the search box
3. (Optional) Click "Advanced" to customize search parameters
4. Press Enter or click "Search" to begin
5. Review the generated research across multiple sections
6. Use the action bar to export, compare, or save your research

### API Configuration

The application requires access to an AI API. Update the configuration in the JavaScript:

```javascript
const PROXY_URL = '/api/proxy';  // Your API endpoint
const MODEL = "accounts/sentientfoundation/models/dobby-unhinged-llama-3-3-70b-new";  // Your model
