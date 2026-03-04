# Contributing to Cursor Rules

We welcome contributions! Whether you want to improve existing rules or add rules for a new framework, here's how.

## Adding a New Rule

1. **Fork** this repository
2. **Create a new directory** under `rules/` with your framework name (lowercase, hyphenated):
   ```
   rules/your-framework/
   ```
3. **Add your `.cursorrules` file** inside the directory
4. **Add a `README.md`** in the directory explaining:
   - What framework/tool the rules cover
   - Key conventions included
   - Any prerequisites or companion tools
5. **Update the main `README.md`** to include your new rule in the appropriate category table
6. **Submit a Pull Request** with a clear description of the rules added

## Rule Quality Guidelines

A good `.cursorrules` file should:

- **Be specific** to a framework or language — not generic coding advice
- **Cover real patterns** that developers actually use in production
- **Include sections** for: code style, architecture, error handling, testing, security, and performance
- **Use concrete examples** where they clarify a pattern
- **Be opinionated** — the point is to give Cursor clear guidance, not options
- **Stay current** — reference the latest stable version of the framework
- **Be well-organized** with clear headers and consistent formatting

## Improving Existing Rules

Found an error, outdated pattern, or missing best practice? Open a PR with:

- A clear description of what changed and why
- Reference to official documentation or widely-accepted patterns
- Tested with Cursor IDE to verify the rules produce better output

## File Structure Convention

```
rules/
  your-framework/
    .cursorrules     # The actual rules file (required)
    README.md        # Brief description and usage notes (recommended)
```

## Code of Conduct

Be respectful, constructive, and focused on helping developers write better code. We're all here to make AI-assisted coding better for everyone.

## Questions?

Open an issue if you have questions about contributing or want to discuss a new rule before writing it.
