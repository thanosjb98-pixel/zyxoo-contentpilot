# Zyxoo The ContentPilot

**AI Content Creator Studio · Taglish creator copilot**

Zyxoo helps Filipino creators turn rough ideas into production-ready content drafts and prompts. The package includes a content-production skill and the bundled `ContentPilot_Knowledge_Base.md` playbook.

## Included workflows

- Affiliate short-video scripts, product angles, calls to action, and disclosure reminders
- AI drama series structure, character profiles, image prompts, and motion prompts
- TikTok, Facebook Reels, and Shorts scripts and shot lists
- Weekly content calendars and faceless YouTube planning
- Repurposing, hooks, captions, and hashtag planning
- Safety reminders for truthful claims, copyright, AI disclosure, and platform rules

## Repository layout

```text
.agents/plugins/marketplace.json
plugins/ai-content-creator-studio/
  plugin.json
  .codex-plugin/plugin.json
  assets/zyxoo-contentpilot-icon.png
  skills/content-production/SKILL.md
  skills/content-production/references/ContentPilot_Knowledge_Base.md
```

## Try it from this repository

This repository includes a repo-scoped marketplace catalog at `.agents/plugins/marketplace.json`.

For supported ChatGPT desktop / Codex local-marketplace workflows:

1. Clone or download this repository.
2. Open the repository in the supported desktop environment.
3. Add or select the repo marketplace source if it is not discovered automatically.
4. Restart the desktop app, open the Plugins Directory, choose **Zyxoo Creator Tools**, and install **Zyxoo The ContentPilot**.

Availability varies by client and account. A GitHub repository does not automatically publish a plugin in the universal public directory.

## Share with friends

You can share the standalone plugin ZIP alongside this repository. A recipient can use it only if their ChatGPT/Codex account and client expose a compatible plugin upload or local installation flow. Simply sending a private ChatGPT plugin URL will not grant access.

## Public ChatGPT directory publication

The repository is prepared as a starting point, not a published listing or approval. To publish in the universal directory, use the official plugin submission flow, complete developer verification, review the listing and policy requirements, upload the standalone plugin ZIP, resolve automated findings, and submit for review. Approval and publication are separate steps.

Before public submission, confirm:

- The public developer identity matches the verified identity selected in the submission portal. The current package uses the existing project author label `jb thanos`; this has not been verified here.
- A published privacy policy accurately explains actual data handling. This package contains skills and reference text, with no bundled MCP server or external API integration.
- A working support contact/page and any other listing details required by the portal.
- Country availability and whether the plugin involves payments or purchases.
- The icon, listing copy, and package contents in the final submission portal.

Do not add passwords, API keys, tokens, or private reviewer credentials to this repository.

## Scope and limitations

This is a skills-and-knowledge package. It generates drafts and prompts; it does not itself upload or publish social posts, access TikTok Shop accounts, fetch live product listings, or guarantee views, sales, or income. Users must verify product claims, affiliate disclosures, permissions, music/footage rights, and current platform rules.

## Version

Distribution package: **0.3.1**. Core content-production skill and knowledge base are carried forward from the private v0.3.0 plugin release.

## License

No open-source license has been selected or included. Do not assume the contents are licensed for unrestricted reuse or redistribution beyond the sharing permission granted by the author.
