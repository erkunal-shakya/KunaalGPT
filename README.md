# KunaalGPT

KunaalGPT is a personal, lightweight AI chat interface that brings multiple AI providers and free/limited AI models into one simple ChatGPT-style interface.

The project is built as a frontend-first application using HTML, CSS and JavaScript.

## Features

- ChatGPT-style conversational interface
- Multiple AI providers
- Free / limited model filtering
- Coding-specific model selection
- Model switching
- Responsive desktop and mobile UI
- Collapsible sidebar
- Multiple conversations / new chats
- Copy responses easily
- Copy code blocks
- Code syntax formatting
- Emoji support
- Image upload support where supported by the selected AI provider
- Markdown-style AI responses
- API key configuration
- Local configuration support
- Automatic model loading from supported providers
- Separate coding-focused model selection
- Dark themed interface

## Supported AI Providers

Currently the project can work with providers such as:

- Google Gemini
- Groq
- OpenRouter
- Hugging Face
- Mistral
- Cloudflare Workers AI

Availability of models depends on the provider, account, API limits and current free-tier availability.

> Free does not necessarily mean unlimited. Providers may apply rate limits, quotas or usage restrictions.

## Coding Models

KunaalGPT includes a dedicated **Coding Specific** model category.

This makes it easier to find models intended for:

- PHP
- Magento 2 / Adobe Commerce
- JavaScript
- HTML / CSS
- MySQL
- REST APIs
- GraphQL
- Debugging
- Code generation
- Refactoring
- Technical explanations

## API Keys

KunaalGPT can use API keys from the supported providers.

API keys should be treated as private credentials.

**Never commit your personal API keys to a public GitHub repository.**

For local usage, configure your API keys through the application's settings.

If you use a separate configuration file, make sure it is excluded from Git using `.gitignore`.

Example:

```gitignore
.kunaal-config
*.env
.env
```
## Screen Shorts

