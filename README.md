model_list:
  - model_name: claude-sonnet-4-6
    litellm_params:
      model: github_copilot/gpt-4o
      extra_headers:
        Editor-Version: "vscode/1.99.0"
        Copilot-Integration-Id: "vscode-chat"

  - model_name: claude-haiku-4-6
    litellm_params:
      model: github_copilot/gpt-4o
      extra_headers:
        Editor-Version: "vscode/1.99.0"
        Copilot-Integration-Id: "vscode-chat"

general_settings:
  master_key: sk-litellm-master-key
