# ClaudeCodeWorking

## How to Use Claude Code in Your Project

Follow these steps to configure Claude Code with OpenRouter:

### Steps to Configure

1. **Create `.claude` folder** in your project root

2. **Create `settings.local.json`** inside the `.claude` folder

3. **Add the following configuration** to `settings.local.json`:

```json
{
  "env": {
    "ANTHROPIC_BASE_URL": "https://openrouter.ai/api",
    "ANTHROPIC_AUTH_TOKEN": "<Your KEY >",
    "ANTHROPIC_API_KEY": "",
    "ANTHROPIC_MODEL": "nvidia/nemotron-3-super-120b-a12b:free"
  }
}
```

### Configuration Details

| Setting | Description |
|---------|-------------|
| `ANTHROPIC_BASE_URL` | OpenRouter API endpoint |
| `ANTHROPIC_AUTH_TOKEN` | Your OpenRouter API key |
| `ANTHROPIC_API_KEY` | Leave empty when using OpenRouter |
| `ANTHROPIC_MODEL` | Model to use (nvidia/nemotron-3-super-120b-a12b:free) |

### Getting Your API Key

1. Visit [OpenRouter](https://openrouter.ai/)
2. Sign up or sign in
3. Go to API Keys section
4. Create a new API key
5. Replace `<Your KEY >` in the configuration with your actual key
