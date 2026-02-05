# Contributing to MemberJunction Cowork Plugins

Thank you for your interest in contributing! This project aims to provide free, high-quality AI tools for associations and their communities.

## Ways to Contribute

### 1. Domain Expertise

Are you an association professional? Your expertise is invaluable:

- **Review existing skills** for accuracy and completeness
- **Suggest new commands** for common tasks you perform
- **Enhance documentation** with real-world examples
- **Share best practices** from your experience

### 2. Technical Contributions

Developers can help improve the plugins:

- **Add new commands** following the existing patterns
- **Create new skills** encoding domain knowledge
- **Improve MCP integrations** for better functionality
- **Fix bugs** and improve documentation

### 3. Testing and Feedback

Help us improve by:

- **Testing plugins** in real-world scenarios
- **Reporting issues** you encounter
- **Suggesting improvements** based on your experience
- **Sharing success stories** to help others

## Plugin Structure

Each plugin follows this structure:

```
plugin-name/
├── .claude-plugin/
│   └── plugin.json      # Plugin metadata
├── .mcp.json            # MCP server configuration
├── commands/            # Slash commands
│   └── command-name.md
├── skills/              # Domain knowledge
│   └── skill-name.md
└── README.md            # Plugin documentation
```

## Command Format

Commands are markdown files with this structure:

```markdown
# /command-name

Brief description of what the command does.

## Usage

\`\`\`
/command-name [arguments] [options]
\`\`\`

## Arguments

- `argument`: Description

## What This Command Does

Detailed explanation of the command's functionality...

## Example

\`\`\`
/command-name example-argument --option=value
\`\`\`
```

## Skill Format

Skills are comprehensive markdown documents encoding domain expertise:

```markdown
# Skill Name

This skill provides knowledge about [topic].

## Section 1

Content...

## Section 2

Content...
```

## Submission Process

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/new-command`)
3. **Make your changes** following the patterns above
4. **Test your changes** in Claude Cowork
5. **Submit a pull request** with a clear description

## Code of Conduct

- Be respectful and inclusive
- Focus on constructive feedback
- Help others learn and grow
- Maintain professional standards

## Questions?

- Open an [issue](https://github.com/MemberJunction/co-work-plugins/issues) for bugs or feature requests
- Start a [discussion](https://github.com/MemberJunction/co-work-plugins/discussions) for questions or ideas

Thank you for helping make association management tools accessible to everyone!
