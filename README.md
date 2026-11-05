# Baseline for ChatGPT

Baseline is a personal health log for meals, workouts, goals and Apple Health summaries. This plugin connects ChatGPT to your Baseline account through the Baseline MCP server and adds skills for logging meals, weekly reviews and workout planning.

## Set up

1. In https://chatgpt.com/plugins press +, choose Add custom MCP server, enter https://baseline.chaitanyabhagwat.com/api/mcp with OAuth, and choose Create as a plugin.
2. Copy the `plugin_asdk_app...` ID from the browser URL and add it to `.app.json` (or run `@plugin-creator` with that ID).
3. Start a new chat, type @, pick Baseline, and try the default prompts.

## Data

Requests go to your Baseline account through https://baseline.chaitanyabhagwat.com/api/mcp, signed in with OAuth. The plugin reads and writes your food log, routines, goals and health summaries there and stores nothing itself.
