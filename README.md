# AI Thinker
An experiment to "fine-tune" AI through intellectual discussion.

## Reference Setup
The following is the setup I use. I believe they can be easily swapped.

- Model : gpt-oss:20b
  - Reasons: 
    - Free
      - Locally using [ollama](https://ollama.com) or similar tools.
      - [OpenRouter](https://openrouter.ai/openai/gpt-oss-20b:free) as of 16/Aug/2025).
    - Has reasoning capability
- Chat Tool: (aider)[https://aider.chat/]
  - Reasons:
    - Has filesystem access out of box without having to setup agent.
    - Can search the web.
  - Command: 
    - aider --no-auto-commit --model openrouter/openai/gpt-oss-20b:free

## Workflow
- Initiate the chat session by telling the AI to use the content from `SYSTEM.md` as prompt.
- As you interact with the LLM, the chat tool is supposed to update `AIBRAIN.md` automatically.
