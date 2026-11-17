# AutoGen HR Assistant Agent

A single AutoGen AssistantAgent that acts as an HR assistant in the console.

> Part of my Gen AI course practice work (Week 5, Day 1).

## Tech stack

- Python 3
- Microsoft AutoGen (AgentChat)
- OpenAI (`gpt-4o-mini`)

## Features

- Async AssistantAgent named `hr_assistant`
- Streams the conversation in the console

## Getting started

1. Clone the repository:
   ```bash
   git clone https://github.com/Prembazskar/autogen-hr-assistant-agent.git
   cd autogen-hr-assistant-agent
   ```
2. Install and configure:
   ```bash
   pip install -r requirements.txt
   cp .env.example .env   # then add your OpenAI key
   ```

Environment variables (set in `.env`, never commit it):

- `OPENAI_API_KEY`

## Usage

```bash
python hr_agent.py
```

## License

MIT, see [LICENSE](LICENSE).
