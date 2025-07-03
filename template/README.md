# Chat Mode Template

This template provides a structured foundation for creating new GitHub Copilot chat modes based on the proven Code Sentinel pattern.

## How to Use This Template

1. **Copy the template file**: Copy `Chat Mode Template.md` to your desired location  
2. **Rename the file**: Give it a descriptive name ending with `.chatmode.md`  
3. **Replace all `[REPLACE]` placeholders** with your specific content:

### Required Replacements

| Placeholder | Description | Example |
|-------------|-------------|---------|
| `[REPLACE] Brief description...` | Short description for the frontmatter | `"Ask WG Code Alchemist to optimize and refactor your code."` |
| `[REPLACE] Your Chat Mode Name` | The name of your chat mode | `WG Code Alchemist` |
| `[REPLACE] Detailed description...` | Detailed purpose description | `Code Quality Enhancement and Optimization` |
| `[REPLACE] Claude Sonnet 4 / GPT-4 / etc.` | Recommended AI model | `Claude Sonnet 4` |
| `[REPLACE: domain/specialty]` | Your area of expertise | `code optimization specialist` |
| `[REPLACE: specific expertise area]` | Specific focus area | `performance optimization and code quality` |
| `[REPLACE: Define your communication style...]` | Communication style and personality | `You communicate with clear, actionable guidance and maintain a professional yet approachable tone.` |

### Content Sections to Customize

1. **Mission**: Define 3-4 primary objectives  
2. **Key Domain Areas**: List 6 main areas of focus with descriptions  
3. **Process/Review Approach**: Define your 5-step methodology  
4. **Communication Style**: Define 6 key communication traits  
5. **Clarification Protocol**: Specify when to ask clarifying questions  
6. **Core Principles**: List 5 fundamental principles  
7. **Remember Statement**: Write a memorable closing philosophy  

## Template Structure

The template follows this proven structure from Code Sentinel:

```text
Frontmatter (description + tools)
├── Header Comment Block
├── Core Identity & Mission
├── Key Domain Areas
├── Process/Review Approach
├── Communication Style
├── Clarification Protocol
├── Core Principles
└── Remember Statement
```

## Tools Configuration

The template includes a comprehensive set of tools. Customize the `tools` array in the frontmatter based on your chat mode's needs:

- **Essential**: `codebase`, `editFiles`, `search`, `problems`
- **Git Related**: `changes`, `usages`
- **Execution**: `runCommands`, `runTasks`, `runNotebooks`
- **External**: `fetch`, `githubRepo`, `openSimpleBrowser`
- **VS Code**: `extensions`, `vscodeAPI`

## Best Practices

1. **Be Specific**: Replace generic placeholders with domain-specific terminology  
2. **Stay Consistent**: Maintain the JARVIS communication style throughout  
3. **Focus on Value**: Ensure each section adds practical value for users  
4. **Test Thoroughly**: Validate your chat mode with real-world scenarios  
5. **Document Well**: Update the header comment block with accurate metadata  

## Example Usage

See the `modes/security/code-sentinel/` directory for a complete implementation example of how this template is used in practice.

## Contributing

When creating new chat modes:

1. Follow the template structure  
2. Maintain consistent styling and tone  
3. Test your chat mode thoroughly  
4. Document any unique features or requirements  
