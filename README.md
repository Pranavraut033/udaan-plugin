# Udaan plugin for Claude Code

Connects Claude Code (or any plugin-aware host) to the [Udaan](https://github.com/Pranavraut033/resume-builder) desktop app's local MCP server: parse jobs, tailor resumes, Deep Analysis, Fit Check, cover letters, all against your local data.

## Install

1. Install the Udaan desktop app and **open it once**. That writes the launcher this plugin runs (`~/.udaan/bin/udaan-mcp`).
2. In Claude Code:

   ```
   /plugin marketplace add Pranavraut033/udaan-plugin
   /plugin install udaan@udaan
   ```

The app doesn't need to be open afterwards. Everything stays on your machine.
