# Token Permissions

This doc details the minimum scopes/permissions needed for GitHub/Azure DevOps tokens needed to use this template, along with reasons why.

## GitHub

### Personal Access Tokens (classic)

**Scope** | **Reason**
---|---
repo | Needed to create repo & set its settings
workflow | Needed to allow template tasks to commit workflows

### Fine-grained tokens

**Permission** | **Reason**
---|---
administration:write | Needed to create repo & set its settings
issues:write | Needed to create custom labels
workflows:write | Needed to allow template tasks to commit workflows

## Azure DevOps

**Scope** | **Reason**
---|---
code:full | Needed to create repo & set its settings
release:read, write, execute, & manage | Needed to create pipelines