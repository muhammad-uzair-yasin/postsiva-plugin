# Postsiva — Claude plugin

Create, schedule, draft and publish social posts and blog articles across **LinkedIn, Instagram,
Facebook, TikTok, YouTube, Threads, Bluesky, Pinterest, Mastodon, WordPress, Blogger, Dev.to and
Tumblr** — written in your brand's own voice, from Claude.

This plugin bundles a **skill** (how Claude should use Postsiva) and a reference to the **Postsiva MCP
connector** (`https://mcp.postsiva.com/apps/mcp`). It pairs with the standalone "Postsiva" connector in
the Claude directory — install either; together they give one clean set of tools.

## What it can do
- List your connected accounts
- Publish, schedule or draft a post to one or many platforms in a single step
- Publish long-form blog articles
- Manage scheduled posts and drafts; reply to comments
- Read posts, comments and analytics
- Upload media and get a shareable URL
- Use your Postsiva brand persona, memories and per-platform writing skills so content sounds like you

Publishing, scheduling and replies are confirmed before they run. This plugin does **not** run ads or
spend money.

## Requirements
A Postsiva account (free to start) with at least one channel connected at
[postsiva.com](https://www.postsiva.com) → Accounts. Sign-in is via secure OAuth.

## Install
- **In Claude:** install the **Postsiva** plugin from the directory, or add the connector directly:
  Settings → Connectors → Add custom connector → `https://mcp.postsiva.com/apps/mcp`.
- **Claude Code:**
  ```
  /plugin marketplace add muhammad-uzair-yasin/postsiva-plugin
  /plugin install postsiva@postsiva-plugin
  ```

## Structure
```
.claude-plugin/plugin.json   # manifest
.mcp.json                    # references the Postsiva MCP connector (/apps/mcp)
skills/postsiva/SKILL.md     # how Claude uses the tools
```

## Privacy & terms
- Privacy Policy: https://www.postsiva.com/privacy
- Terms: https://www.postsiva.com/terms-and-conditions
- Docs: https://docs.postsiva.com/integrations/claude
- Support: admin@postsiva.com

Postsiva collects only what's needed to publish and manage content on the accounts you connect; data
use, storage, third-party sharing, retention and contact details are described in the Privacy Policy
linked above.
