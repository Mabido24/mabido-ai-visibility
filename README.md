# MABIDO AI Visibility Check — Claude plugin

A read-only checker for small-business websites: is the site easy for AI assistants to understand?

Ask Claude: *"Check whether https://example-bakery.com is visible to AI assistants."*
You get a pass/fail checklist (structured data, FAQ, llms.txt, sitemap, robots rules, freshness, consistency) and the five fixes that matter most.

- Reads public pages only. Submits nothing, logs in nowhere, changes nothing.
- No tracking, no account.
- Honest by design: it measures readiness, it does not promise rankings.

Made by [MABIDO](https://mabido.com). Optional full audit: https://mabido.com/visibility-audit?utm_source=claude_plugin&utm_medium=plugin&utm_campaign=ai_visibility_check

## Install
```
/plugin marketplace add Mabido24/mabido-ai-visibility
/plugin install mabido-ai-visibility@mabido
```

## Privacy

This plugin collects, stores and transmits **no data**.

- It reads only the public pages of the website you ask Claude to check (including the business name, address and phone number that site publishes, to compare them with each other).
- It runs no shell command, logs in nowhere, and sends nothing to MABIDO or to any third party.
- Nothing is saved: the result is shown in your own conversation and nowhere else.
- The only link it shows is an optional pointer to MABIDO's free audit. Clicking it is your choice; MABIDO's own site privacy policy then applies: https://mabido.com/privacy

Questions: admin@mabido.com

MIT licensed.
