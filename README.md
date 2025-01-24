
# Improved Prompt Sail with Java Backend

This is an improved version of the original [Prompt Sail](https://github.com/PromptSail/prompt_sail) project, featuring a robust Java backend implementation. While the original project is no longer actively maintained, this version will receive regular updates and improvements.

## Key Improvements

- Modern Java backend implementation using Spring Boot
- Enhanced performance and scalability
- Better maintainability and extensibility
- Improved API documentation
- More comprehensive test coverage

## Why This Fork?

The original Prompt Sail project, while innovative, has seen reduced maintenance activity. This fork aims to:
- Continue development with regular updates
- Address open issues and feature requests
- Provide better long-term support
- Improve overall code quality and architecture

We remain grateful to the original authors for their work and hope to build upon their foundation to create an even better tool for the community.

---

# Prompt Sail

LLM's proxy for prompt and response governance, monitoring, and analysis. 📊🔍

> ⚠️ **Prompt Sail is currently in Development**: Expect breaking changes and bugs! Feedback and contributions are welcome. Please see the [Contributing Guide](/sabelosimelane/prompt_sail/blob/main/CONTRIBUTING.md) for more information.

## What is Prompt Sail?

Prompt Sail is a proxy for Large Language Models (LLMs) API's such as OpenAI GPT models, Azure OpenAI, Anthropic Clude etc. that allows you to record prompts and responses, analyze costs, generation speed, compare and track trends and changes across various models and projects over time.

To learn more about Prompt Sail's features and capabilities, see:

- [Documentation](https://promptsail.github.io/prompt_sail/) 📖
- [Examples](https://github.com/PromptSail/prompt_sail/tree/main/examples) 💻
- [API Reference](https://try-promptsail.azurewebsites.net/api/docs)

## Getting Started 🚀

The easiest way is to test our demo at **<https://try-promptsail.azurewebsites.net/>** (every new deployment erases the database)

Check out the documentation [how to run PromptSail locally via docker.](https://promptsail.com/docs/quick-start-guide/)

### Run Prompt Sail locally via Docker Compose 🐳

To try out Start Prompt on your own machine, we recommend using docker-compose.

### Requirements 📋

- installed docker and docker-compose on your machine
- git clone repository and navigate to main directory

### Run docker images 🏗️

Build and run the docker image:

    docker-compose -f docker-compose-build.yml up --build

Pull and run the Docker images from GHCR:

    docker-compose -f docker-compose.yml up

### Create a project 📝

Navigate to <http://localhost:80> and add you AI provider of choice.

### Modify your code to use Prompt Sail proxy 👨‍💻

To use Prompt Sail with `openai` Python library, you need to set `OPENAI_API_BASE` environment variable, or modify `openai.api_base` parameter to point to your Prompt Sail project.

## Contact 📞

- Bugs & requests: [file a GitHub ticket](https://github.com/PromptSail/prompt_sail/issues/new/choose) 🐞
- For business inquiries: email <contact@promptsail.com>. 📧
- Our website: <https://promptsail.com> 🌐

## License 📜

Prompt Sail is free and open source, under the [MIT license](/sabelosimelane/prompt_sail/blob/main/LICENSE).

## About

Open Source LLM proxy that transparently captures and logs all interactions with LLM API

[promptsail.com/](http://promptsail.com/)
