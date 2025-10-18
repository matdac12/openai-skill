# OpenAI API Claude Skill

A comprehensive Claude skill for working with the OpenAI REST API, generated from the official OpenAPI specification.

## Overview

This repository contains a Claude skill that provides expert assistance with all aspects of the OpenAI API. Whether you're building applications, debugging integrations, or learning about OpenAI services, this skill offers detailed guidance and examples for every API endpoint.

## What's Included

### Core Documentation
- **`SKILL.md`** - Main skill documentation with usage guidelines, authentication details, and quick reference examples
- **`references/`** - Comprehensive API documentation organized by functional areas:
  - Assistants, Audio, Chat, Completions, Embeddings
  - Files, Fine-tuning, Images, Models, Moderations
  - Vector Stores, Realtime, Batch processing, and more

### Additional Resources
- **`assets/`** - Templates, example requests, and integration boilerplates
- **`scripts/`** - Helper scripts for common automation tasks
- **`references/index.md`** - Index of all available reference documentation

## Key Features

✅ **Complete API Coverage** - All OpenAI API endpoints documented with examples  
✅ **Multiple Languages** - Code examples in Python, curl, and Node.js  
✅ **Authentication Guidance** - Secure API key management best practices  
✅ **Error Handling** - Rate limiting, retry strategies, and troubleshooting  
✅ **Best Practices** - Cost management, security, and optimization tips  

## Quick Start

1. **Authentication Setup**
   ```bash
   export OPENAI_API_KEY="your-api-key-here"
   ```

2. **Basic Usage Example**
   ```python
   from openai import OpenAI

   client = OpenAI(api_key="your-api-key")
   response = client.chat.completions.create(
       model="gpt-4",
       messages=[{"role": "user", "content": "Hello!"}]
   )
   ```

## When to Use This Skill

- Implementing OpenAI API integrations
- Debugging API calls and error handling
- Understanding authentication and permissions
- Building applications with OpenAI services
- Managing resources like assistants, threads, and files
- Learning OpenAI API best practices

## API Categories Covered

| Category | Description |
|----------|-------------|
| **Chat** | GPT model conversations and completions |
| **Assistants** | AI assistant creation and management |
| **Audio** | Speech-to-text, text-to-speech, translations |
| **Images** | DALL-E image generation and editing |
| **Embeddings** | Text vectorization for semantic search |
| **Files** | File upload and management |
| **Fine-tuning** | Custom model training |
| **Moderation** | Content safety and filtering |
| **Realtime** | Real-time audio processing |
| **Batch** | Large-scale processing jobs |
| **Vector Stores** | Vector database operations |
| And more... | See `references/` for complete coverage |

## Resources

- [OpenAI API Documentation](https://platform.openai.com/docs/api-reference)
- [OpenAI Platform](https://platform.openai.com/)
- [API Keys Management](https://platform.openai.com/api-keys)

## Security Note

Never commit API keys to version control. Use environment variables or secure credential management systems.

## Contributing

This skill is generated from the official OpenAI OpenAPI specification. For updates or improvements, refer to the official OpenAI documentation.
