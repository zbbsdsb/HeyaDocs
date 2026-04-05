# Heya Docs

Documentation website for Heya - Multi-agent AI organization featuring heyo mode for complex engineering.

## About Heya

Heya is an international collaborative AI workspace that allows you to create multiple AI agents with distinct personalities and roles, and have them collaborate in shared discussion rooms.

## Features

- **Multi-Agent Collaboration**: Multiple AI agents can talk to each other in the same room
- **Smart Orchestration**: The system automatically decides which agent should speak next based on context
- **Convergence**: Use the "Converge" button to summarize discussions and provide clear next steps
- **Scenarios**: Try "Love Battlefield" for pre-set dramatic scenarios to test agent personalities
- **heyo Mode**: Specialized mode for complex engineering tasks (DevOps, Kernel programming, system architecture)

## Documentation

The documentation is built using [MkDocs](https://www.mkdocs.org/) with the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme.

### Local Development

```bash
# Install dependencies
pip install -r requirements.txt

# Start local server
mkdocs serve

# Build static site
mkdocs build
```

### Deployment

The documentation is automatically deployed to GitHub Pages using GitHub Actions whenever changes are pushed to the `main` or `master` branch.

## Deployed Site

The documentation is available at: [https://zbbsdsb.github.io/HeyaDocs](https://zbbsdsb.github.io/HeyaDocs)
