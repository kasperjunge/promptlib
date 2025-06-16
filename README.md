# promptlib

A curated collection of prompts, templates, and rules for AI-powered development workflows. This library provides reusable prompt templates to improve consistency and effectiveness in AI interactions for software development tasks.

## 📁 Project Structure

```
promptlib/
├── prompts/          # Reusable prompt templates
├── context/          # Context files for specific domains
├── rules/            # Development rules and guidelines
└── README.md         # This file
```

## 🎯 Purpose

promptlib serves as a centralized repository for:
- **Prompt Templates**: Ready-to-use prompts for common development scenarios
- **Context Files**: Domain-specific context to enhance AI understanding
- **Development Rules**: Best practices and guidelines for consistent workflows

## 📝 Available Prompts

### Communication & Alignment
- **`alignment.md`**: Summarize and confirm understanding of conversation progress
- **`document_alignment.md`**: Document agreed-upon decisions and requirements

### Development
- **`api_design.md`**: Initiate API design sessions and discussions

## 🛠 Development Rules

### Python Environment Management
- Uses `uv` for Python environment management
- Install environment: `uv sync`
- Add packages: `uv add <package-name>`
- Run scripts: `uv run script_name.py`
- Run commands: `uv run <command>`

## 🚀 Usage

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd promptlib
   ```

2. **Browse available prompts**:
   - Navigate to the `prompts/` directory
   - Select appropriate templates for your use case

3. **Customize templates**:
   - Replace placeholder variables (e.g., `{{ file_name }}`)
   - Adapt prompts to your specific context

4. **Apply context**:
   - Use files from `context/` directory for domain-specific guidance
   - Follow rules from `rules/` directory for consistent development practices

## 🤝 Contributing

To add new prompts or improve existing ones:
1. Create new `.md` files in the appropriate directory
2. Use clear, descriptive names
3. Include placeholder variables where appropriate
4. Document the prompt's purpose and usage

## 📄 License

[Add your license information here]

## 🔗 Related Resources

- [Add links to related documentation or tools]