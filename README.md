# AI Tool Setup Project

## Overview
This repository documents the setup process for AI development tools and the troubleshooting steps involved during installation and configuration.

---

## Tools Installed

- Cursor IDE
- GitHub
- Git
- Node.js
- Claude Code CLI
- OpenAI Codex CLI

---

## Steps Completed

### 1. Installed Cursor IDE
- Downloaded and installed Cursor IDE successfully.
- Explored the interface and extension marketplace.

### 2. Attempted Marketplace Installation
- Searched for:
  - Claude Code
  - Codex
- The extensions were not available in the Cursor Marketplace search results.

### 3. Researched Alternative Installation Methods
- Investigated documentation and community discussions regarding Cursor extension availability.
- Found that current installation workflows use npm-based CLI installations instead of marketplace extensions.

### 4. Installed Node.js
- Installed the latest LTS version of Node.js to enable npm package management.

### 5. Installed Claude Code CLI
Used the following command:

```bash
npm install -g @anthropic-ai/claude-code
```

### 6. Resolved PowerShell Execution Policy Issue
Encountered a PowerShell security restriction preventing npm scripts from running.

Resolved temporarily using:

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

### 7. Verified Claude Code Installation
- Successfully launched Claude Code through terminal commands.
- Verified installation and CLI accessibility.

### 8. Installed OpenAI Codex CLI
Used npm to install Codex successfully.

### 9. Configured Sandbox Environment
- Completed Codex authentication and sandbox configuration.
- Selected non-admin sandbox mode for safer local execution.

### 10. Created GitHub Repository
- Created a public GitHub repository for documentation and portfolio purposes.

---

## Issues Encountered

### Extension Marketplace Availability
- Claude Code and Codex were not visible in the Cursor Marketplace search results.

### PowerShell Security Restriction
- npm commands initially failed due to PowerShell execution policy restrictions.

---

## Solutions

### Alternative Installation Workflow
- Researched updated installation methods using npm CLI tools.

### PowerShell Fix
- Temporarily bypassed execution policy restrictions for the current terminal session only.

---

## What I Learned

- Basic AI development environment setup
- npm package installation workflows
- Terminal and CLI usage
- PowerShell execution policies
- Sandbox security concepts
- Troubleshooting and documentation practices

---

## Status

All required tools were successfully installed and configured.
