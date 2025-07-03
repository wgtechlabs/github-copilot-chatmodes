# 🎯 Contribute to WG GitHub Copilot Chatmodes

Welcome to the WG GitHub Copilot Chatmodes project! We're excited that you're interested in contributing. This document provides guidelines and instructions to help you get started.

All contributions are welcome and valued, whether it's a new chat mode, documentation improvements, or bug reports. The community looks forward to your contributions! 🎉✌✨

## 📋 Code of Conduct

This project and everyone participating in it is governed by the project's [Code of Conduct](https://github.com/wgtechlabs/github-copilot-chatmodes/blob/main/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

Key points:

- Be respectful and inclusive
- Focus on constructive feedback
- Avoid offensive or harmful language
- Respect others' time and contributions

Please report unacceptable behavior to [opensource@wgtechlabs.com](mailto:opensource@wgtechlabs.com).

## 💖 How to Contribute

There are multiple ways to contribute to this project:

1. **Create new chat modes**: Design and build custom chat modes for specific use cases
2. **Improve existing modes**: Enhance functionality, fix bugs, or improve instructions
3. **Documentation**: Help improve READMEs, examples, and usage instructions
4. **Testing**: Test chat modes in different scenarios and report issues
5. **Ideas**: Suggest new chat mode concepts or improvements

### 🧬 Development

This section is for contributors who want to create or modify chat modes. Please follow these guidelines:

- All pull requests should target the `dev` branch (PRs to `main` will be automatically rejected)
- Follow the template and structure provided in the examples
- Test your chat mode thoroughly before submission

#### 🔧 Development Setup

To get started with development:

1. Fork and clone the repository

   ```bash
   git clone https://github.com/your-username/github-copilot-chatmodes.git
   cd github-copilot-chatmodes
   ```

2. Create new chat mode
   - For creating a new chat mode, use the template in the `template` folder
   - Read the README in the template folder for guidelines

3. Follow the chat mode structure

   ```text
   modes/
     category/
       your-mode-name/
         WG Your Mode Name.chatmode.md
         README.md
   ```

#### 🎯 Development Guidelines

- **Formatting**: Follow the template structure provided in the `template` folder
- **Emojis**: Use appropriate emojis to enhance readability and user experience
- **Documentation**: Include a comprehensive README.md with your chat mode that explains:
  - What the mode does
  - Example prompts
  - Key capabilities
  - Any special instructions for users
- **Naming Convention**: Use the format "WG Mode Name.chatmode.md" for your chat mode files
- **Quality**: Test your chat mode with GitHub Copilot Chat before submitting
- **Consistency**: Follow the style and structure of existing chat modes

#### 🔍 Code Review Process

1. Pre-submission checks:
   - Chat mode follows the template structure
   - README.md is included and follows the standard format
   - File naming conventions are followed
   - Mode functionality is tested with GitHub Copilot Chat

2. Pull Request Requirements:
   - Target the `dev` branch (PRs to `main` will be rejected)
   - Include clear description of changes
   - Explain the purpose and functionality of your chat mode
   - Follow existing patterns and guidelines
   - Update any relevant documentation

## 🏗️ Architecture & Technical Details

### 💠 Chat Mode Structure

Each chat mode must include the following components:

- **Metadata Section**:

  ```yaml
  ---
  description: "Brief description of what your chat mode does"
  tools: ['list', 'of', 'tools', 'needed']
  ---
  ```

- **Header Comment**:

  ```html
  <!--
    * ==================================================================
    * Chat Mode: Your Chat Mode Name
    * Description: Brief description
    * Version: 1.0.0
    * Author: Your Name
    * License: MIT License
    * Recommended Model: Claude Sonnet 4
    * Repository: https://github.com/WGTechLabs/github-copilot-chatmodes
    * ==================================================================
  -->
  ```

- **System Message**: Defines the personality and behavior of the chat mode
- **Core Functionality**: Detailed instructions for the AI to follow
- **README.md**: Documentation for users explaining the purpose and usage

### 🔧 File Structure Requirements

```text
modes/
  category/
    mode-name/
      WG Mode Name.chatmode.md  # The actual chat mode file
      README.md                 # Documentation for users
```

Categories include:

- `quality/` - For code quality focused modes
- `security/` - For security focused modes
- (Add more categories as needed)

## 📖 Documentation

Improvements to documentation are always welcome! This includes:

- README updates
- Chat mode documentation
- Usage examples
- Clarifying existing documentation
- Fixing typos or improving explanations

## 🐞 Reporting Bugs

If you find any issues with a chat mode, please create an issue with:

- Clear description of the problem
- Steps to reproduce
- Expected vs actual behavior
- Environment information:
  - GitHub Copilot Chat version
  - IDE type and version
  - Operating system
- Example conversation that demonstrates the issue (screenshots if applicable)

For urgent issues or security vulnerabilities, please contact us directly at [security@wgtechlabs.com](mailto:security@wgtechlabs.com).

## 💡 Feature Requests

We welcome suggestions for new chat modes! Please create an issue with:

- Clear description of the proposed chat mode
- Use case and benefits
- Any implementation considerations
- Examples of prompts and expected responses

## 📊 Pull Request Process

1. Create a branch from `dev` with a descriptive name (e.g., `add-data-analyst-mode`)
2. Make your changes following the guidelines above
3. Test your changes thoroughly with GitHub Copilot
4. Update documentation as needed
5. Submit a pull request to the `dev` branch
6. Address any feedback from the code review

## ✨ Quick Start

Want to contribute quickly? Here's how to get started in 5 minutes:

1. Fork the repository
2. Copy the template from `template/Chat Mode Template.md`
3. Create a new folder in the appropriate category in `modes/`
4. Create your chat mode file and README following the guidelines
5. Test with GitHub Copilot Chat
6. Submit a PR to the `dev` branch

---

💻 with ❤️ by [Waren Gonzaga](https://warengonzaga.com), [WG Technology Labs](https://wgtechlabs.com), and [Him](https://www.youtube.com/watch?v=HHrxS4diLew&t=44s) 🙏
