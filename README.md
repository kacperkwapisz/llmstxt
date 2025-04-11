# LLMs.txt Collection

> A curated collection of llms.txt files for popular libraries and frameworks, optimized for AI-powered development tools like Cursor.

## Quick Start

```bash
# In Cursor or similar AI tools, use any of these:
/docs https://llmstxt.kapi.dev/magicui/llms.txt        # UI Components
/docs https://llmstxt.kapi.dev/openai-agents/llms.txt   # AI Agents
# ... and more libraries available at llmstxt.kapi.dev
```

## What is this?

This repository hosts a collection of standardized llms.txt files following the [llms.txt specification](https://llmstxt.org). These files are specifically formatted to help Large Language Models (LLMs) better understand and work with various libraries and frameworks.

All files are accessible through our CDN at `llmstxt.kapi.dev/{library}/llms.txt`.

## Usage

### In Cursor

1. Use the `/docs` command with our CDN URL:

```bash
/docs https://llmstxt.kapi.dev/{library}/llms.txt
```

2. Or use the raw GitHub URL:

```bash
/docs https://raw.githubusercontent.com/yourusername/llmstxt/main/{library}/llms.txt
```

### In Other AI Tools

Most AI coding assistants support loading external documentation. You can use these llms.txt files by providing either:

- CDN URL: `https://llmstxt.kapi.dev/{library}/llms.txt`
- Raw GitHub URL: `https://raw.githubusercontent.com/yourusername/llmstxt/main/{library}/llms.txt`

## Available Libraries

| Library       | Description                                       | Status   | URL                                                                                        |
| ------------- | ------------------------------------------------- | -------- | ------------------------------------------------------------------------------------------ |
| Magic UI      | React components for beautiful landing pages      | ✅ Ready | [llmstxt.kapi.dev/magicui/llms.txt](https://llmstxt.kapi.dev/magicui/llms.txt)             |
| OpenAI Agents | Python library for building OpenAI Assistants     | ✅ Ready | [llmstxt.kapi.dev/openai-agents/llms.txt](https://llmstxt.kapi.dev/openai-agents/llms.txt) |
| shadcn/ui     | React components built with Radix UI and Tailwind | 🚧 WIP   | Coming soon                                                                                |
| tRPC          | End-to-end typesafe APIs                          | 🚧 WIP   | Coming soon                                                                                |

Visit [llmstxt.kapi.dev](https://llmstxt.kapi.dev) for the complete list.

## Structure

Each llms.txt file follows a consistent structure:

```markdown
# Library Name

> Brief description of the library

## Installation

Installation instructions...

## Components/API

### Component/Feature Name

Description and usage examples...

## Resources

- Documentation links
- GitHub repository
```

## Contributing

1. Check if the library already has an llms.txt file at [llmstxt.kapi.dev](https://llmstxt.kapi.dev)
2. Follow the [llms.txt specification](https://llmstxt.org)
3. Use the template in `.template/llms.txt`
4. Submit a PR with your addition

## Why llms.txt?

The llms.txt specification provides a standardized way to make documentation LLM-friendly. Benefits include:

- Consistent format across libraries
- Focused, relevant information
- Easy to parse by AI tools
- Reduced context window usage
- Better AI assistance with code

## License

MIT
