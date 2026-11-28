# MA3 Pro Plugins marketplace

The plugin marketplace for **MA3 Vibe**, which lets Claude Code work on a grandMA3 show with you. It is a beta for invited testers. After installing, the console tools and the knowledge base need a sign-in and beta access.

## Install

In the Claude desktop app: **Plugins** → **Add** → **Add marketplace** → **Add from a repository**, enter `ma3-pro-plugins/marketplace` and click **Sync**. Then install **MA3 Vibe** from the plugin list.

In a terminal:

```text
claude plugin marketplace add ma3-pro-plugins/marketplace
claude plugin install ma3-vibe@ma3-pro-plugins
```

Then start a new Claude Code session and run `/ma3-vibe:connect`.

## What is here

Only `.claude-plugin/marketplace.json`. It names each plugin's current version and where its zip is downloaded from (`shop.ma3-pro-plugins.com`), pinned by the zip's SHA-256. Claude Code downloads the zip from there and checks it against the hash. The file is updated with each release.

More: https://shop.ma3-pro-plugins.com
