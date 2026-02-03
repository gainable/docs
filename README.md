# Gainable Documentation

This repository contains the documentation for [Gainable](https://app.gainable.ai), the AI-powered no-code app builder.

## Documentation Structure

```
docs/
├── introduction.mdx          # Platform overview
├── quickstart.mdx            # First app in 5 minutes
│
├── concepts/
│   ├── how-it-works.mdx      # How Gainable builds apps
│   ├── agents.mdx            # AI agent system
│   └── skills.mdx            # Built-in capabilities
│
├── prompting/
│   ├── overview.mdx          # Prompt strategy fundamentals
│   ├── best-practices.mdx    # Writing effective prompts
│   ├── examples.mdx          # Real prompt examples
│   └── common-patterns.mdx   # Templates for common apps
│
├── building/
│   ├── data-models.mdx       # Data and schemas
│   ├── views.mdx             # UI and pages
│   ├── real-time.mdx         # Live updates
│   └── collaboration.mdx     # Chat, files, comments
│
├── skills/
│   ├── chartjs.mdx           # Data visualization
│   ├── kanban.mdx            # Drag-drop boards
│   ├── weavy.mdx             # Collaboration features
│   └── design.mdx            # Themes and styling
│
└── reference/
    ├── api.mdx               # Generated app APIs
    └── troubleshooting.mdx   # Common issues
```

## Local Development

1. Install the Mintlify CLI:
   ```bash
   npm i -g mintlify
   ```

2. Run the local development server:
   ```bash
   mintlify dev
   ```

3. Open `http://localhost:3000` to preview the docs.

## Deployment

Documentation is automatically deployed when changes are pushed to the main branch.

## Contributing

1. Make changes to the relevant `.mdx` files
2. Preview locally with `mintlify dev`
3. Create a pull request

## Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [Gainable App](https://app.gainable.ai)
