curl -X POST "http://localhost:4000/v1/chat/completions" -H "Content-Type: application/json" -H "Authorization: Bearer sk-litellm-master-key" -d "{\"model\":\"github_copilot/gpt-5.1-codex\",\"messages\":[{\"role\":\"user\",\"content\":\"Say hello from GitHub Copilot via LiteLLM.\"}]}"


{
  "env": {
    "ANTHROPIC_BASE_URL": "http://localhost:4000",
    "ANTHROPIC_AUTH_TOKEN": "sk-litellm-master-key",
    "ANTHROPIC_MODEL": "claude-sonnet-4-6",
    "ANTHROPIC_SMALL_FAST_MODEL": "claude-haiku-4-6",
    "DISABLE_NON_ESSENTIAL_MODEL_CALLS": "1",
    "CLAUDE_CODE_DISABLE_NONESSENTIAL_TRAFFIC": "1"
  },
  "alwaysThinkingEnabled": false
}}"
