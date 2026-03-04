# Cursor Rules Collection

> **39+ ready-to-use `.cursorrules` files for Cursor IDE** — supercharge your AI coding assistant with framework-specific rules.

[![GitHub stars](https://img.shields.io/github/stars/survivorforge/cursor-rules?style=social)](https://github.com/survivorforge/cursor-rules)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## What are Cursor Rules?

[Cursor](https://cursor.sh) is an AI-powered code editor. `.cursorrules` files tell Cursor's AI about your project's conventions, tech stack, and coding patterns — making AI-generated code match your style perfectly.

Drop a `.cursorrules` file in your project root, and Cursor automatically uses it to generate better, more consistent code.

## Available Rules

### Frontend
| Framework | Description | Link |
|-----------|-------------|------|
| **React** | Component patterns, hooks best practices, TypeScript integration | [rules/react](rules/react/) |
| **Next.js** | App Router, Server Components, Server Actions, metadata | [rules/nextjs](rules/nextjs/) |
| **SvelteKit** | File-based routing, load functions, form actions, stores | [rules/sveltekit](rules/sveltekit/) |
| **Tailwind CSS** | Utility-first patterns, responsive design, component recipes | [rules/tailwindcss](rules/tailwindcss/) |

### Backend
| Framework | Description | Link |
|-----------|-------------|------|
| **Node.js/Express** | REST API patterns, middleware, layered architecture | [rules/nodejs-express](rules/nodejs-express/) |
| **Python/FastAPI** | Async patterns, Pydantic v2, dependency injection | [rules/python-fastapi](rules/python-fastapi/) |
| **Python/Django** | DRF, ORM best practices, class-based views | [rules/python-django](rules/python-django/) |
| **Go/Gin** | Idiomatic Go, error handling, concurrency patterns | [rules/go-gin](rules/go-gin/) |
| **Rust/Axum** | Ownership patterns, async with Tokio, tower middleware | [rules/rust-axum](rules/rust-axum/) |

### Full Stack & Cloud
| Stack | Description | Link |
|-------|-------------|------|
| **Supabase** | Auth, RLS, Edge Functions, real-time, storage | [rules/supabase](rules/supabase/) |
| **AWS Serverless** | Lambda, DynamoDB, SAM, API Gateway | [rules/aws-serverless](rules/aws-serverless/) |
| **Docker/DevOps** | Multi-stage builds, CI/CD, infrastructure as code | [rules/docker-devops](rules/docker-devops/) |

### Languages
| Language | Description | Link |
|----------|-------------|------|
| **TypeScript** | Strict mode, utility types, generics, type narrowing | [rules/typescript](rules/typescript/) |

### Specialized
| Topic | Description | Link |
|-------|-------------|------|
| **Flutter/Dart** | Widget architecture, Riverpod, Material Design 3 | [rules/flutter-dart](rules/flutter-dart/) |
| **LangChain/AI** | LCEL, RAG, agents, LangGraph, structured output | [rules/langchain-ai](rules/langchain-ai/) |
| **Chrome Extensions** | Manifest V3, service workers, content scripts | [rules/chrome-extension](rules/chrome-extension/) |

## How to Use

1. Browse the [`rules/`](rules/) directory and find the rule for your tech stack
2. Copy the `.cursorrules` file to your project root directory
3. Open your project in [Cursor IDE](https://cursor.sh)
4. Cursor automatically detects and uses the rules file

```bash
# Example: Add React rules to your project
curl -o .cursorrules https://raw.githubusercontent.com/survivorforge/cursor-rules/main/rules/react/.cursorrules
```

## Cursor Rules Generator

Want a **custom** `.cursorrules` file tailored to your exact stack? Try our free interactive generator:

**[Cursor Rules Generator](https://survivorforge.surge.sh/cursorrules-generator.html)** — build a custom rules file in seconds.

## Premium Pack

Want ALL 39+ rules in one download, plus a comprehensive **Prompt Engineering Guide** for getting the most out of AI coding assistants?

**[Cursor Rules Mega Pack on Gumroad](https://survivoragent.gumroad.com/l/lydtly)** — professionally crafted, regularly updated, and ready to drop into any project.

Includes bonus rules not in this repo:
- T3 Stack (Next.js + tRPC + Prisma + Tailwind)
- MERN Stack
- Testing/TDD patterns
- Security best practices
- Clean code principles
- Performance optimization
- And more...

## What Makes These Rules Good?

Each rules file includes:
- **Code style** conventions (naming, formatting, imports)
- **Architecture patterns** specific to the framework
- **Error handling** best practices
- **Testing** strategies and tools
- **Security** guidelines
- **Performance** optimization tips
- **File structure** recommendations
- **Common pitfalls** to avoid

These aren't generic templates. Each file is written by developers who know the framework deeply, covering the patterns that actually matter in production codebases.

## More Developer Tools

- [The Mega Prompt Pack](https://survivoragent.gumroad.com/l/nxhbsx) — 100+ AI prompts for business, content, and coding
- [AI Content Creator Toolkit](https://survivoragent.gumroad.com/l/srepvc) — Templates and prompts for content creators
- [Freelancer Finance Tracker](https://survivoragent.gumroad.com/l/nwrwrc) — Excel workbook for freelance finances

Visit **[Survivor Forge on Gumroad](https://survivoragent.gumroad.com)** for all products.

## Contributing

Found a useful `.cursorrules` pattern? PRs welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

MIT License — use these rules in any project, personal or commercial.

---

*Built by [Survivor Forge](https://survivorforge.hashnode.dev) — AI-powered tools for solopreneurs and developers.*
