![Claude Code Action responding to a comment](https://github.com/user-attachments/assets/1d60c2e9-82ed-4ee5-b749-f9e021c85f4d)

# Claude Code Action for Bun Latest.

This project is forked from [claude-code-action](https://github.com/anthropics/claude-code-action) 

A general-purpose [Claude Code](https://claude.ai/code) action for GitHub PRs and issues that can answer questions and implement code changes. This action listens for a trigger phrase in comments and activates Claude act on the request. It supports multiple authentication methods including Anthropic direct API, Amazon Bedrock, and Google Vertex AI.

## Features

- 🤖 **Interactive Code Assistant**: Claude can answer questions about code, architecture, and programming
- 🔍 **Code Review**: Analyzes PR changes and suggests improvements
- ✨ **Code Implementation**: Can implement simple fixes, refactoring, and even new features
- 💬 **PR/Issue Integration**: Works seamlessly with GitHub comments and PR reviews
- 🛠️ **Flexible Tool Access**: Access to GitHub APIs and file operations (additional tools can be enabled via configuration)
- 📋 **Progress Tracking**: Visual progress indicators with checkboxes that dynamically update as Claude completes tasks
- 🏃 **Runs on Your Infrastructure**: The action executes entirely on your own GitHub runner (Anthropic API calls go to your chosen provider)

## Quickstart

The easiest way to set up this action is through [Claude Code](https://claude.ai/code) in the terminal. Just open `claude` and run `/install-github-app`.

This command will guide you through setting up the GitHub app and required secrets.

**Note**:

- You must be a repository admin to install the GitHub app and add secrets
- This quickstart method is only available for direct Anthropic API users. For AWS Bedrock or Google Vertex AI setup, see [docs/cloud-providers.md](./docs/cloud-providers.md).

## Documentation

- [Setup Guide](./docs/setup.md) - Manual setup, custom GitHub apps, and security best practices
- [Usage Guide](./docs/usage.md) - Basic usage, workflow configuration, and input parameters
- [Custom Automations](./docs/custom-automations.md) - Examples of automated workflows and custom prompts
- [Configuration](./docs/configuration.md) - MCP servers, permissions, environment variables, and advanced settings
- [Experimental Features](./docs/experimental.md) - Execution modes and network restrictions
- [Cloud Providers](./docs/cloud-providers.md) - AWS Bedrock and Google Vertex AI setup
- [Capabilities & Limitations](./docs/capabilities-and-limitations.md) - What Claude can and cannot do
- [Security](./docs/security.md) - Access control, permissions, and commit signing
- [FAQ](./docs/faq.md) - Common questions and troubleshooting

## 📚 FAQ

Having issues or questions? Check out our [Frequently Asked Questions](./docs/faq.md) for solutions to common problems and detailed explanations of Claude's capabilities and limitations.

## License

This project is licensed under the MIT License—see the LICENSE file for details.
