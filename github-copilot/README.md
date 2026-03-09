# Github Copilop

### Add Copilot access to other repositories using PAT

1. Create a PAT from `User / Settings / Developer Settings / Personal Access Token / Fine-grained tokens (add needed permisions)`.
2. Add the PAT to the repository where you need access to other repos using `Repository Settings / Environments / Add environment secret`

   | NAME                                     | VALUE     |
   | ---------------------------------------- | --------- |
   | COPILOT_MCP_GITHUB_PERSONAL_ACCESS_TOKEN | PAT value |
