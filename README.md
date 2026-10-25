# ingest-web-chat

Ingest a single web LLM chat (ChatGPT, Claude.ai, Gemini, or any other
chat URL) into markdown. Drives a real Chrome over CDP so enterprise
SSO and Cloudflare checks work.

Trigger on "ingest this chat", "import this ChatGPT/Claude/Gemini
conversation", "grab that chat URL", or any chat URL the user wants
captured.

## Install

```bash
pi install npm:@micuintus/ingest-web-chat
```

Extracted with history from
[`micuintus/llm-wiki`](https://github.com/micuintus/llm-wiki), where it
shipped as a nested subskill.
