# WG GitHub Copilot Chat Modes 🤖 [![made by](https://img.shields.io/badge/made%20by-WG%20Tech%20Labs-0060a0.svg?logo=github&longCache=true&labelColor=181717&style=flat-square)](https://github.com/wgtechlabs)

[![sponsors](https://img.shields.io/badge/sponsor-%E2%9D%A4-%23db61a2.svg?&logo=github&logoColor=white&labelColor=181717&style=flat-square)](https://github.com/sponsors/wgtechlabs) [![star](https://img.shields.io/github/stars/wgtechlabs/github-copilot-chatmodes.svg?&logo=github&labelColor=181717&color=yellow&style=flat-square)](https://github.com/wgtechlabs/github-copilot-chatmodes/stargazers) [![license](https://img.shields.io/github/license/wgtechlabs/github-copilot-chatmodes.svg?&logo=github&labelColor=181717&style=flat-square)](https://github.com/wgtechlabs/github-copilot-chatmodes/blob/main/LICENSE)

**WG Enhanced GitHub Copilot Chat Modes** – Elevate your development workflow with WG Technology Labs chat modes that transform GitHub Copilot into a suite of domain-specific experts. Each WG Chat Mode delivers specialized, context-aware assistance for code quality, security reviews, and more—tailored to the unique needs of modern software teams.

Perfect for developers who want expert-level, WG Technology Labs-powered AI guidance directly within their development environment.

## 🤗 Special Thanks

### 🤝 Partner Organizations

These outstanding organizations partner with us to support our open-source work:

<!-- markdownlint-disable MD033 -->
| <div align="center">💎 Platinum Sponsor</div> |
|:-------------------------------------------:|
| <a href="https://unthread.com"><img src="https://raw.githubusercontent.com/wgtechlabs/unthread-discord-bot/main/.github/assets/sponsors/platinum_unthread.png" width="250" alt="Unthread"></a> |
| <div align="center"><a href="https://unthread.com" target="_blank"><b>Unthread</b></a><br/>Streamlined support ticketing for modern teams.</div> |
<!-- markdownlint-enable MD033 -->

## 💸 Sponsored Ads

Open source development is resource-intensive. These **sponsored ads help keep Log Engine free and actively maintained** while connecting you with tools and services that support open-source development.

[![sponsored ads](https://gitads.dev/v1/ad-serve?source=wgtechlabs/github-copilot-chatmodes@github)](https://gitads.dev/v1/ad-track?source=wgtechlabs/github-copilot-chatmodes@github)

## 🤔 What Are Chat Modes?

GitHub Copilot Chat Modes transform your AI assistant into domain specialists by providing:

### **🎯 Specialized Expertise**

- **Code Quality Focus**: Apply Clean Code principles and SOLID design patterns
- **Security-First Reviews**: Identify vulnerabilities with targeted secure coding practices
- **Domain-Specific Knowledge**: Receive advice tailored to specific development disciplines
- **Consistent Methodologies**: Follow structured approaches to development challenges

### **⚡ Enhanced Productivity**

- **Contextual Responses**: Get answers specific to your development scenario
- **Best Practice Guidance**: Receive industry-standard recommendations automatically
- **Reduced Context Switching**: Access expert-level assistance within your development environment
- **Scalable Team Knowledge**: Share consistent expertise across your development team

## ✨ Available Chat Modes

| Mode | Focus | Best For | Key Features | Path |
|------|-------|----------|-------------|------|
| [**WG Code Alchemist**](modes/quality/code-alchemist/WG%20Code%20Alchemist.chatmode.md) | Code quality, Clean Code, SOLID | Code reviews, refactoring | Function optimization, naming conventions, design patterns | `modes/quality/code-alchemist/` |
| [**WG Code Sentinel**](modes/security/code-sentinel/WG%20Code%20Sentinel.chatmode.md) | Security vulnerabilities, secure coding | Security audits, compliance checks | Input validation, authentication, API security, risk assessment | `modes/security/code-sentinel/` |

## 🚀 Quick Start

### **🎯 Using Pre-Built Chat Modes**

1. **Choose a Chat Mode**
   - See the [Available Chat Modes](#-available-chat-modes) table below
   - Download the `.chatmode.md` file for your desired mode

2. **Install in Your Workspace**
   - Create a `.github/chatmodes/` folder in your VS Code workspace
   - Copy the downloaded `.chatmode.md` file into this folder
   - For global access across all workspaces, place it in your VS Code user profile instead

3. **Start Using**
   - Open the Chat view in VS Code (Ctrl+Alt+I)
   - Select your installed mode from the chat mode dropdown
   - Begin getting specialized assistance based on the mode's expertise

## ✨ Key Features

- **🎯 Specialized Expertise** - Domain-specific knowledge for different development needs
- **📋 Structured Methodology** - Consistent approaches to development challenges
- **🧠 Intelligent Communication** - Clear guidance with practical advice
- **⚡ Easy Integration** - Simple copy-paste setup with GitHub Copilot
- **🔄 Adaptive Assistance** - Clarification protocols for accurate understanding
- **📚 Educational Value** - Learn best practices while receiving guidance
- **🛠️ Extensible System** - Create your own specialized chat modes

## 🛠️ Creating Custom Chat Modes

Create your own specialized chat mode using our template system or VS Code commands:

### **📋 Create a Chat Mode**

**Using Our Template:**

1. **Copy the Template**

   ```bash
   cp template/Chat\ Mode\ Template.md modes/your-category/your-mode/Your\ Mode.chatmode.md
   ```

2. **Customize Content**
   - Replace all `[REPLACE]` placeholders with your specific content
   - Define your mission, expertise areas and communication style
   - Establish your methodology and core principles

**Using VS Code Commands:**

1. Open Command Palette (Ctrl+Shift+P)
2. Run `Chat: New Mode File` command
3. Choose workspace or user profile location
4. Enter a name and customize the generated file

To manage existing modes, use `Chat: Configure Chat Modes` command.

### **📋 Chat Mode File Structure**

Each chat mode file (`.chatmode.md`) consists of:

```text
---
description: Brief description of the chat mode's purpose
tools: ['codebase', 'search', 'terminal', ...etc]
---

# Chat Mode Instructions

Your detailed instructions and guidelines for how the AI should behave in this mode.
Define the focus areas, approach, and any specific behaviors desired.
```

The description appears in the chat mode dropdown, and the tools list defines available capabilities.

### **🎨 Template Categories**

Organize by category for better discoverability:

- **Quality**: Code quality, refactoring, best practices
- **Security**: Security reviews, vulnerability assessment
- **Performance**: Optimization, profiling, scalability
- **Architecture**: System design, patterns, documentation
- **Testing**: Test strategies, automation, quality assurance

## 💬 Community Discussions

Connect with other users in our GitHub Discussions:

- 📣 **[Announcements](https://github.com/wgtechlabs/github-copilot-chatmodes/discussions/categories/announcements)**: Official updates
- 📸 **[Showcase](https://github.com/wgtechlabs/github-copilot-chatmodes/discussions/categories/showcase)**: Share your implementations
- 💖 **[Wall of Love](https://github.com/wgtechlabs/github-copilot-chatmodes/discussions/categories/wall-of-love)**: User testimonials
- 🛟 **[Help & Support](https://github.com/wgtechlabs/github-copilot-chatmodes/discussions/categories/help-support)**: Community assistance
- 🧠 **[Ideas](https://github.com/wgtechlabs/github-copilot-chatmodes/discussions/categories/ideas)**: Feature suggestions

## 🛟 Help & Support

- **Community Support**: Check the [Help & Support](https://github.com/wgtechlabs/github-copilot-chatmodes/discussions/categories/help-support) discussion category
- **Ask a Question**: [Create a new discussion](https://github.com/wgtechlabs/github-copilot-chatmodes/discussions/new?category=help-support) for specific issues
- **Report Issues**: [Create a new issue](https://github.com/wgtechlabs/github-copilot-chatmodes/issues/new/choose) for bugs or improvements
- **Security Concerns**: Follow our [security policy](./SECURITY.md) for responsible disclosure

Your contributions to improving this project are greatly appreciated! 🙏✨

## 🎯 Contributing

Contributions are welcome! Please submit your pull request to the `dev` branch for review.

For complete development documentation, see our [Contributing Guide](./CONTRIBUTING.md).

### **Contributing Guidelines**

- **New Chat Modes**: Use the template system for consistency
- **Documentation**: Update README when adding new modes or features
- **Testing**: Verify with real development scenarios
- **Quality Standards**: Follow established patterns and practices

## 💖 Sponsors

Like this project? **Leave a star**! ⭐

Support options:

- [Become a sponsor](https://github.com/sponsors/wgtechlabs) for perks 💖
- [Buy me a coffee](https://buymeacoffee.com/wgtechlabs) ☕
- Share with other developers who could benefit from these chat modes

## ⭐ GitHub Star Nomination

Found this project helpful? Consider nominating **[@warengonzaga](https://github.com/warengonzaga)** for the [GitHub Star program](https://stars.github.com/nominate/)!

## 📋 Code of Conduct & License

This project follows a [Code of Conduct](./CODE_OF_CONDUCT.md) to ensure a welcoming environment for all contributors.

Licensed under the [MIT License](LICENSE), allowing free use with attribution.

## 📝 Author

Created by **[Waren Gonzaga](https://github.com/warengonzaga)** under [WG Technology Labs](https://github.com/wgtechlabs), with help from our [contributors](https://github.com/wgtechlabs/github-copilot-chatmodes/graphs/contributors).

[![contributors](https://contrib.rocks/image?repo=wgtechlabs/github-copilot-chatmodes)](https://github.com/wgtechlabs/github-copilot-chatmodes/graphs/contributors)

---

💻 with ❤️ by [Waren Gonzaga](https://warengonzaga.com) under [WG Technology Labs](https://wgtechlabs.com), and [Him](https://www.youtube.com/watch?v=HHrxS4diLew&t=44s) 🙏

<!-- GitAds-Verify: 4PUZX9T5WXZLXEJ7FAP8M39IKW64GHRM -->
